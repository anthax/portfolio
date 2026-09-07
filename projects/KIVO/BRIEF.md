# KIVO — Website Design & Development Brief

## 01. Project Overview

**Client:** Kivo
**Industry:** Restaurant / Hospitality
**Location:** Lagos, Nigeria
**Project Type:** Responsive multi-page website
**Goal:** Create a premium, modern website that introduces Kivo, showcases its food, and encourages visitors to make a reservation.

Kivo is a fictional contemporary Nigerian restaurant focused on reimagining Nigerian cuisine through modern presentation, high-quality ingredients, and a refined dining experience.

The website should feel **premium, modern, warm, editorial, and confident**.

---

# 02. Target Audience

Kivo's customers are:

* Young professionals
* Couples
* Groups of friends
* Business professionals
* Tourists and visitors to Lagos
* People looking for a premium dining experience

The website should appeal to people who are willing to spend more for **quality, atmosphere, and experience**.

---

# 03. Pages

Build four pages:

1. **Home**
2. **Menu**
3. **About**
4. **Reservations**

Every page must share the same visual identity and navigation.

---

# 04. Brand Identity

## Brand Name

**KIVO**

Use uppercase for the logo.

## Brand Personality

Kivo should feel:

* Sophisticated
* Modern
* Warm
* Confident
* Minimal
* Premium
* Nigerian without relying on clichés

Avoid making the design look overly traditional, colorful, or tourist-oriented.

---

# 05. Colour Palette

Use this palette throughout the website.

| Purpose              | Colour        | Hex       |
| -------------------- | ------------- | --------- |
| Main background      | Near Black    | `#0D0D0D` |
| Secondary background | Dark Charcoal | `#171717` |
| Primary text         | Warm White    | `#F5F2EA` |
| Secondary text       | Muted Grey    | `#A6A29A` |
| Accent               | Warm Gold     | `#C69252` |
| Borders              | Dark Grey     | `#292929` |

### Usage

**Near Black**

* Main page background
* Navbar
* Footer

**Dark Charcoal**

* Cards
* Secondary sections
* Form areas

**Warm White**

* Headings
* Important text
* Navigation

**Muted Grey**

* Descriptions
* Supporting text
* Metadata

**Warm Gold**

* Buttons
* Links on hover
* Small labels
* Important accents

**Dark Grey**

* Borders
* Dividers
* Input borders

Do not use every colour everywhere. The design should remain predominantly black and off-white, with gold used sparingly.

---

# 06. Typography

Use two fonts.

### Primary Font

**Geist**

Use for:

* Navigation
* Body text
* Buttons
* Forms
* Prices
* Small labels

### Display Font

**Playfair Display**

Use for:

* Large hero headings
* Section headings
* Large editorial statements

### Typography Direction

Headings should be large and confident.

Body text should be relatively small, clean, and easy to read.

Do not use excessive font weights.

Suggested hierarchy:

```text
Hero heading:       64–80px desktop
Section heading:    42–56px desktop
Card heading:       20–24px
Body:               16–18px
Small text:         12–14px
```

On mobile, scale these down appropriately.

---

# 07. Images

Use high-quality food and restaurant photography.

Image direction:

* Dark/moody lighting
* Warm tones
* Premium food photography
* Modern restaurant interiors
* Nigerian-inspired dishes
* Close-up food photography
* People dining in a sophisticated environment

Avoid:

* Cartoon illustrations
* Generic corporate stock photos
* Bright fast-food imagery
* Low-quality images
* Overly staged photography

You may use royalty-free placeholder images during development.

---

# 08. Global Navigation

Every page should have the same navbar.

### Desktop

```text
KIVO

Home    Menu    About    Reservations

                    Reserve a Table
```

Requirements:

* Logo on the left
* Navigation in the centre/right
* Reservation CTA
* Dark background
* Sticky navigation
* Subtle border at the bottom

### Mobile

Use a simplified mobile navigation.

Since JavaScript has not been learned yet, the mobile menu does **not** need to be a functional hamburger menu.

