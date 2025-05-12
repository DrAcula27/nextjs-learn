# Next.js Learn Projects

This repository contains code examples from the official [Next.js Learn](https://nextjs.org/learn) curriculum. Each project is a standalone Next.js application representing a different milestone in learning modern full-stack development with Next.js.

The structure of this repo follows a **monorepo** pattern to keep all projects centralized, organized, and easy to manage.

---

## Project Structure

```
nextjs-learn-projects/
├── nextjs-dashboard/
├── pages-router/
├── react-foundations/
├── seo/
└── shared-resources/
```

---

## 🚀 Courses

### 1. [React Foundations](./react-foundations)

Set up a basic Next.js application using `create-next-app`. Learn about file-based routing, React components, and static content rendering.

### 2. [Pages Router](./pages-router)

Learn how to use the Next.js `<Link>` component to handle client-side routing, and how to organize files in the `pages` directory.

### 3. [Next.js Dashboard](./nextjs-dashboard)

Implement dynamic routing with `getStaticPaths` and `getStaticProps`. Learn how to pre-render pages based on external data sources such as markdown files or an API.

### 4. [SEO](./seo)

Deploy your Next.js application using [Vercel](https://vercel.com), configure custom domains, and learn how Continuous Deployment (CD) works in practice.

---

## 🛠 Getting Started

Each course folder is a standalone project. To run any of them locally:

```bash
cd react-foundations # or any other course folder
npm install
npm run dev
```

Then visit `http://localhost:3000` in your browser.

## Lessons Learned

- File-based routing simplifies navigation logic and mirrors folder structure.
- Pre-rendering with getStaticProps/getStaticPaths improves performance and SEO.
- Client-side navigation with `<Link>` results in faster transitions without full page reloads.
- Incremental Static Regeneration (ISR) lets pages update after deployment without rebuilding the entire site.
- Deployment with Vercel is tightly integrated and optimized for Next.js projects.
- Modular folder structure helps manage scalable full-stack applications.

## Professional Use Cases

These projects may be simple, but the patterns and practices scale into real-world applications:

- Marketing or blog websites with fast, SEO-optimized content using static generation.
- Developer portfolios with dynamic routing and markdown-based content.
- Internal tools and dashboards built using Next.js API routes for backend logic.
- Jamstack apps that integrate headless CMS platforms or third-party APIs.
- Client-facing apps that benefit from SSR/ISR and fast navigation.

By understanding and applying these fundamentals, I can now confidently build and deploy full-stack web apps using modern React and serverless tools.

## Tools & Technologies

- `Next.js` — `React` framework with hybrid rendering support
- `React` — UI library for building reusable components
- `Vercel` — Zero-config deployment platform for Next.js
- `Markdown` & static assets — Used for data-driven pages
- `GitHub` — Version control and repository hosting
