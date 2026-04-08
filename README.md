# Atrom - Modern Astro Theme

[English](./README.md) | [中文](./README-zh.md)

<p align="center">
  <img src="./public/images/atrom-preview-en.png" alt="Atrom Theme Preview - English" width="800">
</p>

A beautiful, responsive Astro theme with a clean design and modern aesthetics, built for Astro v6. Supports Chinese and English language switching, which can be easily toggled in the navigation bar.

### Live Preview

Check out the live preview of this theme:
[https://astro-art-template.2636098325.workers.dev/](https://astro-art-template.2636098325.workers.dev/)

## Features

- 🎨 **Clean Design**: Minimalist and elegant UI design
- 🌍 **Multi-language Support**: Built-in Chinese and English language support
- 📱 **Responsive**: Works perfectly on all screen sizes
- 🚀 **Fast Performance**: Built with Astro for optimal speed
- 🎯 **Modern Aesthetics**: Uses Inter font family and smooth transitions
- ✅ **Astro v6 Compatible**: Fully compatible with the latest Astro version

## Pages

- **Home**: Hero section with brand introduction
- **Product**: Showcase product features
- **Value**: Highlight business value propositions
- **Stories**: Customer testimonials and success stories

## Requirements

- **Node.js**: >= 22.12.0 (Astro v6 requirement)
- **Package Manager**: pnpm recommended

## Quick Start

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build
```

## Project Structure

```
atrom/
├── src/
│   └── pages/
│       ├── index.astro          # Chinese home page
│       ├── product.astro        # Chinese product page
│       ├── value.astro          # Chinese value page
│       ├── stories.astro        # Chinese stories page
│       └── en/
│           ├── index.astro      # English home page
│           ├── product.astro    # English product page
│           ├── value.astro      # English value page
│           └── stories.astro    # English stories page
├── astro.config.mjs
├── package.json
└── README.md
```

## Tech Stack

- **Astro**: Static site generator
- **CSS**: Custom styling with modern CSS features
- **JavaScript**: Interactive components

## Language Switching

The theme supports both Chinese and English languages. The language selector is prominently placed in the navigation bar, right after the logo.

## Deployment

### Cloudflare Pages

1. **Prerequisites**:

   - A Cloudflare account
   - Git repository with your Astro project

2. **Deployment Steps**:

   - Log in to your Cloudflare account
   - Navigate to **Workers & Pages** > **Create application** > **Pages**
   - Select your Git repository and branch
   - Configure build settings:
     - **Framework preset**: Astro
     - **Build command**: `pnpm build`
     - **Build output directory**: `dist`
   - Click **Save and Deploy**

3. **Configuration**:
   - The project includes a `cloudflare_pages.yml` configuration file for reference
   - For server-side rendering, ensure the Cloudflare adapter is configured in `astro.config.mjs`
   - **Important**: Do NOT set a custom deploy command in Cloudflare Pages dashboard. Cloudflare Pages will automatically deploy the build output from the `dist` directory.

## License

MIT
