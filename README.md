This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
pnpm run dev
```

Open [http://localhost:1234](http://localhost:1234) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## 🛠 Project Configuration Overview

This project is built with **Next.js**, **TypeScript**, and **Tailwind CSS**. It also includes configurations for code linting, formatting, and consistent development workflows.

### 📦 Tech Stack

- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Package Manager**: pnpm
- **Linting**: ESLint
- **Formatting**: Prettier
- **Hooks & Git Integration**: Husky

---

### 📁 Project Config Files

| File                    | Purpose                                                                 |
|-------------------------|-------------------------------------------------------------------------|
| `.editorconfig`         | Ensures consistent editor behavior across IDEs (indent style, line endings) |
| `.prettierrc`           | Defines formatting rules for Prettier                                   |
| `eslint.config.mjs`     | Modern ESLint config using flat config format                           |
| `.gitattributes`        | Handles Git's text normalization, particularly line endings             |
| `.husky/`               | Contains Git hooks to enforce checks like linting before commits        |