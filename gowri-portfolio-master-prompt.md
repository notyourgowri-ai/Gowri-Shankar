# MASTER AI PROMPT — Build a Premium Personal Brand Portfolio for Gowri

## Overview

You are an award-winning UI/UX designer, senior React developer, creative developer, branding expert, and motion designer. Your task is to create an immersive, premium-quality personal brand portfolio website for **Gowri**, a Digital Marketer, Dropshipping Entrepreneur, Content Marketing Strategist, and Educator who provides affordable courses in Web Development, Digital Marketing, and Content Marketing.

The website should feel like a modern interactive experience instead of a traditional portfolio — closer to a polished UI/UX case-study showcase than a busy sales page. Every page should tell a story, build trust, demonstrate expertise, and encourage visitors to connect, hire, or enroll in courses.

The overall design should be **dark, minimal, confident, and premium** — mobile-first, fast, and visually memorable.

---

# Technology Stack (Strictly Use)

**Frontend**
* React.js (Vite)
* React Router DOM
* Tailwind CSS

**Animations**
* Framer Motion (Primary animation library)
* React Intersection Observer

**3D / Depth (used sparingly, not overloaded)**
* Three.js
* React Three Fiber
* Drei

**Utilities**
* React Icons
* Lenis (Smooth scrolling)
* EmailJS or Resend API
* React Helmet

Do NOT use Next.js.

---

# Design Inspiration

* Apple (product pages)
* Linear / Vercel (dark UI, clean type)
* Modern UI/UX case-study decks (like Behance/Dribbble "case study cover" templates)
* Awwwards dark-mode portfolios

The site should feel confident, editorial, and product-grade — not "AI-generated flashy," but deliberately restrained with one or two standout moments per page.

---

# Theme

**Dark Minimal + Bold Accent**

Think: a black stage with a single spotlight. Calm dark backgrounds, generous whitespace (black-space), and one vivid accent color doing all the emotional work — like a UI/UX case-study cover.

