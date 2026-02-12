# Tuontimesta.fi - Static Site Migration

Migration of www.tuontimesta.fi from Squarespace to self-hosted static website with enhanced copy and functionality.

## Project Overview

**Current State:** Squarespace-hosted business website for Finnish car import company
**Target:** Self-hosted static HTML/CSS site on personal VPS
**Business:** Car importing with 25 years experience (since 1999), specializing in German imports

## Current Site Analysis

### Structure
- Single-page design with sticky navigation
- Mobile-responsive with hamburger menu
- Clean, professional business layout

### Navigation
- Etusivu (Home)
- Hinnasto (Price List)
- Linkkejä (Links)
- Yhteystiedot (Contact Info)

### Content Sections
1. **Hero Section:** Mercedes vehicle image with tagline "Autojen maahantuontia 25 vuoden kokemuksella"
2. **About (MEISTÄ):** Three key points - experience since 1999, technical training, German import focus
3. **Services (PALVELUMME):** Four service points covering selection, test drives via WhatsApp, transport/customs, inspections
4. **Pricing Examples:** Six detailed cost breakdowns across vehicle categories
   - Electric vehicles
   - Gas/Diesel/Hybrid
   - Other vehicles (specialty equipment)
5. **Instagram Feed:** Nine embedded posts showing vehicles and updates
6. **Contact:** Phone, WhatsApp, email, physical addresses (Lahti + Berlin)

### Design Elements
- **Color Scheme:** Dark backgrounds (#222222), white text, clean accents
- **Typography:** Sans-serif, hierarchical heading structure
- **Imagery:** High-quality vehicle photography, port/showroom lifestyle shots
- **Layout:** Grid-based showcases, card-style pricing examples

### Key Features
- WhatsApp video integration for test drives
- Instagram feed widget
- Pricing transparency with detailed formulas
- Multi-location display (Lahti, Berlin)
- References to mobile.de and autoscout24.de

### SEO Elements
- WebSite schema with name "Tuontimesta"
- LocalBusiness structured data
- Google Analytics (UA-36963523-1)
- Finnish language (fi-FI)
- Europe/Helsinki timezone

### Brand Tone
- Professional yet approachable
- Transparent and honest pricing
- Emphasis on experience and convenience
- Key message: "Valitse autosi verkosta, me hoidamme loput" (Choose your car online, we handle the rest)
- Soft CTA approach - informative rather than aggressive

## Migration Goals

### Core Requirements
1. ✅ Maintain all existing content and functionality
2. ✅ Preserve SEO value and structured data
3. ✅ Ensure mobile responsiveness
4. ✅ Keep multi-location information accessible
5. ✅ Maintain pricing transparency

### Enhancements

#### Content/Copy Improvements
- [ ] Refine hero section tagline for stronger impact
- [ ] Expand about section with more compelling storytelling
- [ ] Enhance service descriptions with benefit-focused copy
- [ ] Add customer testimonials/social proof
- [ ] Create more detailed FAQ section
- [ ] Improve call-to-action clarity and placement

#### Design Enhancements
- [ ] Modern, clean aesthetic (maintaining professionalism)
- [ ] Improved typography and readability
- [ ] Better visual hierarchy
- [ ] Enhanced mobile experience
- [ ] Optimized image loading and performance
- [ ] Accessibility improvements (WCAG compliance)

#### Functionality Additions
- [ ] Contact form (replacing Squarespace forms)
- [ ] WhatsApp click-to-chat integration
- [ ] Better Instagram feed integration or static gallery
- [ ] Pricing calculator tool (interactive)
- [ ] Newsletter signup
- [ ] Multi-language support (Finnish/English/German?)

#### Technical Improvements
- [ ] Optimized performance (static HTML/CSS)
- [ ] Better structured data markup
- [ ] OpenGraph and Twitter Card meta tags
- [ ] Modern SEO best practices
- [ ] Privacy-focused analytics alternative
- [ ] HTTPS and security headers

## Technical Approach

### Stack
- Pure HTML5/CSS3 (similar to jani.laatunen.fi)
- No build system initially (can add later if needed)
- Variable fonts for performance
- Mobile-first responsive design
- Semantic HTML with proper accessibility

### Third-Party Services
- Instagram feed: TBD (static gallery or API integration)
- Forms: TBD (Formspree, Netlify Forms, or custom solution)
- Analytics: TBD (Plausible, Simple Analytics, or privacy-focused alternative)

### Hosting
- Personal VPS deployment
- Static file serving
- SSL/TLS certificate
- CDN consideration for assets

## Content Sections to Migrate

### Priority 1 (MVP)
- [x] Site analysis complete
- [ ] Hero section
- [ ] About section
- [ ] Services section
- [ ] Pricing examples
- [ ] Contact information
- [ ] Basic navigation

### Priority 2 (Enhancements)
- [ ] Enhanced copy writing
- [ ] Instagram gallery (static or integrated)
- [ ] Contact form
- [ ] Links page
- [ ] FAQ section

### Priority 3 (Nice-to-have)
- [ ] Interactive pricing calculator
- [ ] Newsletter integration
- [ ] Multi-language support
- [ ] Blog/news section

## Enhancement Opportunities

### Copy Writing Focus Areas
1. **Hero Section:** Create more emotionally compelling headline while maintaining professionalism
2. **Value Proposition:** Clearer articulation of unique benefits vs competitors
3. **Trust Signals:** Incorporate 25 years experience more prominently with specific milestones
4. **Process Clarity:** Step-by-step journey from selection to delivery
5. **Social Proof:** Customer stories and testimonials
6. **SEO Content:** Natural keyword integration without sacrificing readability

### UX Improvements
1. Clearer navigation with descriptive labels
2. Sticky CTA for quick contact
3. Progressive disclosure for pricing details
4. Better mobile touch targets
5. Improved form usability

## Next Steps

1. Create initial HTML structure based on analysis
2. Draft enhanced copy for each section
3. Design modern, clean aesthetic
4. Implement responsive layout
5. Add interactive elements (forms, pricing calculator)
6. SEO optimization
7. Testing and refinement
8. VPS deployment configuration

## Notes

- Maintain Finnish as primary language
- Consider German/English translations for broader reach
- Preserve WhatsApp integration (critical feature)
- Keep pricing transparency as core differentiator
- Instagram integration important for social proof
