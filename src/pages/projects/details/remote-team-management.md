---
layout: ../../../layouts/ProjectDetail.astro
title: Quiteoften
description: A people management platform to helps managers of remote workers keep their teams aligned, engaged and happy in a fraction of the time it takes them with their current tools
tech: ["Node.js", "Express", "React", "PostgreSQL", "Jitsi Meet", "SWR", "Bulma", "Sentry"]
link: https://github.com/gabriel-aleixo/quiteoften-v2-pub/
date: 2021-01-01
featured: true
images:
    - /src/images/project-images/remote-team-management/1.webp
    - /src/images/project-images/remote-team-management/2.webp
    - /src/images/project-images/remote-team-management/3.webp
---

## The Problem

In 2020, as the world rapidly shifted to remote work, managers faced unprecedented challenges in maintaining team alignment and engagement. Traditional management tools were ill-equipped for this new paradigm, often creating friction in workflows and requiring managers to juggle multiple platforms. Quiteoften was born from the need to help managers adapt to this new reality, leveraging best practices in people motivation, achievement, and growth to create a more effective remote team management solution.

## Key Features

- **People Management Framework**: A framework for managing people, based on the science of motivation, achievement and growth
- **Integrated Video Conferencing**: Seamless video calls powered by Jitsi Meet, allowing teams to connect face-to-face without switching platforms
- **Action Item Management**: Track and manage tasks with features for adding, removing, reordering, and marking items as complete
- **Discussion Tracking**: Capture and organize important points from meetings with the ability to add, remove, and share discussion items
- **Role-Based Access**: Separate interfaces for managers and employees, ensuring manager could easily manage their entire team

## Tech Decisions

The project was built with Node.js and Express for the backend, React for the frontend, and PostgreSQL for data storage. We used SWR for efficient real-time updates and data fetching, while Bulma provided a clean and customizable UI framework.

Sentry handled error tracking and monitoring, and Jitsi Meet integration enabled high-quality video calls without requiring custom video infrastructure.

## Interesting Challenge

One of the key challenges was integrating video calls with action item and discussion tracking features. We needed team members to seamlessly transition between video discussions and task management without losing context.

The solution involved real-time synchronization between video and task tracking components. We implemented a queue system for action items and discussions that could be accessed during or after calls, ensuring important points were captured effectively.

## What's Next?

Quiteoften ran as a B2B SaaS startup from 2020 to 2022, during which time we successfully developed and launched the core platform and acquired paying customers. The project has now been shut down, but it was an invaluable experience in building, launching and iterating on a product to find product-market fit.

Back in 2021, we envisioned several features for this product that have since become standard in collaboration systems. These include meeting transcripts, automatic action item detection, and summarization of decisions made during virtual meetings.

The platform demonstrated the potential for integrating video conferencing with task management in a way that reduced friction for remote teams. While the project is no longer active, the insights gained from its development and operation continue to inform my decisions about effective product developement and remote team management practices.
