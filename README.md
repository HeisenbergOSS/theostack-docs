# TheoStack Docs

This website is built using [Docusaurus 3](https://docusaurus.io/), a modern static website generator.

## Installation

This project uses pnpm as the package manager. Make sure you have Node.js 18+ installed.

```bash
pnpm install
```

## Local Development

```bash
pnpm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
pnpm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true pnpm deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> pnpm deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Project Structure

```
theostack-docs/
├── blog/                    # Blog posts
├── docs/                    # Documentation pages
├── src/
│   ├── components/          # React components
│   ├── css/                 # Global CSS
│   └── pages/               # Custom pages
├── static/                  # Static assets
├── docusaurus.config.ts     # Docusaurus configuration
├── sidebars.ts             # Sidebar configuration
└── package.json
```

## Features

- ⚛️ Built with React and TypeScript
- 📝 MDX support for enhanced markdown
- 🎨 Customizable with CSS and React components
- 🔍 Built-in search functionality
- 📱 Mobile responsive design
- 🌙 Dark mode support
- 📊 SEO optimized

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
