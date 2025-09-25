# Lunch Box Landing Page

A modern, responsive landing page built with Next.js, TypeScript, and Tailwind CSS featuring an elegant design with smooth animations and dark/light theme support.

## Features

- 🎨 Modern UI with Tailwind CSS and shadcn/ui components
- 🌙 Dark/Light mode toggle with system preference detection
- 📱 Fully responsive design
- ⚡ Smooth scroll animations and morphing effects
- 🎯 Interactive elements with hover effects
- 🚀 Optimized for performance
- 📦 Built with Next.js 15 and TypeScript

## Technologies Used

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Icons**: Lucide React
- **Form Handling**: React Hook Form with Zod validation
- **Charts**: Recharts
- **Animations**: CSS transforms and transitions

## Getting Started

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd lunch-box-landing
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Run the development server:
   ```bash
   pnpm dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
pnpm build
```

This will create an optimized static export in the `out` directory.

## Deployment

This project is configured for deployment to GitHub Pages with automated CI/CD:

1. Push your code to GitHub
2. Enable GitHub Pages in repository settings
3. Set source to "GitHub Actions"
4. The workflow will automatically build and deploy on every push to main/master

## Project Structure

```
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Main landing page
├── components/            # React components
│   ├── ui/               # shadcn/ui components
│   └── theme-provider.tsx # Theme context provider
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
└── styles/               # Additional styles
```

## Customization

The landing page is fully customizable:

- Edit content in `app/page.tsx`
- Modify styles in `app/globals.css` and Tailwind classes
- Add new components in the `components/` directory
- Configure theme colors in `tailwind.config.ts`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Demo

Visit the live demo: [Your GitHub Pages URL will be here after deployment]