# Totalis AI Website

Professional single-page website for Totalis AI services.

## Tech Stack

- **Framework**: Astro
- **Styling**: Tailwind CSS
- **Deployment**: Netlify or Vercel

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

### Netlify
1. Connect your Git repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Add your custom domain: `totalisai.ca`

### Vercel
1. Import your Git repository to Vercel
2. Framework preset will auto-detect Astro
3. Add your custom domain: `totalisai.ca`

## Customization

- Update contact information in `src/pages/index.astro`
- Modify colors in Tailwind classes (currently using indigo/blue palette)
- Add your company logo by replacing `/public/favicon.svg`
- Update meta tags for SEO in the `<head>` section

## Color Scheme

Professional indigo/blue palette:
- Primary: Indigo-600 (#4F46E5)
- Secondary: Blue, Sky, Purple, Violet, Teal variations
- Background: White with gradient accents
- Text: Gray-900 for headings, Gray-600 for body
