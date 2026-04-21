---
thumbnail: /media/default_dark_compressed.4fd030c7.jpg
title: Data Archos Identity Platform
date: 2026-04-20
last_updated: ''
author: DA team
author_title: ''
category: Retail Intelligence
tags:
  - Artificial Intelligence
  - Retail Intelligence
  - Data Science
seo_title: ''
description: A modern Identity and Access Management (IAM) platform built with a monorepo architecture using Bun workspaces. A modern Identity and Access Management (IAM) .
focus_keyword: ''
canonical_url: ''
excerpt: A modern Identity and Access Management (IAM) platform built with a monorepo architecture using Bun workspaces. A modern Identity and Access Management (IAM) platform built with a monorepo architecture using Bun workspaces.
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

![](/media/default_dark_compressed.4fd030c7.jpg)

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
