---
layout: ../../../layouts/ProjectDetail.astro
title: BIRCON Sessions App
description: A scheduling web-app that lets participants enroll for games sessions at the Berlin International RPG Conference
tech: ["Astro", "TypeScript", "Supabase", "Postgres"]
link: https://github.com/yourusername/project-one
date: 2024-10-01
featured: true
images:
    - /src/images/project-images/scheduling-app/image1.jpeg
    - /src/images/project-images/scheduling-app/image2.jpeg
    - /src/images/project-images/scheduling-app/image3.jpeg
    - /src/images/project-images/scheduling-app/image4.jpeg
    - /src/images/project-images/scheduling-app/image5.jpeg
---

## The Problem

<a href="https://bircon.berlin" target="_blank">BIRCON</a> needed a quick solution to manage 20+ gaming sessions for Berlin's first international RPG conference. The challenge? Build a system in just 4 weeks that would help attendees browse sessions, sign up, and avoid scheduling conflicts.

## Key Features

- **Ticket Holder Authentication**: A simple passwordless authentication method based on the email used to purchase tickets, to simplify the user experience
- **Quick Browse**: Streamlined interface insipired by the visual identity of popular RPG books, offering users a familiar and easy to use app.
- **Cost Efficient**: The entire application was hosted using free services, saving budget for the conference itself.

## Tech Decisions

I chose Astro for its speed and simplicity, which allowed me to build a performant and accessible web application, optimized for mobile and web. TypeScript offered type safety to reduce errors and testing cycles.

For the backend, I used Supabase to handle user authentication and data storage. We used email based passwordless authentication, to simplify the user journey.

Since Supabase is built on Postgres, I used the database's native security features and functions to protect and query data, keeping the solution clean and secure.

## Interesting Challenge

While the app allowed attendees to register their preferences for game sessions they wanted to join, the final allocation of players was handled separately by the team.

The organizers initially planned to manually allocate players according to preferences, to guarantee everyone would have at least one spot in a game they wanted. This proved to be a quite complicated puzzle to crack.

I used AI to go through a step-by-step process of organization and classification of the raw data, using by my knowledge of ranked-preference techniques common in market research. Given correct an specific prompts, the model was able to allocate the bulk of participants, respecting the restrictions and rules I defined.

The main limitation came from the size of the context window I had access to. With enough memory, the LLM was able to solve the puzzle, and the exercise served as a proof-of-concept for the development of an automated algorithm for the next version of the app. 

## What's Next?

BIRCON 2024 was a huge success and the app managed signups for all the game sessions in a simple and friendly way. We're now expanding it into a full event management platform for the 2025 edition of conference, adding ticketing and profile features to support a much lager event.
