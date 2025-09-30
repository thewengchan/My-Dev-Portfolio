# Weng Chan - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Full Stack Developer, AI Engineer, and Entrepreneur. Built with SvelteKit 5 and deployed on Cloudflare Workers.

## 🌐 Live Site

Visit the live website at [wengchan.dev](https://wengchan.dev)

## ✨ Features

- **Modern Tech Stack**: Built with SvelteKit 5, TypeScript, and Tailwind CSS
- **Responsive Design**: Optimized for all device sizes
- **Dark/Light Mode**: Automatic theme switching with system preference detection
- **Performance Optimized**: Deployed on Cloudflare Workers for global edge performance
- **SEO Friendly**: Server-side rendering with proper meta tags
- **Interactive Components**: Carousel, tooltips, and smooth animations
- **Markdown Support**: Dynamic content rendering for projects and blog posts

## 🛠️ Tech Stack

- **Framework**: [SvelteKit 5](https://kit.svelte.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [UnoCSS](https://unocss.dev/)
- **UI Components**: Custom components with [Bits UI](https://www.bits-ui.com/)
- **Icons**: [Lucide Svelte](https://lucide.dev/) + [Carbon Icons](https://carbondesignsystem.com/elements/icons/)
- **Deployment**: [Cloudflare Workers](https://workers.cloudflare.com/)
- **Build Tool**: [Vite](https://vitejs.dev/)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm, pnpm, or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/wengchan.dev.git
cd wengchan.dev
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run deploy` - Deploy to Cloudflare Workers
- `npm run lint` - Run ESLint and Prettier
- `npm run format` - Format code with Prettier
- `npm run check` - Run TypeScript and Svelte checks

## 🏗️ Project Structure

```
src/
├── lib/
│   ├── components/     # Reusable UI components
│   │   ├── common/     # Common components (nav, buttons, etc.)
│   │   ├── ui/         # Base UI components (shadcn/ui inspired)
│   │   └── ...
│   ├── data/          # Static data and content
│   └── utils.ts       # Utility functions
├── routes/            # SvelteKit routes
│   ├── education/     # Education pages
│   ├── experience/    # Work experience pages
│   ├── projects/      # Project showcase
│   ├── skills/        # Skills and technologies
│   └── resume/        # Resume/CV page
└── static/           # Static assets (images, PDFs, etc.)
```

## 🎨 Customization

The portfolio is designed to be easily customizable:

1. **Personal Information**: Update `src/lib/data/base.ts`
2. **Home Page**: Modify `src/lib/data/home.ts`
3. **Skills**: Edit `src/lib/data/skills.ts`
4. **Projects**: Update `src/lib/data/projects.ts`
5. **Experience**: Modify `src/lib/data/experience.ts`
6. **Education**: Edit `src/lib/data/education.ts`

## 🚀 Deployment

This project is configured for deployment on Cloudflare Workers:

1. Install Wrangler CLI:

```bash
npm install -g wrangler
```

2. Authenticate with Cloudflare:

```bash
wrangler login
```

3. Deploy:

```bash
npm run deploy
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/wengchan.dev/issues).

## 📞 Contact

- **Email**: [Contact me here](wengchan99899@gmail.com)
- **LinkedIn**: [Weng Chan](https://www.linkedin.com/in/wengchan-uk/)
- **GitHub**: [thewengchan](https://github.com/thewengchan)
- **Website**: [wengchan.dev](https://wengchan.dev)

---

Built with ❤️ by Weng Chan
Inspired by riadh-adrani