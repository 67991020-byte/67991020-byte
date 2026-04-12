# About Me Website Design Specification

## 1. Concept & Vision

A clean, modern personal portfolio site that reflects Poovee's identity as a Computer Engineering student focused on IoT and Networking. The design should feel tech-forward yet approachable—like a well-organized digital workspace with personality.

## 2. Design Language

### Aesthetic Direction
Dark theme with neon accents, inspired by terminal/code aesthetics but softened for readability. Think "developer workspace meets modern dashboard."

### Color Palette
- **Primary Background**: `#0f0f1a` (deep navy-black)
- **Secondary Background**: `#1a1a2e` (card backgrounds)
- **Primary Accent**: `#45f7b2` (mint green - main highlights)
- **Secondary Accent**: `#61dafb` (cyan - secondary elements)
- **Text Primary**: `#ffffff`
- **Text Secondary**: `#a0a0b0`
- **Gradient**: Linear from `#45f7b2` to `#61dafb`

### Typography
- **Headings**: "Fira Code", monospace (tech feel)
- **Body**: "Inter", sans-serif (readability)
- **Code/Terminal elements**: "Fira Code"

### Spatial System
- Base unit: 8px
- Section padding: 80px vertical, 24px horizontal
- Card padding: 24px
- Border radius: 12px for cards, 8px for buttons

### Motion Philosophy
- Subtle fade-in on scroll (300ms ease-out)
- Hover lifts on cards (transform: translateY(-4px))
- Typing animation for hero tagline
- Skill badges pulse subtly on hover

## 3. Layout & Structure

### Sections (top to bottom)
1. **Hero** - Name, tagline with typing effect, avatar/gif, social links
2. **About** - Profile overview with YAML-style layout
3. **Skills** - Tech stack organized by category with badges
4. **Goals** - Current focus and 2025 goals
5. **Quote** - Personal motto with styling

### Responsive Strategy
- Desktop: Max-width 1200px, centered
- Tablet: Stack columns, reduce padding
- Mobile: Single column, full-width cards

## 4. Features & Interactions

- Typing animation on hero tagline
- Hover effects on skill badges
- Smooth scroll navigation
- Social links with hover color transitions
- GitHub activity graph embed (or placeholder)

## 5. Component Inventory

### Hero Section
- Large heading with gradient text
- Animated typing tagline
- GIF/avatar area
- Social badge buttons

### Profile Card
- YAML-style key-value display
- Icon accents for each item

### Skill Badge
- Rounded pill shape
- Icon + text
- Hover: glow effect

### Quote Block
- Centered italic text
- Decorative quotes
- Subtle background

## 6. Technical Approach

- Single HTML file with embedded CSS and JS
- No frameworks - vanilla HTML/CSS/JS
- Google Fonts for typography
- CSS custom properties for theming
- Intersection Observer for scroll animations
