---
title: Project Structure
sidebar_position: 3
---

# Project Structure

Overview of the core folders and files:

```
/
├── app/ → App router-based pages and layouts
├── components/ → Reusable UI components
├── lib/ → Utilities and helpers
├── styles/ → Global CSS (e.g., tailwind.css)
├── public/ → Static assets
├── tests/ → E2E and unit tests
├── .eslintrc.js → Linter config
├── tailwind.config.ts
├── tsconfig.json
```

- Uses the **App Router** (`app/`) for routing.
- Code-split components via `components/`.