You can instead use a simplified navigation layout that works with CSS alone.

---

# 09. HOME PAGE

## Section 1 — Hero

Large full-width hero section.

Content:

**Small label**

`MODERN NIGERIAN DINING`

**Main heading**

`A new expression of Nigerian cuisine.`

**Supporting text**

`Seasonal ingredients, bold flavours, and thoughtful preparation come together in the heart of Lagos.`

Buttons:

`Explore Menu`

`Reserve a Table`

Hero image should occupy a significant portion of the screen.

---

## Section 2 — Introduction

Small label:

`THE KIVO EXPERIENCE`

Heading:

`Rooted in tradition. Designed for today.`

Short paragraph explaining Kivo's approach to Nigerian cuisine.

Layout:

```text
Text                Image
```

On mobile:

```text
Image
Text
```

---

## Section 3 — Featured Dishes

Small label:

`FROM THE MENU`

Heading:

`Made to be remembered.`

Display three featured dishes.

### Dish 1

**Jollof Arancini**

Crispy jollof rice, smoked tomato, pepper relish.

**₦8,500**

### Dish 2

**Suya Short Rib**

Slow-cooked beef short rib, suya spice, roasted pepper.

**₦18,500**

### Dish 3

**Coconut Panna Cotta**

Coconut cream, mango, toasted coconut.

**₦7,500**

Each dish should include a high-quality image.

---

## Section 4 — Why Kivo

Create three feature blocks.

### 01 — Seasonal

`Our menu evolves with the best ingredients available.`

### 02 — Local

`We celebrate Nigerian ingredients through a contemporary lens.`

### 03 — Thoughtful

`Every plate is designed around flavour, balance, and experience.`

Use a simple three-column layout on desktop.

---

## Section 5 — Gallery

Create an editorial image gallery using CSS Grid.

Use 5–7 images.

The layout should be asymmetrical rather than a basic collection of identical squares.

---

## Section 6 — Visit Kivo

Display:

**Location**

14 Adeola Odeku Street
Victoria Island, Lagos

**Opening Hours**

Monday — Thursday
12:00 PM — 10:00 PM

Friday — Saturday
12:00 PM — 11:00 PM

Sunday
12:00 PM — 9:00 PM

Include a simple location/image area.

---

## Section 7 — Reservation CTA

Large section near the bottom.

Heading:

`Your table is waiting.`

Text:

`Join us for an evening of modern Nigerian dining.`

Button:

`Make a Reservation`

---

# 10. MENU PAGE

## Hero

Label:

`THE MENU`

Heading:

`A modern take on Nigerian flavour.`

Short introductory paragraph.

---

## Menu Categories

Display:

```text
Starters
Main Courses
Sides
Desserts
Drinks
```

Since JavaScript has not been learned yet, these categories do not need to filter dynamically.

---

## Menu Items

Create at least **15 items** across the categories.

Every item must contain:

* Name
* Description
* Price

Example:

**Jollof Arancini**
Crispy jollof rice, smoked tomato, pepper relish.
₦8,500

Use a clean editorial layout.

---

# 11. ABOUT PAGE

## Hero

Label:

`OUR STORY`

Heading:

`Nigerian food. A different perspective.`

Large restaurant image.

---

## Story

Explain how Kivo was created.

The story should communicate:

* Respect for Nigerian food
* Modern interpretation
* Local ingredients
* Hospitality
* Community

---

## Philosophy

Create three sections:

### Ingredient

`We begin with ingredients worth celebrating.`

### Technique

`Traditional flavours meet modern technique.`

### Experience

`Every detail is designed to make people want to stay longer.`

---

## Chef Section

Create a fictional chef profile.

**Chef:** Amara Okafor

Include:

* Portrait
* Short biography
* Cooking philosophy

---

## Final CTA

Heading:

`Come experience Kivo.`

Button:

`Reserve a Table`

---

# 12. RESERVATIONS PAGE

## Hero

Label:

`RESERVATIONS`

Heading:

`Make your evening memorable.`

