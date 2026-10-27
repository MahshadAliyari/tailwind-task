
## Tailwind CSS Landing Page Redesign

### Overview

The original Nafas cosmetics store landing page was redesigned using **Tailwind CSS** while preserving its main content, layout structure, and brand identity.

The redesigned page is available in `landingpage-tailwind.html`. The original `landingpage.html` remains unchanged.

### Features

- **Responsive Design:** Mobile-first layout using Tailwind responsive utilities.
- **Custom Brand Colors:** Soft pink, navy, and muted purple color palette.
- **Dark Mode:** Navy backgrounds, lighter cards, readable text, and pink accents.
- **Interactive Cards:** Hover animations, subtle borders, rounded corners, and soft shadows.
- **Improved Typography:** Responsive headings, readable line heights, and Vazirmatn font.
- **Styled Navigation:** Responsive navigation links with hover effects.
- **Call-to-Action Section:** Gradient background, rounded buttons, and hover transitions.
- **Utility-First Styling:** Tailwind classes for spacing, colors, typography, borders, shadows, and layout.

### Dark Mode

Dark mode is configured using Tailwind CSS's `class` strategy in `tailwind.config.js`.

To preview dark mode during development, add the `dark` class to the HTML element:

```html
<html lang="fa" dir="rtl" class="dark">
```

The dark theme uses a deep navy background, slightly lighter navy cards, muted text, and pink highlights instead of pure black.

### Custom Tailwind Configuration

The Tailwind theme includes the following custom extensions:

- **Primary Colors:** `primary`, `primary-dark`
- **Pink Colors:** `pink-light`, `pink-soft`
- **Dark Theme Colors:** `night-bg`, `night-surface`, `night-elevated`, `night-text`, `night-muted`, `night-border`
- **Font Family:** `vazir`
- **Border Radius:** `rounded-brand`
- **Box Shadows:** `shadow-brand`, `shadow-brand-dark`

### Build Commands

Build the Tailwind CSS stylesheet:

```bash
npm run build:css
```

Watch for changes during development:

```bash
npm run watch:css
```

The generated stylesheet is saved to `css/tailwind.css`.

### Technologies Used

- HTML5
- Tailwind CSS 3
- JavaScript (where applicable)
- Google Fonts — Vazirmatn

### Project Files

- `landingpage.html` — Original landing page.
- `landingpage-tailwind.html` — Redesigned landing page using Tailwind CSS.
- `tailwind.config.js` — Tailwind configuration and custom theme.
- `src/input.css` — Tailwind input stylesheet.
- `css/tailwind.css` — Generated Tailwind stylesheet.

### Notes

The Tailwind redesign is maintained separately from the original page to simplify comparison and testing. Dark mode currently uses the `dark` class on the root HTML element; an interactive theme toggle can be implemented separately.

### Demo



### AI Transparency

- **Section:** Tailwind CSS exercise: understanding utility classes and installing Tailwind.
- **How I used it:** I first asked the AI to explain the concepts behind Tailwind utility classes, and I studied the explanation. I also asked the AI for help installing and setting up Tailwind in the project.
- **What I changed:** I wrote all the markup and Tailwind classes myself; the AI was used only for concept explanation and installation help.