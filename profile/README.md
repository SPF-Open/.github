# 👋 Welcome to the TAO Automation Platform

Welcome to the GitHub organization of the **FPS Finances P&O Testing Team**.

This organization hosts the source code for the **TAO Automation Platform**, a suite of tools designed to automate, simplify, and improve TAO-related workflows. Our goal is to reduce manual effort, improve reliability, and provide a unified experience for assessment management.

## 🌐 Access the Platform

The platform is accessible through a central portal:

🔗 **[Open TAO Portal](https://tao.lv0.eu)**

The portal serves as a central entry point for all available tools, their documentation, and the release changelog.

---

## 🛠 Available Tools

| Tool | Description | Link |
|---|---|---|
| **Import** | Turn an Excel workbook into a clean TAO question set — map columns, preview content, and export. | [Open ↗](https://tao.lv0.eu/import) |
| **Forge** | Create and schedule exams from scratch or using templates, with multilingual support. | [Open ↗](https://tao.lv0.eu/forge) |
| **Format** | Wrap every question prompt in a TAO QTI export in bold, ready for re-import. | [Open ↗](https://tao.lv0.eu/format) |
| **Editor** | Edit any question in a TAO QTI export — prompts, answers, limits, and metadata — using a form-based interface or raw XML. | [Open ↗](https://tao.lv0.eu/editor) |
| **Export** | Convert ZIP exam archives into printable reports and structured result tables. | [Open ↗](https://tao.lv0.eu/export) |
| **Audit** | Compare a TAO export against its original Excel source and flag discrepancies by severity. | [Open ↗](https://tao.lv0.eu/audit) |
| **IAT** | Perform post-exam item analysis, including difficulty, discrimination, and distractor statistics. | [Open ↗](https://tao.lv0.eu/iat) |
| **Library** | Build a portable SQLite question bank from TAO exports and search it instantly — entirely in the browser. | [Open ↗](https://tao.lv0.eu/library) |

Every tool comes with its own documentation, accessible through the portal or directly from the [📖 Documentation Hub](https://tao.lv0.eu/docs).

Release history is available in the [Changelog](https://tao.lv0.eu/changelog).

---

## 🏗 Platform Architecture

The platform is built as a unified **SvelteKit** application, with each tool organized into its own dedicated route.

```text
tao.lv0.eu
├── /            Portal & navigation
├── /import      Excel → TAO question sets
├── /forge       Exam composer & scheduler
├── /format      QTI prompt formatting
├── /editor      Full QTI question editor
├── /export      ZIP → PDF/JSON result tables
├── /audit       Consistency checks against Excel source
├── /iat         Post-exam item analysis
├── /library     In-browser question bank
├── /docs        Documentation hub (per-tool + stack)
├── /changelog   Release history
└── /slides      Product presentation
```

This architecture provides:

- Centralized access to all tools.
- A shared design system and reusable components.
- A consistent user experience across the platform.
- Simplified deployment and maintenance.
- Faster development through a shared codebase.

---

## 🚀 Technology Stack

- **Framework:** SvelteKit 2 + Svelte 5
- **Language:** TypeScript
- **Styling:** Tailwind CSS 4
- **Testing:** Vitest & Playwright (unit and end-to-end tests)
- **Deployment:** Cloudflare Pages
- **Runtime:** Node.js

---

## 🎯 Objectives

The TAO Automation Platform aims to:

- Automate repetitive and time-consuming tasks.
- Improve operational efficiency.
- Reduce manual errors.
- Centralize assessment-related tools.
- Provide a consistent and intuitive user experience.
- Support reliable and maintainable assessment workflows.

---

## 🤝 Contributing

Contributions from team members are welcome.

Before submitting changes:

1. Create a feature branch.
2. Follow the project's coding standards.
3. Ensure all relevant tests pass.
4. Open a Pull Request for review.

---

## 📬 Support

For questions, bug reports, or feature requests, please open an issue in the relevant repository or contact Benoit Welsch.

---

<p align="center">
  Built with ❤️ by Benoit Welsch
</p>
