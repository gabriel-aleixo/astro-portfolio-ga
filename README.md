# Professional Portfolio Website

A modern, performant portfolio website built with Astro, focusing on clean design and optimal user experience. This project demonstrates how to create a fast, maintainable, and visually appealing portfolio website using modern web technologies.

## Features

- 🚀 **Performance-First**: Optimized for speed with minimal JavaScript and efficient asset loading
- 📱 **Responsive Design**: Clean, functional layout that works seamlessly across all devices
- 🖼️ **Project Showcase**: Detailed project pages with image carousels and technical information
- 🌓 **Dark Mode**: Built-in dark mode support with system preference detection
- 🔍 **SEO Optimized**: Proper meta tags and semantic HTML for better search engine visibility
- 🔄 **Automated Deployment**: Continuous deployment pipeline with GitHub Actions and Netlify

## Tech Stack

- [Astro](https://astro.build/) - The web framework for content-driven websites
- [TypeScript](https://www.typescriptlang.org/) - For type safety and better developer experience
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Netlify](https://www.netlify.com/) - For hosting and deployment
- [GitHub Actions](https://github.com/features/actions) - For automated testing and deployment

## Project Structure

```
src/
├── components/     # Reusable UI components
├── layouts/        # Page layouts and templates
├── pages/          # Route components
│   └── projects/   # Project detail pages
├── styles/         # Global styles and Tailwind config
└── images/         # Static images and assets
```

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gabriel-aleixo/astro-portfolio-ga.git
   cd astro-portfolio-ga
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:4321](http://localhost:4321) to view the website.

### Building for Production

```bash
npm run build
# or
yarn build
```

## Deployment

The website is automatically deployed to Netlify when changes are pushed to the main branch. The deployment process includes:

1. Running tests
2. Building the project
3. Deploying to Netlify

## Contributing

While this is primarily a personal portfolio website, suggestions and improvements are welcome. Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Gabriel Aleixo - [@gabriel_aleixo](https://twitter.com/gabriel_aleixo)

Project Link: [https://github.com/gabriel-aleixo/astro-portfolio-ga](https://github.com/gabriel-aleixo/astro-portfolio-ga)
