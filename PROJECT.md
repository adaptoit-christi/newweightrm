# The Weight RM Website - Project Documentation

**Last Updated:** January 4, 2025 (8:55 PM)
**Client:** The Weight RM - Torrance, CA Gym
**Owners:** Antonio & Clayton (Lead Trainers & Co-Owners)

## Project Overview

Premier fitness gym website for The Weight RM located in Torrance, South Bay CA. The site focuses on science-backed personal training, semi-private training, and group conditioning classes.

### Deployment Strategy
- **Staging:** Vercel (connected to GitHub for continuous deployment)
- **Production:** Wix (will migrate once client signs off)
- **Version Control:** GitHub repository

## Site Structure

### Pages
1. **index.html** - Homepage
   - Hero section with gym interior image
   - "Control the Controllables" tagline
   - Science-backed coaching approach
   - Training programs (One-on-One & Semi-Private)
   - Trainers section (Antonio & Clayton)
   - Services & resources overview
   - Contact information

2. **membership.html** - Pricing & Plans
   - Semi-Private Training packages (8/12/16 sessions)
   - AutoPay vs One-time payment options
   - HYROX Conditioning Classes (4/8/12 class packs)
   - Gym Classes (4/8 class packs, drop-in)
   - **Price increase notice:** Current pricing through Dec 31, 2025
   - **New 2026 pricing** shown in yellow notice box
   - Free consultation CTA

3. **products.html** - Product Recommendations
   - Footwear: Xero Shoes, WHITIN
   - Nutrition: David's Protein Bars
   - Supplements: Momentous (protein, creatine, magnesium)
   - Affiliate disclosure
   - Personal recommendation philosophy
   - Category filtering (JavaScript tabs)

4. **contact.html** - Contact & Join
   - Three pathways: New Member, Existing Member, Questions
   - Clubworx join form (iframe integration)
   - Contact information (phone, email, address)
   - Quick FAQ section
   - Free consultation offer

5. **book-online.html** - Session Booking
   - Clubworx weekly agenda calendar (iframe)
   - Semi-Private Training booking
   - HYROX Classes booking
   - Gym Classes booking
   - Help section for first-timers
   - New member consultation CTA

6. **blog.html** - Training Insights
   - Featured article section
   - Blog post grid (5 articles shown)
   - Sidebar: Categories, Recent articles, Quick tips
   - Newsletter signup form
   - All articles marked "Coming Soon"

7. **calendar.html** - Training Schedule
   - Visual calendar grid (January 2025)
   - Color-coded availability (green/yellow/red)
   - Session types: Semi-Private, One-on-One, Group Classes
   - Quick booking form
   - Booking guidelines

### Supporting Files
- **wix-version.html** - Wix-specific version
- **products-backup.html** - Backup of products page

## Brand & Design

