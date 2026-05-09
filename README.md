# Kavin P - Premium Developer Portfolio

A cinematic, premium developer portfolio website built with React, Vite, Tailwind CSS, and Framer Motion.

## Features
- **Premium Aesthetics:** Dark mode, glassmorphism, gradient blurs, and Apple-level minimalism.
- **Advanced Animations:** Scroll reveals, custom cursor glow, floating bento grids using Framer Motion.
- **Smooth Scrolling:** Powered by Lenis for a luxury feel.
- **Responsive:** Fully optimized for all screen sizes.
- **SEO Optimized:** Metadata, semantic HTML, and high performance.

## Tech Stack
- React 18 + Vite
- Tailwind CSS
- Framer Motion
- React Icons
- Lenis
- EmailJS

## Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run Development Server:**
   ```bash
   npm run dev
   ```

3. **Build for Production:**
   ```bash
   npm run build
   ```

## Environment Variables

For the contact form to work, create a `.env` file in the root directory and add your EmailJS credentials:

```env
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
```

*(Note: The current codebase has EmailJS code commented out to simulate successful submissions for demonstration purposes. Uncomment and add credentials to use the live service).*

## Deployment

This project is fully ready for deployment on platforms like Vercel, Netlify, or Cloudflare Pages.

1. Connect your GitHub repository to your preferred platform.
2. Set the framework preset to `Vite`.
3. Build command: `npm run build`
4. Output directory: `dist`
5. Add the environment variables in the platform's settings.
