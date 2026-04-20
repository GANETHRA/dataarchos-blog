---
title: Hello
date: 2026-04-20
---

# Data Archos Identity Platform

A modern Identity and Access Management (IAM) platform built with a monorepo architecture using Bun workspaces.

## 📁 Project Structure

```plain
identity-platform/
├── api/                  # Backend API (Hono + Drizzle ORM + Better Auth)
├── app/                  # Frontend Application (React + Vite + TanStack Router)
└── package.json         # Root package.json with Bun workspaces
```

## 🚀 Getting Started

### Prerequisites

- [Bun](https://bun.sh/) >= 1.0.0
- PostgreSQL database

![](https://picsum.photos/id/6/1920/1280.webp)

### Installation

```bash
# Install dependencies for all workspaces
bun install
```

### Development

```bash
# Run all workspaces in development mode
bun run dev

# Run API only
bun run dev:api

# Run App only
bun run dev:app
```
