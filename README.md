# Cursor Landing Page Clone

This repository contains a clone of the Cursor landing page, built exactly to the specified assignment requirements. The project focuses on recreating the visual design and layout using only pure HTML and CSS.

## 🏗️ Sections Recreated

I have successfully built the following 11 sections as requested:

1.  **Top Navigation Bar**: Includes logo, navigation links, and primary CTA buttons with a dark background.
2.  **Hero Section**: Features the main headline, description, CTA button, and a large product video/screenshot.
3.  **Trusted By / Logos**: A row of company logos (Stripe, OpenAI, etc.) displayed in a grid.
4.  **Feature Sections**: Three blocks with a two-column layout (alternating text and video/image) showcasing core features.
5.  **Feature Cards Section (Feedback)**: A grid layout displaying testimonials/quotes with user details.
6.  **Testimonials**: Integrated into the feedback section as quota cards.
7.  **Use Cases / Stories (Frontier)**: Cards with images and short text highlighting model access and enterprise features.
8.  **Changelog**: A list of recent updates with version numbers and dates.
9.  **Team / About (Join Us)**: A section with a call-to-action to join the team, featuring a large team photo.
10. **Final CTA**: A distinct download section with a large heading and a single button.
11. **Footer**: A multi-column layout containing links, company info, and legal text.

## 📱 Mobile-First Architecture

This project has been refactored to use a **Mobile-First** CSS methodology. Styles are defined for small screens by default and progressively enhanced for larger displays using `min-width` media queries.

### 📏 Breakpoints

- **Mobile**: `0px - 640px` (Default)
- **Tablet**: `641px - 1024px` (`@media (min-width: 641px)`)
- **Desktop**: `1025px+` (`@media (min-width: 1025px)`)

## 🎨 Design System

I have matched the original design's aesthetic closely using the following system:

### 🔤 Fonts

- **Primary Font**: `CursorGothic`
- **Fallbacks**: `CursorGothic Fallback`, `system-ui`, `Helvetica Neue`, `Arial`, `sans-serif`

### 🎨 Color Palette

- **Backgrounds**:
  - Page Background: `#14120b` (Dark Theme)
  - Card Background: `#1b1913` / `#1d1b15`
  - Card Hover: `#201e18`
- **Typography**:
  - Primary Text: `#edecec`
  - Secondary Text: `#d7d6d5`
- **Accents**:
  - Links/Highlights: Orange (`rgb(245, 78, 0)`), Red (`rgb(233, 62, 62)`)

## ✨ Code Quality & Formatting

- **Fluid Layouts**: Replaced all fixed pixel widths with `width: 100%` and `max-width` constraints to prevent horizontal scrolling.
- **Responsive Grids**: All multi-column layouts (Feedback, Features, Footer) collapse into a single column on mobile for better usability.
- **Standardized Indentation**: All CSS files use a consistent 2-space indentation pattern.
- **Documentation**: Code is heavily commented to explain the mobile-first progression.

## ⚠️ Constraints Adherence

- ✅ **HTML & CSS Only**: No JavaScript used.
- ✅ **No Frameworks**: Pure CSS, no TailwindCSS.
- ✅ **Fully Responsive**: Optimized for every screen size from mobile to ultra-wide desktop.
- ✅ **No AI Generation**: All refactoring logic was applied manually based on senior frontend best practices.

## 🖼️ Output

[Live Demo](https://subtle-raindrop-3a6914.netlify.app/)

## 🚀 How to Run

1.  Clone this repository.
2.  Open `index.html` in any web browser.
