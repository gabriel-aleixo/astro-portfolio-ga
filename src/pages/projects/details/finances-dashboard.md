---
layout: ../../../layouts/ProjectDetail.astro
title: Finances Dashboard
description: A proof of concept for a personal finance dashboard that aggregates data from accounts in various financial institutions using the Yapily API
tech: ["Next.js", "TypeScript", "Prisma", "SQLite", "Tailwind CSS"]
link: https://github.com/gabriel-aleixo/finances-dashboard-nextjs-prisma
date: 2024-03-15
featured: true
images:
    - /src/images/project-images/finances-dashboard/1.webp
    - /src/images/project-images/finances-dashboard/2.webp
---

## The Problem

The goal was to create a proof of concept for a dashboard for a Berlin-based tech startup that could automatically aggregate financial data from various institutions using the Yapily API, providing users with a unified view of their finances.

## Key Features

- **Multi-Bank Integration**: Seamless connection to multiple financial institutions through the Yapily API
- **Data Aggregation**: Centralized view of accounts and transactions across different banks
- **Responsive Design**: Clean, modern interface that works well on both desktop and mobile devices
- **Type-Safe Development**: Full TypeScript implementation ensuring code reliability and maintainability

## Tech Decisions

I used Next.js to align with the company's existing stack. The excellent developer experience and built-in features like server-side rendering and API routes allowed for efficient data fetching and processing while maintaining good performance.

For the database layer, I implemented Prisma with SQLite for development and testing. This combination provided a robust ORM with type safety and easy database migrations. The choice of SQLite made it simple to get started, though the architecture is designed to be easily switched to PostgreSQL for production.

Tailwind CSS was selected for styling, enabling rapid development of a responsive and consistent UI while keeping the bundle size minimal.

## Interesting Challenge

One of the most interesting challenges was obtaining realistic test data for development. To properly test the dashboard's functionality and UI, I needed to simulate different scenarios with varying levels of information density, transaction history length, and data complexity.

To solve this, I leveraged an LLM trained on the project's data structures to rapidly generate verosimil test data. This allowed me to create realistic mock data that included:

- Diverse transaction histories with varying frequencies and amounts
- Multiple account types with different balance ranges
- Complex transaction descriptions and categories
- Edge cases and unusual patterns

This approach enabled rapid iteration on both the backend data processing and frontend visualization components while maintaining a high degree of realism in the development environment.

## What's Next?

This project served as a solid proof of concept for the rapid developement and implementation of the user interface. However, the collaboration with the startup didn't evolve and the project wasn't further developed.