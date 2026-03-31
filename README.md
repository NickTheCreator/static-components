# Static Components Collection

Welcome to a collection of static HTML and CSS components. This repository contains reusable UI components built with pure HTML and CSS, made to practice, as an inspiration and to use in projects.

## 📋 Repository Overview

This repository includes different basic web UI components that follow simple design ideas. Each component is separated and focused on being clear, usable, and visually clean. You will find components from simple ones like pagination and tables, to more complete sections like hero section and layout examples

**Component Types:**
- Navigation & Layout Components
- Content Display Components  
- Interactive Components
- Form & CTA Elements

---

## 📁 Project Structure

```
Layouts/
├── email-copy/
│   ├── email.html
│   └── email.css
Section-static/
├── static-accordion/
│   ├── 01-accordion.html
│   └── accordion.css
├── static-carousel/
│   ├── 02-carousel.html
│   ├── carousel.css
│   └── img/
├── static-hero/
│   ├── 03-hero.html
│   ├── hero.css
│   └── img/
├── static-pagination/
│   ├── 04-pagination.html
│   └── pagination.css
└── static-table/
    ├── 05-table.html
    └── table.css
README.md (this file)
```


## 🎯 Purpose and Usage

This repository is mainly for practicing and improving HTML and CSS skills, and also to keep components organized in one place. It can be used as a reference for ideas or as a base to reuse and adapt components in other projects.

Each component includes:

- Simple and semantic HTML structure
- CSS focused on layout and styling
- Defined color palette and typography
- Basic explanation about the design and its purpose

---

## 🎨 Component Previews

### Accordion

![Accordion Preview](/Preview/preview-accordion.png)

**Description**  
This accordion component was created focusing on clarity and organization of content. Each item is separated using spacing and soft shadows, which helps to visually divide the sections without needing strong borders.

The numbering (01, 02, 03) was used to give a better sense of order and help users scan the content faster. When opened, the content is easy to read, with good spacing between paragraphs and list items.

The color contrast between the light background and the blue accent helps to show which item is active, without being too strong or aggressive. The inspiration comes from FAQ sections and simple modern interfaces.

**Design Properties**
- **Color Palette:**  
  - Background: `#edf2ff`  
  - Accent (Active State): `#4263eb`  
  - Shadow: `rgba(0, 0, 0, 0.685)` (semi-transparent dark)

- **Typography:**  
  - Font Family: Inter
  - Title: 26px (font-weight: 500)
  - Paragraph: 22px (line-height: 1.6)
  - List Items: 18px (font-weight: 300)

- **Personality:**  
  Calm, simple, and organized

---

### Carousel / Testimonial Slider

![Carousel Preview](/Preview/preview-carousel.png)

**Description**  
This carousel component is designed as a testimonial showcase, featuring an elegant dark green background that creates a premium feel. The component displays customer testimonials alongside their profile imagery and positioning information.

The navigation arrows are positioned on the sides with a subtle shadow effect, making them easily accessible without being intrusive. The dot indicators at the bottom provide clear pagination feedback. The design emphasizes readability and trust through generous spacing and a professional layout that works well for customer feedback sections.

**Design Properties**
- **Color Palette:**  
  - Primary Background: `#087f5b` (deep teal/green)  
  - Secondary Background: `#f8f9fa` (light gray)
  - Button Background: White
  - Accent: `#087f5b`

- **Typography:**  
  - Font Family: Inter
  - Testimonial Text: Default size with 1.6 line-height
  - Author Name: Bold styling
  - Job Title: Smaller, supporting text

- **Personality:**  
  Modern, trustworthy, professional

---

### Hero Section

![Hero Preview](/Preview/preview-hero.png)

**Description**  
The hero section is a full-screen landing area designed to grab attention and guide users toward action. It features a striking background image with a semi-transparent dark overlay that ensures text readability while maintaining visual impact.

The layout positions content on the left side of the viewport, creating a clean hierarchy with a prominent headline, descriptive text, and a clear call-to-action button. The design uses warm accent colors and a readable serif font to convey reliability and professionalism. This component works excellently for marketing landing pages and product introductions.

**Design Properties**
- **Color Palette:**  
  - Overlay: `rgba(34, 34, 34, 0.5)` (semi-transparent dark)
  - Text: White (`#fff`)
  - CTA Button: `#e67e22` (warm orange)
  - Secondary Text: `#343a40` (dark gray)

- **Typography:**  
  - Font Family: Rubik
  - Headline: 56px (font-weight: 700)
  - Body Text: 24px (line-height: 1.6)
  - CTA Button: 22px (font-weight: 600)

- **Personality:**  
  Bold, modern, actionable

---

### Data Table

![Table Preview](/Preview/preview-table.png)

**Description**  
This static table component is designed for presenting structured data in a clear, scannable format. It displays product specifications with alternating row colors to improve readability and reduce visual strain during comparison.

The header row uses a bold teal color to establish hierarchy and draw focus. The alternating background colors in the tbody create a visual rhythm that makes horizontal scanning easier. Generous padding and left-aligned text enhance legibility. This component is ideal for product comparisons, pricing tables, and specification listings.

**Design Properties**
- **Color Palette:**  
  - Header Background: `#099268` (teal green)
  - Header Text: `#fff` (white)
  - Row 1 (Odd): `#e9ecef` (light gray)
  - Row 2 (Even): `#ced4da` (medium gray)
  - Body Text: `#212529` (dark gray)

- **Typography:**  
  - Font Family: Outfit
  - Cell Content: Default system size
  - Padding: 16px 24px (generous spacing)

- **Personality:**  
  Professional, organized, scannable

---

### Pagination

![Pagination Preview](/Preview/preview-pagination.png)

**Description**  
This pagination component provides intuitive navigation for multi-page content. It features numbered page buttons, navigation arrows, and an ellipsis indicator for large page ranges.

The design uses a subtle color scheme with a bold accent color for hover states, creating clear visual feedback for user interaction. The circular button design is modern and minimalist, while the icon-based navigation arrows reduce visual clutter. The component is perfect for search results, blog archives, and any paginated content lists.

**Design Properties**
- **Color Palette:**  
  - Background: `#f1f3f5` (very light gray)
  - Accent/Hover: `#fa5252` (red/pink)
  - Button Border: `#fa5252`
  - Text: `#212529` (dark gray)

- **Typography:**  
  - Font Family: System default (12px size)
  - Button Size: 24px × 24px (circular)
  - Icon: 12px × 12px

- **Personality:**  
  Simple, intuitive, minimal

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open any HTML file in your browser to view the component
3. Review the corresponding CSS file to understand the styling
4. Customize colors, typography, and spacing to match your project needs

## 💡 Design Principles Used

- **Visual Hierarchy:** Clear distinction between primary and secondary elements
- **Consistency:** Unified spacing scale and typography across components
- **Accessibility:** Proper contrast ratios and semantic HTML structure
- **Simplicity:** Clean designs that don't sacrifice functionality for aesthetics
- **Responsiveness:** Components built with modern CSS layout techniques

---

**Happy designing!** Feel free to fork, modify, and build upon these components.
