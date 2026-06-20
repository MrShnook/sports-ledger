# SportsLedger — Tech Stack Definition

*Author: Mr. Shnook*
*Date: 2026-03-25*

## 1. Project Requirements Summary

Based on the initial venture brief, SportsLedger needs to be a web application that allows parents to:
- Create accounts and manage profiles for their children.
- Log expenses related to youth sports (e.g., team fees, uniforms, travel).
- Categorize expenses by child, sport, and type.
- View dashboards and reports summarizing their spending.
- Securely store and retrieve their data.

This implies the following technical needs:
- **Frontend:** A responsive and interactive user interface.
- **Backend:** API endpoints for CRUD (Create, Read, Update, Delete) operations on expenses, users, etc.
- **Database:** A relational database to store user data, expenses, and categories.
- **Authentication:** A secure way for users to sign up, log in, and manage their accounts.
- **Deployment:** A reliable and scalable hosting solution.

## 2. Proposed Tech Stack

I propose the following tech stack, leveraging modern, efficient, and familiar tools to maximize development velocity and scalability. This stack is nearly identical to the one used for the "Study Scheduler" project, which will allow for rapid development due to high familiarity.

| Component | Technology | Rationale |
|---|---|---|
| **Framework** | **Next.js (App Router)** | A full-stack React framework that provides a robust structure for both frontend and backend development. Its server components, API routes, and static/dynamic rendering capabilities are a perfect fit. |
| **Styling** | **Tailwind CSS + shadcn/ui** | Tailwind CSS allows for rapid UI development with utility-first classes. `shadcn/ui` provides a set of beautifully designed, accessible, and un-opinionated components that can be easily customized. |
| **Database** | **Neon (Serverless Postgres)** | A modern, serverless PostgreSQL provider that is easy to set up, scales automatically (including to zero), and offers a generous free tier. It integrates perfectly with Vercel. |
| **ORM** | **Drizzle ORM** | A lightweight, TypeScript-native ORM that provides excellent type safety and performance. It's less bulky than Prisma and has a more SQL-like feel, which is great for query construction. |
| **Authentication** | **Clerk** | A complete user management solution that handles sign-up, sign-in, multi-factor authentication, and profile management out of the box. Its integration with Next.js is seamless and saves weeks of development time. |
- **Deployment** | **Vercel** | The ideal platform for deploying Next.js applications. It provides seamless Git integration, automatic CI/CD, and a global CDN for optimal performance. (Note: Matt needs to resolve the `limited:true` issue on his account for this to be fully effective). |

## 3. Alternatives Considered

| Category | Alternative | Reason for Not Choosing |
|---|---|---|
| **Database** | Supabase, Firebase | While excellent platforms, Neon + Drizzle provides a more focused, SQL-centric approach that aligns well with the relational nature of the data. Supabase is a strong contender, but Neon's simplicity is compelling for a new project. |
| **ORM** | Prisma | Prisma is a fantastic ORM, but Drizzle is lighter, faster, and its TypeScript-first approach feels more modern and provides tighter type safety. |
| **Authentication** | NextAuth.js, Lucia | These are great open-source options but require significantly more manual setup for things like UI components, email verification, and social logins. Clerk provides a more complete, out-of-the-box solution, accelerating development. |
| **Backend** | Standalone Express/Fastify API | A separate backend would add complexity to development and deployment. Next.js API routes provide a simpler, more integrated solution for this project's scale. |

## 4. Next Steps

1.  Gain Matt's approval on this proposed stack.
2.  Once approved, create the initial project scaffold using `create-next-app`.
3.  Set up the Neon database and connect it to the project.
4.  Integrate Clerk for authentication.
5.  Begin building out the core database schema using Drizzle.
