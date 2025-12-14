# Barbershop Website Mockups

## Project Overview

This repository contains **5 distinct website design mockups** for a barbershop business opening its second location in Chelmsford, UK. The business operates two barbershops:

1. **Man About Town** - 62 New London Rd, Chelmsford, CM2 0PA (Tel: 01245 354 333)
2. **New London Barbers** - 45 High Street, Chelmsford, CM1 1DH (Tel: 01245 123 456)

## Project Structure

```
barbershop-website/
├── index.html          # Landing page with links to all 5 designs
├── design1/
│   └── index.html     # Classic Dark Hero design (PRIMARY/ACTIVE DESIGN)
├── design2/
│   └── index.html     # Split-Screen Dual Location design
├── design3/
│   └── index.html     # Minimal Bold Typography design
├── design4/
│   └── index.html     # Vintage Warmth design
└── design5/
    └── index.html     # Contemporary Pro with Side Nav design
```

## Important Information

### Primary Design
**design1** is the primary/active design that has received the most refinement and should be considered the main reference for any updates.

### Technical Constraints
- **HTML and CSS only** (including Tailwind CSS via CDN)
- **Minimal JavaScript** - only use when absolutely necessary
- **Mobile responsive** - all designs must work on mobile devices
- **No build process** - pure HTML files that can be opened directly in a browser

### Business Information

#### Booking URLs
- Both shops currently use the same booking URL: `https://iframe-678.nearcut.com/book/shops/NKOYJS/`
- This is intentional as the second shop doesn't have its own URL yet

#### Opening Hours (Both Locations)
- Monday - Wednesday: 9:00 AM - 6:00 PM
- Thursday: 9:00 AM - 8:00 PM
- Friday - Saturday: 9:00 AM - 6:00 PM
- Sunday: Closed

#### Barbers
The website features 8 barbers split between the two locations:
- 4 barbers at Man About Town
- 4 barbers at New London Barbers

Each barber should have:
- Name
- Shop location (indicated with colored barber pole icon)
- Short bio/specialties
- Headshot photo (currently using stock images)

#### Color Coding
The two shops are differentiated by barber pole icon colors:
- **Man About Town**: Gold (#d4af37)
- **New London Barbers**: Blue (#4a90e2)

These colors should be distinct and easily distinguishable.

### Design Decisions & Best Practices

#### Navigation
- Fixed navigation with gradient fade at bottom (no harsh line)
- Background: `linear-gradient(to bottom, rgba(0,0,0,0.5) 0%, rgba(0,0,0,0.3) 80%, rgba(0,0,0,0) 100%)`
- Includes backdrop blur for modern glass effect

#### Hero Section
- Single "Book Now" button that links to #locations
- Bouncing down arrow indicator to encourage scrolling
- Equal prominence for both shop names

#### Locations Section
- Serves as the primary booking CTA
- Each location card has a prominent "Book at [ShopName]" button at the TOP
- Includes full contact details, hours, and embedded Google Maps
- Subtitle emphasizes appointment-based booking

#### Gallery Section (Our Work)
- Last grid item is an Instagram CTA
- Links to: `https://www.instagram.com/manabouttownbarbers/`
- Text: "See more" and "on Instagram" (two lines, same size)
- Uses Instagram gradient background (purple to pink to orange)

#### Section Order (design1)
1. Hero
2. About
3. Barbers (Meet Our Barbers)
4. Gallery (Our Work)
5. Locations (with booking CTAs)
6. Footer

Note: There is NO separate "Book Your Appointment" section - all booking is handled in Locations.

### Content Guidelines

#### Placeholder Content
- Use stock photos from Unsplash for images
- Use placehold.co for barber headshots if needed
- Barber names and bios are placeholder content

#### Instagram CTA
- Must be visually balanced (not squashed)
- Icon, text, and spacing should fill the square appropriately
- No arrow or external link icons needed - the gradient makes it obviously clickable

#### Styling Consistency
- Primary color (cream): #ccc9c2
- Dark backgrounds: #212020, #1a1a1a
- Use Playfair Display for headings
- Use Inter for body text

### Reference Websites

The designs were inspired by:
- Original site: https://manabouttownbarbers.co.uk
- Target aesthetic: https://brooksbarbershops.co.uk

Both sites feature dark, sophisticated aesthetics with professional photography and clean layouts.

## Development Notes

### When Making Changes
1. **design1 is primary** - apply major updates here first
2. **Test responsiveness** - check mobile, tablet, and desktop views
3. **Maintain equal shop prominence** - both locations should feel equally important
4. **Keep it simple** - avoid over-engineering or unnecessary features
5. **No auto-playing carousels** - design1 previously had one but it was removed for simplicity

### Common Pitfalls to Avoid
- Don't make one shop appear more prominent than the other
- Don't add complicated JavaScript features
- Don't create separate booking sections (it's integrated in Locations)
- Don't use harsh borders on navigation
- Don't make barber pole colors too similar (they need clear distinction)
- Don't squash content in the Instagram CTA square

## Footer
- Copyright year: 2026
- Social links: Facebook and Instagram (no Twitter)
- Include contact information for both locations

## Future Considerations
- When the second shop gets its own booking URL, update both booking buttons accordingly
- Real barber photos and bios will need to be added
- Actual Instagram URL may need updating when account is finalized
- Consider adding actual customer testimonials/reviews
