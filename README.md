# The Art of Noticing

Photography by Kendrick Henson. A modern editorial photography portfolio and geographic visual archive.

## Creative direction
Modern editorial minimalism meets geographic exploration. Photography remains dominant; generous whitespace, subtle cartographic details, and exhibition-style collections establish the visual identity.

- Brand language: The Art of Noticing.
- Secondary tagline: Exploration / Adventure / Photography.
- Typography: Cormorant Garamond, Manrope, IBM Plex Mono.
- Foundation: paper #F5F3ED, charcoal #242820, sage #737C68, terracotta #B16B45, sand #D9D2C3, slate blue #426675, ochre #C39D53.
- Collection-specific accent palettes will be curated from original photographs.
- Only original photography will be used in the public portfolio. During prototyping use descriptive photo briefs, not stock images.

## Run the prototype
Download index.html and open it in a browser, or serve the repository with `python3 -m http.server 8000` and open http://localhost:8000. Google Fonts requires an internet connection; system fallback fonts are included.

## Version 0.1
A responsive standalone HTML/CSS homepage with navigation to collections, Explore, Field Notes, and About. Photo placeholders are labeled with suggested subjects and compositions. Map and editorial content are explicitly illustrative, not live features.

## Roadmap
- [x] Establish creative direction
- [x] Create repository and initial homepage
- [ ] Review rendered homepage on desktop and mobile
- [ ] Separate reusable styles and collection components
- [ ] Implement exhibition pages, category filters, and selected work
- [ ] Connect Sanity Studio (proposed) with image assets, bulk upload, ordering, captions, cover images, color accents, and publication controls
- [ ] Implement geographic map using approved collection coordinates
- [ ] Build Field Notes blog and fullscreen photo viewer
- [ ] Add About, contact, accessibility and performance checks
- [ ] Select hosting and domain, migrate original photographs, launch

## Content model (planned)
Collections: title, slug, description, location, optional public coordinates, dates, categories, cover, ordered image assets, accent palette, publication state.
Photos: asset reference, alt text, optional caption and metadata. Original filenames can be retained; asset identifiers handle uniqueness. Do not publish private or sensitive GPS metadata automatically.
Field notes: title, slug, date, cover, article body, related collections, publication state.

GitHub stores code; the planned CMS stores content and image assets. No credentials should be committed. Sanity and hosting are not connected yet.
