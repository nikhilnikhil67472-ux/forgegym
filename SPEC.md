# IronForge Gym Website Specification

## 1. Project Overview
- **Project Name**: IronForge Gym
- **Type**: Single-page marketing website
- **Core Functionality**: A bold, high-energy gym website showcasing the brand, services, trainers, and facilities with smooth animations and a commanding visual presence.
- **Target Users**: Potential gym members, fitness enthusiasts, people looking for personal training

## 2. UI/UX Specification

### Layout Structure
- **Navigation**: Fixed top navbar with logo, nav links, and CTA button
- **Sections**: Hero, About, Services, Trainers, Pricing, Contact, Footer
- **Responsive Breakpoints**:
  - Mobile: < 768px
  - Tablet: 768px - 1024px
  - Desktop: > 1024px

### Visual Design

#### Color Palette
- **Primary Background**: #0a0a0a (near-black)
- **Secondary Background**: #141414 (dark gray)
- **Accent Primary**: #ff3c00 (fierce orange-red)
- **Accent Secondary**: #ff6b35 (lighter orange)
- **Text Primary**: #ffffff
- **Text Secondary**: #a0a0a0
- **Card Background**: #1a1a1a
- **Border/Highlight**: #2a2a2a

#### Typography
- **Headings**: "Bebas Neue", sans-serif (bold, uppercase, commanding)
- **Body**: "Barlow", sans-serif (clean, readable)
- **Hero Title**: 96px desktop / 48px mobile
- **Section Titles**: 64px desktop / 36px mobile
- **Body Text**: 18px
- **Small Text**: 14px

#### Spacing System
- **Section Padding**: 100px vertical desktop / 60px mobile
- **Container Max Width**: 1200px
- **Card Padding**: 32px
- **Element Gap**: 24px

#### Visual Effects
- **Hero Background**: Dark gradient with subtle diagonal stripe pattern overlay
- **Cards**: Subtle border glow on hover (accent color)
- **Buttons**: Scale transform on hover (1.05), background color shift
- **Scroll Animations**: Fade-in-up on scroll for sections

### Components

#### Navigation
- Logo (text-based "IRONFORGE")
- Nav links: About, Services, Trainers, Pricing, Contact
- CTA Button: "JOIN NOW" with accent background
- Mobile: Hamburger menu with slide-in drawer

#### Hero Section
- Full viewport height
- Large headline: "FORGE YOUR STRENGTH"
- Subheadline: "Transform your body. Conquer your goals."
- Two buttons: "START FREE TRIAL" (primary), "VIEW CLASSES" (outline)
- Background: Dark with diagonal stripe pattern + gradient overlay

#### About Section
- Two-column layout: image placeholder on left, text on right
- Brief brand story
- Stats: "10+ Years", "500+ Members", "50+ Trainers", "24/7 Access"

#### Services Section
- Grid of 4 service cards:
  1. Strength Training - weights icon
  2. Cardio - heart icon
  3. Personal Training - user icon
  4. Group Classes - people icon
- Each card: icon, title, description, price

#### Trainers Section
- Grid of 3 trainer cards
- Each: placeholder image, name, specialty, brief bio

#### Pricing Section
- 3 pricing tiers: Basic, Pro, Elite
- Feature list with checkmarks
- Highlighted "Pro" tier as recommended

#### Contact Section
- Two columns: contact info + map placeholder
- Address, phone, email
- Simple contact form (name, email, message)

#### Footer
- Logo
- Quick links
- Social icons placeholder
- Copyright

## 3. Functionality Specification

### Core Features
- Smooth scroll navigation to sections
- Mobile hamburger menu toggle
- Scroll-triggered fade animations
- Hover effects on cards and buttons
- Form validation (HTML5)

### User Interactions
- Click nav links → smooth scroll to section
- Click hamburger → toggle mobile menu
- Hover cards → subtle lift and glow
- Scroll → elements fade in from below
- Submit form → browser alert (demo)

### Edge Cases
- Navigation works with JavaScript disabled (anchor links)
- Images have alt text
- Forms have proper labels

## 4. Acceptance Criteria
- [x] Page loads without errors
- [x] All sections visible and properly styled
- [x] Navigation links scroll to correct sections
- [x] Mobile menu works on small screens
- [x] Hover effects work on interactive elements
- [x] Typography is bold and readable
- [x] Color scheme is consistent throughout
- [x] Responsive on mobile, tablet, desktop