Visual elements include:
* Near-black backgrounds (charcoal, not pure #000)
* Subtle grain/noise texture for depth
* Soft vignette lighting
* Large, bold display typography
* Sparse, deliberate glow/blur accents (not everywhere — just key CTAs and hero)
* Product/device mockups presented on dark pedestals or floating cards
* Minimal grid layouts with strong alignment

---

# Color Palette

**Primary**
* Rich Black / Charcoal (`#0A0A0A`–`#151515`)
* Off-white / Soft White (`#F5F5F5`)

**Accent (the "hero" color — used boldly, sparingly)**
* Vivid Orange (`#FF5A1F`–`#FF6B2C`)

**Secondary / Supporting**
* Warm Gray (for cards, borders)
* Muted Amber (for hover/secondary highlights)

**Background**
* Solid dark with subtle radial gradient glow
* Soft grain texture overlay
* No heavy particle fields — use restraint

---

# Global Features

* Smooth, purposeful animations (not "heavy" — every motion should feel intentional)
* Cinematic page transitions
* Fully responsive, mobile-first layouts
* Smooth scrolling (Lenis)
* SEO optimization (React Helmet, meta tags, semantic HTML)
* Accessibility (contrast-checked against dark backgrounds, keyboard nav, alt text)
* High Lighthouse scores (95+)

---

# Navigation

Floating dark glass navbar with a subtle bottom border and blur.

**Pages**
* Home
* About
* Services
* Skills
* Projects
* Courses
* Articles
* Testimonials
* Resume
* Contact

Navigation animates in with a slide/fade using Framer Motion. Active page indicator uses the orange accent underline/dot.

Page transitions: fade + slight vertical slide, or a subtle "curtain" wipe in charcoal — keep it clean, avoid overly playful transitions.

---

# Hero Section

**Headline**
"Helping Businesses Grow with Digital Marketing, E-commerce & Modern Web Skills"

**Subheading**
Digital Marketer • Dropshipping Entrepreneur • Content Marketing Strategist • Educator

**Buttons**
* Hire Me (filled orange, primary)
* View My Work (outline, secondary)
* Explore Courses (text link with arrow)

**Visual**
A large type-driven hero (like the reference image) — oversized headline text with one accent word in orange, paired with a single supporting visual: a floating device mockup, dashboard screenshot, or abstract 3D shape casting soft light. Avoid crowding the hero with many 3D objects — one clean focal element is stronger.

---

# About Page

Tell Gowri's story.

**Include**
* Personal introduction
* Career journey (how she moved into digital marketing, dropshipping, and teaching)
* Mission & vision
* Teaching philosophy — why she makes courses affordable and accessible
* Future goals

**Animated counters** (simple number count-up on scroll, no clutter)
* Students Trained
* Businesses Helped
* Courses Published
* Client Satisfaction

---

# Services Page

Present services as clean, dark cards with a single orange accent border/glow on hover (not tilt-heavy — restrained hover states: slight lift + border glow).

**Digital Marketing**
* SEO
* Google Ads
* Meta Ads
* Instagram Growth
* Brand Strategy

**Content Marketing**
* Copywriting
* Social Media Strategy
* Blog Strategy
* Content Planning

**Dropshipping**
* Shopify Store Setup
* Product Research
* Winning Products
* Store Optimization

**Training**
* Digital Marketing Course
* Web Development Course
* Content Marketing Course

---

# Skills Page

Display expertise with clean, minimal progress bars or dot-rating indicators (dark card, orange fill) — no overly busy icon animations.

**Marketing** — SEO, SEM, Meta Ads, Google Ads, Email Marketing, Analytics
**Development** — HTML, CSS, JavaScript, React, Tailwind
**Design** — Canva, Figma, Photoshop
**Business** — Shopify, Branding, Sales Funnels, CRM
**Soft Skills** — Communication, Leadership, Problem Solving, Public Speaking

---

# Projects Page

Showcase best work as **case-study cards** — styled like the reference image (dark card, bold title, one accent stat like "60KM" style callout numbers for results).

**Each project card includes**
* Cover image/mockup on dark background
* Short description
* Tools/technologies used
* Key result (e.g., "+40% engagement", styled as a bold stat)
* Client feedback (short quote)
* Live demo / link

**Hover**
Subtle lift + border glow — no heavy 3D tilt, keep it minimal and premium.

Clicking opens a full case-study page: Problem → Approach → Solution → Result, styled like a UI/UX case study deck.

---

# Courses Page

Course cards with a dark theme and orange accent badges for price/level.

**Each card includes**
* Thumbnail
* Title
* Description
* Difficulty level (badge)
* Duration
* Price
* Topics covered
* Enroll button (orange filled)

**Courses**
* Web Development
* Digital Marketing
* Content Marketing

Include a short testimonials strip and clear learning outcomes per course.

---

# Articles Page

Feature educational content from Medium / Hashnode / Dev.to / personal blog.

**Each article card**
* Cover image
* Summary
* Reading time
* Publish date
* Tags
* "Read More" link

---

# Resume Page

* Download Resume / View Resume buttons
* Education
* Experience
* Certifications
* Achievements
* Skills summary

Styled as a clean, printable-feeling dark page with strong typographic hierarchy.

---

# Testimonials

Elegant, minimal testimonial cards — dark background, subtle border, client photo, name, role/company, short quote. Fade/slide in on scroll, no excessive motion.

---

# Contact Page

**Fields:** Name, Email, Subject, Message

**Features**
* EmailJS or Resend integration
* Form validation
* Success/loading animation (simple checkmark/spinner, not flashy)
* Spam protection

**Display:** Email, WhatsApp, Location, Social links

---

# Social Links

LinkedIn, Instagram, YouTube, WhatsApp, Telegram, Medium/Hashnode.

Hover: simple scale + orange glow — understated, not overly animated.

---

# Call-to-Action (near footer)

**Headline:** "Ready to Grow Your Business or Learn New Skills?"

**Buttons:** Book a Consultation • Enroll in a Course • Hire Me • Contact Me

Background: solid dark with a soft orange radial glow — echo the hero's restrained lighting style.

---

# Footer

* Brand logo/name
* Navigation
* Social links
* Newsletter subscription
* Copyright
* "Built with React & Framer Motion"

---

# Animation Principles

* Motion should be purposeful, not decorative — fades, slides, and scale-ins on scroll
* Spring physics for buttons/cards (subtle, not bouncy)
* Letter/word reveal for major headlines only (hero, section titles)
* No element should appear abruptly, but avoid over-animating every pixel — the dark minimal aesthetic depends on restraint

---

# Mobile Optimization

* Fully responsive, touch-friendly navigation
* Responsive typography scaling
* Reduced/no 3D on smaller devices
* Smooth performance on low-end phones

---

# Performance

* 60 FPS
* Lazy loading & code splitting
* Compressed assets
* Lighthouse score above 95

---

# Content Management

Store all editable content (bio, services, projects, courses, articles, testimonials, social links) in a single configuration file so updates require no UI component changes.

---

# Final Goal

Create a portfolio that feels like a premium, dark-mode product case study — confident, uncluttered, and credible — establishing Gowri as a trusted digital marketing expert, educator, and entrepreneur. Every visual choice should reinforce professionalism and clarity over noise, guiding visitors naturally toward hiring her, enrolling in a course, or connecting on social platforms — while staying fast, accessible, and mobile-friendly.
