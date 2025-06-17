---
layout: ../../../layouts/ProjectDetail.astro
title: PizzaVision
description: A cross-platform mobile app that helps you remember which frozen pizzas you've tried and liked, using computer vision to identify similar products
tech: ["Ionic", "React", "TensorFlow.js", "Supabase", "Capacitor"]
link: https://github.com/gabriel-aleixo/pizza-vision
date: 2024-01-15
featured: true
images:
    - /src/images/project-images/pizzavision/1.svg
    - /src/images/project-images/pizzavision/2.svg
    - /src/images/project-images/pizzavision/3.svg
---

## The Problem

The frozen pizza aisle is a cluttered space where products often look similar, with Italian-sounding names and picturesque images that don't reflect the actual quality. After accidentally buying the same disappointing frozen pizza twice, I realized there had to be a better way to remember product preferences and avoid repeat mistakes.

## Key Features

- **Image Recognition**: Uses TensorFlow.js and MobileNet to identify and match similar product packages
- **Simple Rating System**: Quick "👍" or "👎" tagging for immediate feedback
- **Photo Library**: Browse past purchases chronologically or by rating
- **Cross-Platform**: Available on iOS with Android version in development
- **Cloud Sync**: Automatic synchronization of photos and preferences across devices
- **One-Time Password Authentication**: Simple email-based login system

## Tech Decisions

I chose Ionic with React for the frontend to enable cross-platform development while leveraging my existing React knowledge. The framework's mature ecosystem and large community support made it an ideal choice for a mobile-first application.

For the backend, Supabase provided a comprehensive solution that included authentication, database, and storage capabilities. This allowed me to focus on the core functionality while having a robust infrastructure for user data and photos.

TensorFlow.js with MobileNet was selected for image recognition, offering a good balance between accuracy and performance on mobile devices. While the current implementation uses MobileNet, the architecture is designed to be easily upgraded to more accurate models like EfficientNet in the future.

## Interesting Challenge

One of the most significant challenges was implementing efficient image similarity search. The app needed to quickly identify similar product packages from the user's photo library, which required careful optimization of the image processing pipeline.

The solution involved:
- Pre-processing images to focus on product packaging
- Implementing efficient similarity algorithms
- Caching processed images to improve performance
- Balancing accuracy with mobile device constraints

This challenge led to valuable insights about mobile-first development and the importance of optimizing for performance while maintaining a good user experience.

## What's Next?

PizzaVision is currently available on the App Store, with an Android version in development. The project started as my final project for the Harvard CS50x course, and while it successfully solved my personal problem of remembering pizza preferences, there's potential to expand its scope.

Future improvements could include:
- Enhanced image classification accuracy using EfficientNet
- Performance optimizations for image processing
- Additional product categories beyond frozen pizzas
- Social features for sharing recommendations
- Improved library management with infinite scroll and advanced filtering

The project demonstrates how computer vision can be applied to solve everyday problems, making product discovery and preference tracking more efficient and enjoyable.