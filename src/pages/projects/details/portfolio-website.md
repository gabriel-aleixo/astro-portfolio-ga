---
layout: ../../../layouts/ProjectDetail.astro
title: This Website
description: A modern, performant portfolio website built with Astro, focusing on clean design and optimal user experience. Built using Astro and well structured HTML and CSS, it features a clean and responsive design, optimized for exceptional performance and a great user experience on both desktop and mobile devices.
tech: ["Astro", "TypeScript", "Tailwind CSS", "Netlify"]
link: https://github.com/gabriel-aleixo/astro-portfolio-ga
date: 2025-02-01
featured: false
images:
    - /src/images/project-images/portfolio-website/1.svg
---

## The Problem

Creating a professional portfolio website that balances aesthetics, performance, and maintainability can be challenging. Many portfolio sites either sacrifice performance for visual appeal or compromise on design for better loading times. The goal was to build a website that excels in both areas while remaining easy to maintain and extend.

## Key Features

- **Performance-First**: Optimized for speed with minimal JavaScript and efficient asset loading
- **Responsive Design**: Clean, functional layout that works seamlessly across all devices
- **Project Showcase**: Detailed project pages with image carousels and technical information
- **Dark Mode**: Built-in dark mode support with system preference detection
- **SEO Optimized**: Proper meta tags and semantic HTML for better search engine visibility
- **Automated Deployment**: Continuous deployment pipeline with GitHub and Netlify

## Tech Decisions

I chose Astro as the core framework for its excellent performance characteristics and content-focused approach. The framework's partial hydration model allows for minimal JavaScript usage while maintaining interactivity where needed.

TypeScript was implemented for type safety and better developer experience, while Tailwind CSS provided consistent styling while keeping the codebase clean and maintainable.

For deployment, I chose Netlify for its excellent developer experience and GitHub integration. The setup includes automated deployment from Github, ensuring consistent quality across updates.

## Interesting Challenge

I decided to build an image carousel using only HTML and CSS, without relying on any JavaScript frameworks. This was a fun exercise in going back to basics in a time where I was used to rely on tools like React and Next.js for most projects.

The implementation involved:

- Lazy loading of images
- Optimized image formats and sizes
- Smooth scrolling behavior
- Touch-friendly navigation
- Minimal JavaScript usage

## What's Next?

The current version of the portfolio website provides a solid foundation for showcasing projects and professional information. Future improvements could include:

- Blog section for sharing technical insights
- Interactive project demos
- Multi-language support
- Integration with a headless CMS for easier content management

I really enjoyed building this website and more and more I'm chosing simpler and more performant solutions like this one for my projects.