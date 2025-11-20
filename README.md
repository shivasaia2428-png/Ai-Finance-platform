**AI Finance Platform**

A modern, AI-powered personal finance management platform built with Next.js, TailwindCSS, ShadCN UI, Prisma, and Google Gemini AI.
This project provides intelligent financial insights, automated data extraction, and beautifully designed dashboards to help users understand and manage their finances effortlessly.
This platform enables users to manage accounts, track transactions, scan receipts with AI, and automatically generate monthly insights. It includes secure authentication, real-time UI updates, automated background jobs, and rate-limited endpoints for production-level security.
The project follows industry best practices in architecture, file structure, UI design, and API development.

**Project Structure**
actions/            # Server actions for business logic (Next.js)
app/                # App router pages & layouts
components/         # Reusable UI components
components.json     # ShadCN component config
data/               # Static or mock data
emails/             # Email templates
hooks/              # Reusable React hooks
lib/                # Utility functions, API clients, helpers
prisma/             # Prisma schema & migrations
public/             # Static assets (icons, images, etc.)
middleware.js       # Auth / middleware logic
next.config.mjs     # Next.js configuration
package.json        # Dependencies
tailwind.config.js  # TailwindCSS config
postcss.config.mjs  # PostCSS config


Tech Stack
**Frontend**

Next.js (App Router)

React

TailwindCSS

ShadCN UI

TypeScript

Client + Server Components

Zod validation (commonly used with ShadCN)

**Backend**

Next.js Server Actions

Prisma ORM

PostgreSQL (used in the video & Prisma)

API Routes / Server Components

**AI / Automation**

Google Gemini AI (as shown in video)

AI Receipt Scanner

AI Monthly Insights Generator

Inngest (for cron jobs / background tasks)

**Security**

Middleware-based route protection

Rate limiting (Arcjet)

Form validation using Zod

Strict type safety through Prisma + TS

**Emails**

Email templates (via Resend / Nodemailer depending on your setup)

**DevOps / Deployment**

Vercel

Environment variables via .env

Optimized build with Next.js
--------------------------------------------------------------------------------------------------------

**Features**
**Secure Authentication**

Login and registration flow

Protected routes via middleware.js

Session management

Production-ready security

**Finance Dashboard**

View account balances

Track income & expenses

Visual charts & analytics

Transaction history

Filters & sorting

**AI-Powered Tools**

Receipt Scanner using Gemini AI

Automatically extract:

Merchant

Amount

Date

Category

AI Monthly Insights report generation

Smart recommendations

**Database & Backend**

Fully typed ORM with Prisma

Postgres schema

Database migrations

Server Actions for business logic

Audit-safe database operations

**Automated Background Jobs**

Using Inngest

Monthly insights generation

Budget alerts

Routine maintenance tasks

Automated report delivery

**Security**

Arcjet rate limiting (from video)

Field-level validation

Zod schemas

Secure API endpoints

**Modern UI/UX**

Built with:

ShadCN UI

TailwindCSS

Responsive layouts

Consistent component structure

Dark/light mode support

**Infrastructure**

Vercel-ready deployment

Image upload support

Environment-safe config

Optimized API routes