Short supporting paragraph.

---

## Reservation Form

Create the following fields:

**Full Name**

**Email Address**

**Phone Number**

**Date**

**Preferred Time**

**Number of Guests**

**Special Requests**

Button:

`Reserve a Table`

Use appropriate HTML input types and validation.

Required fields should use:

```text
required
```

Email should use:

```text
type="email"
```

Date should use:

```text
type="date"
```

Phone should use:

```text
type="tel"
```

No backend is required.

The form is purely frontend for this version.

---

# 13. FOOTER

Every page should have the same footer.

Include:

```text
KIVO

Modern Nigerian dining
in the heart of Lagos.

Navigation
Home
Menu
About
Reservations

Contact
14 Adeola Odeku Street
Victoria Island, Lagos

hello@kivo.ng

Instagram
```

Bottom:

`© 2026 Kivo. All rights reserved.`

---

# 14. Responsive Requirements

The website must work at:

### Mobile

`320px – 767px`

### Tablet

`768px – 1023px`

### Desktop

`1024px+`

The design should not simply shrink.

Change layouts where necessary.

Examples:

Desktop:

```text
[ Image ] [ Text ]
```

Mobile:

```text
[ Image ]

[ Text ]
```

Desktop menu:

```text
[ Dish ] [ Dish ] [ Dish ]
```

Mobile:

```text
[ Dish ]
[ Dish ]
[ Dish ]
```

---

# 15. CSS Requirements

Your implementation must demonstrate:

* CSS reset
* CSS variables
* Flexbox
* CSS Grid
* Positioning
* Responsive media queries
* `max-width`
* `min-height`
* Spacing system
* Typography hierarchy
* Hover states
* Focus states
* Transitions
* Border styling
* Image handling
* Responsive typography

Use semantic HTML wherever possible.

Examples:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

Avoid building the entire website with `<div>` elements.

---

# 16. Accessibility Requirements

Include:

* Meaningful `alt` text for images
* Proper heading hierarchy
* Labels for form inputs
* Keyboard-accessible links/buttons
* Visible focus states
* Sufficient text contrast
* Semantic HTML

---

# 17. Technical Restrictions

For this version, use **only:**

```text
HTML
CSS
```

Do not use:

* JavaScript
* React
* Next.js
* Tailwind
* Bootstrap
* Component libraries
* Backend
* Database

You may use external fonts and image sources.

---

# 18. File Structure

Use:

```text
kivo/
│
├── index.html
├── menu.html
├── about.html
├── reservations.html
│
├── css/
│   └── style.css
│
├── images/
│   ├── hero.jpg
│   ├── dish-1.jpg
│   ├── dish-2.jpg
│   ├── dish-3.jpg
│   └── ...
│
└── README.md
```

---

# 19. Definition of Done

The project is finished when:

* All four pages are complete
* Navigation works
* Every page is responsive
* Images load correctly
* Forms contain proper validation
* Hover/focus states work
* No broken links exist
* No horizontal scrolling occurs on mobile
* HTML is semantic
* CSS is organized
* The website looks intentionally designed rather than assembled from random tutorials
* The project is deployed
* The code is pushed to GitHub
* The live URL works

---

# 20. Portfolio Presentation

Your GitHub README should contain:

**Kivo — Modern Nigerian Restaurant Website**

A short description:

`A responsive multi-page restaurant website built from scratch using semantic HTML and modern CSS.`

Then include:

* Project screenshot
* Features
* Technologies
* Design decisions
* Responsive behavior
* Live demo
* GitHub repository

The portfolio project should demonstrate that you can take a design brief and turn it into a **complete, responsive frontend without relying on a framework.**

---

# Final Constraint

Do not add features just because you know they exist.

There is no:

* Login
* Dashboard
* Payment system
* Database
* Reservation management
* CMS
* JavaScript animation
* Authentication

Those belong to later versions.

**Your job right now is to make the frontend excellent.**

Build the simplest version that satisfies the brief, then polish it until it looks like something a real restaurant would actually pay for.