### Color Palette
- **Primary Green:** `#556B2F` (gym-green)
- **Light Green:** `#6B7F3A` (gym-green-light)
- **Dark Green:** `#4A5D2A` (gym-green-dark)
- **Background:** Gray-50 (#f9fafb)
- **Text:** Gray-900 (#111827)

### Typography
- **Font:** Inter (Google Fonts)
- **Weights:** 300, 400, 500, 600, 700, 800

### Design Philosophy
- Clean, minimal, professional
- Evidence-based messaging (references to Galpin, Norton, Huberman)
- Direct, honest tone
- No fluff or marketing gimmicks
- Focus on consistency and progressive overload

## Key Features

### Third-Party Integrations
1. **Clubworx** - Gym management system
   - Join form: `https://app.clubworx.com/websites/theweightrm/join/iframe`
   - Calendar booking: `https://app.clubworx.com/websites/theweightrm/calendar/weekly_agenda_iframe`
   - Powers membership management and booking

2. **Tailwind CSS** - Via CDN
   - Custom color configuration
   - Responsive utilities
   - Component styling

### SEO Optimization
- Schema.org structured data (Gym type)
- Location-specific keywords (Torrance, South Bay, CA)
- Meta descriptions for all pages
- Keywords targeting local fitness market
- Geo coordinates: 33.8358, -118.3406

### Accessibility
- Skip links for screen readers
- ARIA labels on interactive elements
- Focus indicators on all focusable elements
- Semantic HTML structure
- Alt text on all images

## Contact Information

**Address:** 2535 W. 237th Street Suite 128, Torrance, CA 90505
**Phone:** (310) 406-7938
**Email:** info@theweightrm.com
**Website (Staging):** newweightrm.vercel.app

## Brand Messaging

### Core Philosophy
- "Control the Controllables"
- Science-backed programming (not guesswork)
- Progressive overload focus
- Consistency beats motivation
- Earned recognition, not participation trophies
- Direct coaching with honest feedback

### Training Approach
- Evidence-based methods
- References: Galpin, Norton, Huberman
- Individual programming in group settings
- Real-time form corrections
- Session-by-session progression tracking

### Target Audience
- People ready to commit to getting stronger
- Willing to be coached
- Value consistency and discipline
- Looking for science-backed approach
- Located in Torrance/South Bay area

## Pricing Structure (Current - Through Dec 31, 2025)

### Semi-Private Training
**AutoPay (Best Value):**
- 8 sessions/month: $320 ($40/session)
- 12 sessions/month: $420 ($35/session) - Best Value
- 16 sessions/month: $480 ($30/session)

**One-Time Packages:**
- 8 sessions: $360 ($45/session) - 2 month expiration
- 12 sessions: $468 ($39/session) - 3 month expiration
- 16 sessions: $576 ($36/session) - 4 month expiration

### HYROX Classes
- 4 classes: $144 ($36/class) - 2 month expiration
- 8 classes: $264 ($33/class) - 3 month expiration
- 12 classes: $360 ($30/class) - 4 month expiration

### Gym Classes
- 4 classes: $99 ($24.75/class) - 2 month expiration
- 8 classes: $159 ($19.88/class) - 2 month expiration
- Drop-in: $30 single class

### 2026 Price Increase (Effective Jan 1, 2026)
**Semi-Private Packages:**
- 16 sessions: $680 ($42.50/session)
- 12 sessions: $525 ($43.75/session)
- 8 sessions: $400 ($50.00/session)

**Semi-Private AutoPay:**
- 16 sessions: $600 ($37.50/session)
- 12 sessions: $480 ($40.00/session)
- 8 sessions: $360 ($45.00/session)

*HYROX and Gym class pricing unchanged for 2026*

## Image Assets

### Gym Photos
- `images/logo-full.jpg` - Full logo with text
- `images/IMG_3595-1.jpg` - Hero/gym interior
- `images/IMG_3596-2.jpg` - Training equipment
- `images/IMG_3669-3.jpg` - Gym interior view
- `images/IMG_3675-6.jpg` - Professional dumbbells
- `images/IMG_3682-8.jpg` - Training space

### Trainer Photos
- `images/Antonio.jpg` - Antonio (Lead Trainer & Co-Owner)
- `images/Clayton.jpg` - Clayton (Lead Trainer & Co-Owner)

### Product Images
- `images/xeroshoes.png` - Xero Shoes
- `images/whitin.jpg` - WHITIN barefoot shoes
- `images/davidprotein.png` - David's Protein Bars
- `images/momentous.png` - Momentous supplements

## Navigation Structure

**Main Navigation (Desktop):**
Home | Membership | Book Online | Contact | Calendar | Blog | Products

**Mobile Navigation:**
- Hamburger menu
- Same links as desktop
- Slide-out menu

**Footer Links:**
- Quick Links (Home, Membership, Book Online, Contact, Calendar)
- Training Options (Semi-Private, HYROX, Gym Classes, Blog, Products)
- Contact Info (Phone, Email, Schedule Consultation)

## Technical Notes

### JavaScript Functionality
1. **Mobile Menu Toggle** - All pages
2. **Smooth Scrolling** - index.html anchor links
3. **Form Handlers** - Alert-based (to be replaced with real submissions)
4. **Product Category Tabs** - products.html filtering
5. **Calendar Interactions** - calendar.html session booking
6. **Newsletter Signup** - blog.html

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Tailwind CSS via CDN (latest version)

## Content Strategy

### Tone & Voice
- Direct and honest
- No excessive hype or marketing speak
- Evidence-based claims
- Professional but approachable
- Action-oriented ("Do the work", "Show up")

### Key Phrases
- "Control the Controllables"
- "Consistency beats motivation"
- "Progression beats perfection"
- "Evidence-based programming"
- "Earned recognition"
- "Progressive overload"

## Known Items / To-Do
- [ ] Blog articles are placeholders (all marked "Coming Soon")
- [ ] Social media icons in footer are placeholders (no real links)
- [ ] Forms use alert() - need backend integration
- [ ] Newsletter signup needs integration
- [ ] Analytics tracking to be added
- [ ] Final client review before Wix migration
- [ ] Verify all Clubworx iframe integrations work on Wix

## Development Workflow

1. **Staging:** Push to GitHub → Auto-deploy to Vercel
2. **Testing:** Review on Vercel staging site
3. **Client Review:** Share Vercel link with Antonio & Clayton
4. **Approval:** Get sign-off from owners
5. **Production:** Migrate to Wix platform
6. **Launch:** Update DNS/domains to point to Wix

## Recent Updates

### Latest Commits (from git log)
- 9f4077b - Make product images square and show full images
- 923f634 - Remove training hours from contact page
- 07a3906 - Clean up filler content and placeholder links
- 648c291 - Fix navigation consistency across all pages
- da73291 - Update hero image overlay text

## Notes for Future Reference

- **Image Strategy:** Product images are set to `aspect-square` with full object-contain to show complete product images
- **Pricing Notice:** Yellow notice box prominently displays 2026 price increase
- **Booking Flow:** Contact page for new members → Book Online for existing members
- **Free Consultation:** Featured on multiple pages as primary CTA for new leads
- **Clubworx Dependency:** All booking and membership management relies on Clubworx integration

---

**Project Manager:** Christi (AdapToIT)
**Client Contacts:** Antonio & Clayton (The Weight RM)
**Location:** OneDrive - AdapToIT\02_Clients\The Weight RM\10_Website
