# Astro Learning Blog

A personal blog documenting my journey learning Astro, built with the Astro framework.

## 🚀 Features

- **Static Site Generation**: Fast, SEO-friendly blog built with Astro
- **Markdown Support**: Write blog posts in Markdown with frontmatter
- **Component Library**: Reusable components built with Preact
- **RSS Feed**: Automatic RSS feed generation for blog posts
- **Tag System**: Organize posts by tags
- **Responsive Design**: Mobile-friendly layout

## 🛠️ Tech Stack

- **Framework**: Astro
- **UI Components**: Preact
- **Styling**: CSS
- **Content**: Markdown
- **Deployment**: Netlify

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── BlogPost.astro
│   │   ├── Footer.astro
│   │   ├── Greeting.jsx
│   │   ├── Header.astro
│   │   ├── Menu.astro
│   │   ├── Navigation.astro
│   │   ├── Social.astro
│   │   └── ThemeIcon.astro
│   ├── layouts/
│   │   ├── BaseLayout.astro
│   │   └── MarkdownPostLayout.astro
│   ├── pages/
│   │   ├── about.astro
│   │   ├── blog.astro
│   │   ├── index.astro
│   │   ├── rss.xml.js
│   │   ├── posts/
│   │   │   ├── post-4.md
│   │   │   ├── posts-1.md
│   │   │   ├── posts-2.md
│   │   │   └── posts-3.md
│   │   └── tags/
│   │       ├── [tag].astro
│   │       └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd astro-project-1
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:4321](http://localhost:4321) in your browser.

## 📝 Usage

### Creating Blog Posts

1. Create a new Markdown file in `src/pages/posts/`
2. Add frontmatter with title, date, description, author, image, and tags
3. Write your post content in Markdown
4. The post will automatically appear on the blog page

### Adding Components

- Place reusable components in `src/components/`
- Use `.astro` for Astro components or `.jsx` for Preact components
- Import and use them in your pages and layouts

## 🏗️ Build & Deployment

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Deploy

This project is configured for deployment on Netlify. The production site is available at: [https://emy-cmd-astro-site.netlify.app/](https://emy-cmd-astro-site.netlify.app/)


## 🤝 Contributing

This is a personal learning project, but feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using Astro*
