# Hamza Ben Ayed Portfolio

Static portfolio website built with HTML, CSS, Bootstrap, and JavaScript.

## Run Locally

Open `index.html` with Live Server in VS Code.

## About Section Update

A new role placeholder was added in the About timeline.

Edit it in:
- `index.html` under `<div id="about" class="basic-1 bg-gray">`

Replace:
- `add start - add end`
- `New Role Title`
- placeholder summary text

## About Intro Update

Updated the About introduction text in `index.html` to reflect:
- 3+ years of software development experience
- production-grade delivery
- platform infrastructure and CI/CD focus

## Header Refresh Update

The homepage header was redesigned for a more professional and compact layout.

What changed:
- Reduced excessive top/bottom hero spacing across breakpoints
- Replaced generic CTA with `View Projects`
- Added a professional kicker, stronger headline, and supporting subtitle
- Added highlight chips for expertise areas
- Added a right-side profile card with impact-focused metrics
- Removed inline style usage from the hero title and avatar

Main files:
- `index.html` (header structure/content)
- `css/styles.css` (header and responsive styling)

## Color Palette Update

Applied a professional color polish while preserving the existing visual identity.

What changed:
- Introduced color tokens in `:root` for maintainable palette control
- Upgraded primary accent to modern blue (`#2563eb`) with darker hover (`#1d4ed8`)
- Updated CTA, icon, timeline, and utility accent usages to token-based colors
- Replaced flat hero background with a premium dark gradient (`#0f172a` to `#1f2937`)
- Improved hero text contrast with tuned kicker and muted subtitle colors

Main file:
- `css/styles.css`

## About Section Redesign

Redesigned the About area for clearer storytelling and professional scanability.

What changed:
- Added section heading `About & Experience`
- Replaced the 3-column split with:
  - left intro card (summary + focus areas)
  - right single-column chronological timeline
- Standardized all date formats (`Mon YYYY - Mon YYYY` and `Present`)
- Rewrote experience summaries with stronger impact-oriented phrasing
- Added timeline card visuals with accent line and milestones
- Improved responsive behavior for desktop and mobile readability

Main files:
- `index.html` (About section structure and content)
- `css/styles.css` (About timeline and card styling)

## Services Section Redesign

Rebuilt the Services section for a stronger professional positioning and higher visual impact.

What changed:
- Updated title and supporting copy to focus on production engineering outcomes
- Replaced generic services with four high-value offerings:
  - Platform & CI/CD Engineering
  - Cloud Infrastructure & Reliability
  - Backend & API Engineering
  - Technical Delivery Leadership
- Added service tags for quick capability scanning
- Added a trust metrics row to reinforce expertise and delivery standards
- Introduced premium section styling:
  - subtle gradient background
  - elevated service cards
  - icon badges
  - hover lift and accent states
  - staggered reveal animation
- Improved responsive spacing and card layout behavior

Main files:
- `index.html` (Services structure and content)
- `css/styles.css` (Services visuals, interactions, and responsiveness)

## About Timeline Enhancement

Enhanced the About section to include freelance experience and eliminate the large empty space on the left panel.

What changed:
- Added new timeline entry:
  - `Oct 2022 - May 2023`
  - `Full-stack Developer`
  - `Freelance - Hybrid`
  - Included project bullets for:
    - Carpooling Platform
    - Logistics Management System
    - Recipe Sharing Platform
- Upgraded the left column into a two-card experience panel:
  - professional introduction card
  - impact snapshot card with stats and capability chips
- Added sticky behavior on desktop for the left panel, so the section feels intentional while scrolling the timeline
- Added dedicated styling for timeline context labels and project bullets

Main files:
- `index.html` (new freelance timeline content + left panel structure)
- `css/styles.css` (About side-panel enhancements and timeline detail styles)

## Details Section Upgrade

Upgraded the `Why Work With Me` split section with more professional messaging and a cleaner visual hierarchy.

What changed:
- Rewrote content with a stronger executive narrative focused on:
  - production-first architecture
  - reliable delivery systems
  - engineering partnership
- Replaced long generic paragraphs with compact feature cards for faster scanning
- Added a professional technology chip row for core stack visibility
- Improved visual styling with:
  - refined image overlay
  - premium right-panel gradient
  - card-based content blocks
  - stronger typography hierarchy
- Tuned desktop sizing for better readability in the split layout

Main files:
- `index.html` (Details section content/structure)
- `css/styles.css` (Details section styling and responsive sizing)


## Details Responsive Fix

Resolved the overflow/cutoff issue in the split Details section on large screens.

What changed:
- Removed all rigid desktop height constraints that caused dead space and clipping
- Refactored desktop layout to a grid-based split with equal adaptive columns
- Overrode the left visual panel fixed height on desktop so it stretches with the section
- Kept mobile behavior stacked with a fixed hero image block for consistent appearance
- Added fluid width safeguards for the right text container to prevent clipping

Main file:
- `css/styles.css`

## Skills Container Upgrade

Refined the Skills section to look more professional and better highlight platform tooling.

What changed:
- Added section heading and supporting description for context
- Improved logo rail styling with:
  - compact icon cards
  - cleaner spacing
  - hover elevation
  - independent marquee animation (`skillsScroll`)
- Added requested platform tools directly into the moving marquee rail (not static):
  - Kubernetes
  - Terraform
  - Terragrunt
  - Next.js
  - K9s
  - Argo CD
  - GitHub Actions
- Styled moving tool badges to match logo card height, spacing, and hover behavior
- Corrected logo `alt` text labels for better accessibility

Main files:
- `index.html` (skills content and moving tool badges)
- `css/styles.css` (skills layout and moving badge visuals)

## Projects Section Redesign

Redesigned the Projects section to be more attractive, professional, and easier to scan.

What changed:
- Replaced the old linear project list with a modern showcase structure:
  - featured project block for strongest case study
  - responsive card grid for additional projects
- Upgraded project copy to focus on delivery outcomes, reliability, and production context
- Added structured project metadata:
  - project type labels
  - capability/technology chips
  - clear per-project call-to-action links
- Improved visual hierarchy and interaction design with:
  - elevated cards
  - refined borders and shadows
  - hover media zoom
  - consistent spacing and typography
- Added responsive breakpoints for tablet/desktop so layout scales cleanly:
  - single-column mobile
  - 2-column project grid on wider screens
  - split featured layout on large screens

Main files:
- `index.html` (new projects section structure and professional content)
- `css/styles.css` (projects visuals, layout, and responsive behavior)

## Project Detail Pages Redesign

Redesigned every project detail page to match the upgraded portfolio style and improve readability, consistency, and responsiveness.

What changed:
- Rebuilt project detail pages into a consistent case-study format:
  - premium header with project context and tags
  - structured content cards (overview, capabilities, architecture, challenges, contributions)
  - responsive right-side snapshot panel on desktop
  - gallery sections with improved image layout for web and mobile projects
- Rewrote page copy with clearer professional language focused on delivery value and engineering decisions
- Removed old encoding artifacts and normalized copyright text formatting
- Added reusable project-case design system in `styles.css` with dedicated responsive breakpoints

Updated project pages:
- `BuilLab.html`
- `Transportyni.html`
- `carpooling.html`
- `Tawasalna.html`
- `WebMedical.html`

Main files:
- `css/styles.css` (new reusable project-case components and breakpoints)
- `BuilLab.html` (new case-study structure/content)
- `Transportyni.html` (new case-study structure/content)
- `carpooling.html` (new case-study structure/content)
- `Tawasalna.html` (new case-study structure/content)
- `WebMedical.html` (new case-study structure/content)

## Header and Footer Professionalization

Refined header/navigation and footer contact strategy to present a more professional software-engineering profile.

What changed:
- Removed Facebook and Instagram links from navbar and footer across homepage and project detail pages
- Added professional navbar contact actions:
  - `Download CV` button
  - email quick action
  - LinkedIn quick action
  - GitHub quick action (placeholder URL to update)
- Replaced old icon-only footer with a structured professional footer:
  - personal positioning summary
  - quick navigation links
  - dedicated professional contact panel (email, LinkedIn, GitHub, location)
  - clean contact icons (email + LinkedIn + GitHub)
- Added responsive styling for the new footer grid (mobile, tablet, desktop)
- Updated contact paragraph in `index.html` to use proper `mailto:` link and secure LinkedIn target attributes
- Added dedicated CV folder and path convention:
  - `assets/cv/Hamza-Ben-Ayed-CV.pdf`
  - helper file: `assets/cv/PUT-CV-HERE.txt`

Updated pages:
- `index.html`
- `BuilLab.html`
- `Transportyni.html`
- `carpooling.html`
- `Tawasalna.html`
- `WebMedical.html`

Main file:
- `css/styles.css` (navbar contact actions + new professional footer styles)

## Email Action Fix + FAQ/Contact Redesign

Addressed non-working email interactions and upgraded the sections below projects for stronger professionalism and usability.

What changed:
- Replaced `mailto:` primary actions with browser-safe Gmail compose links in:
  - navbar email quick action
  - footer `Start a Conversation` button
  - footer email links/icons
  - contact section action buttons
- Fixed FAQ behavior by removing duplicate collapse IDs and rebuilding with unique IDs
- Rewrote FAQ content to be clearer and more professional
- Redesigned FAQ visuals with modern cards, cleaner spacing, and better hierarchy
- Rebuilt contact section as a professional contact hub:
  - email, LinkedIn, GitHub, availability cards
  - right-side quick action panel
  - direct CV download action
- Added responsive styles for the new FAQ and contact layouts

Notes:
- Active CV download path used across the site:
  - `assets/cv/Resume_Ben_Ayed_Hamza.pdf`

Main files:
- `index.html` (FAQ + contact structure/content + email action updates)
- `css/styles.css` (FAQ/contact redesign and responsive behavior)
- `BuilLab.html`, `Transportyni.html`, `carpooling.html`, `Tawasalna.html`, `WebMedical.html` (email action link updates)

## Contact Link UX Tweak

Improved contact card link readability by replacing raw profile URLs with clean profile names.

What changed:
- LinkedIn card link text changed from full URL to `Hamza Ben Ayed`
- GitHub card link text changed from full URL to `hamzabenayed`
- Kept original destinations unchanged

Main file:
- `index.html` (contact card link labels)

## Outcomes and Process Sections

Added two new strategic sections to strengthen professional positioning and delivery credibility.

What changed:
- Added a new `Project Outcomes` section:
  - delivery impact framing
  - measurable snapshot cards
  - reliability and CI/CD value emphasis
- Added a new `How I Work` section:
  - 5-step workflow from discovery to release support
  - clear execution model for clients and teams
- Added dedicated responsive styling for both sections to ensure clean behavior on mobile, tablet, and desktop

Main files:
- `index.html` (new outcomes and process section structure/content)
- `css/styles.css` (section visuals and responsive grid rules)

## About Section UI/UX Balance

Improved the `About & Experience` section to avoid the previous imbalance where the right timeline was long and the left column ended too early.

What changed:
- Added a concise section eyebrow and supporting summary for clearer hierarchy
- Expanded the left rail into a complete career profile:
  - professional intro
  - impact snapshot
  - delivery ownership card
  - platform mindset card
  - current focus card
  - delivery toolkit card
- Improved timeline cards with role categories and skill tags for faster scanning
- Refined spacing, card styling, hover states, and section background
- Added responsive behavior so the layout stays coherent on mobile, tablet, and desktop
- Fixed the freelance context text encoding issue by replacing the broken separator with `Freelance / Hybrid`

Main files:
- `index.html` (about section content and timeline structure)
- `css/styles.css` (about section styling and responsive rules)

## WordPress Project Additions

Added two recent WordPress website projects to the `Projects Built For Production` section.

What changed:
- Added `SOBYFA Conseil` as a WordPress website redesign project
- Added `Elevational` as a WordPress brand website project
- Positioned both projects near the top of the project grid as recent work
- Added live website links with secure external-link attributes
- Updated the project section intro to include WordPress website delivery
- Used WordPress mShots live screenshot thumbnails for project media:
  - `https://sobyfaconseil.com/`
  - `https://elevational.co.uk/`

Notes:
- Local Chrome/PowerShell network access was blocked in this environment, so static screenshot files could not be captured directly from the shell.
- The portfolio cards use live screenshot URLs instead of committing error-page screenshots.

Main file:
- `index.html` (new WordPress project cards and project intro update)

## Process Section Redesign

Redesigned the `How I Work From Scope to Production` section for a more compact and modern UX.

What changed:
- Replaced long paragraph-heavy cards with shorter step summaries
- Added action labels for each phase:
  - Clarify
  - Design
  - Build
  - Validate
  - Operate
- Converted the layout into a compact stepper-style flow with hover feedback
- Reduced card height, padding, and text density for better scanning
- Added responsive behavior for desktop, tablet, and narrow mobile screens

Main files:
- `index.html` (process section content structure)
- `css/styles.css` (process stepper layout and responsive behavior)

## Quick Actions Button Contrast Fix

Fixed unreadable outline buttons in the contact section `Quick Actions` card.

What changed:
- Added contact-card-specific styles for `Download CV` and `Open LinkedIn`
- Improved contrast on the dark card background
- Added readable hover and focus states
- Kept the primary `Email Me` button visually dominant

Main file:
- `css/styles.css` (contact quick action button states)

## Contact Method Card Redesign

Redesigned the contact method cards beside `Quick Actions` for a more modern and premium contact experience.

What changed:
- Added icon-led card headers for Email, LinkedIn, GitHub, and Availability
- Added contextual badges such as `Best first step`, `Career`, `Code`, and `Open`
- Improved card hierarchy with shorter supporting copy
- Added subtle accent bars, decorative depth, hover movement, and link arrow feedback
- Added safer wrapping for long email text on smaller screens
- Preserved all existing contact destinations

Main files:
- `index.html` (contact method card structure)
- `css/styles.css` (premium card styling and interaction states)

## Footer Premium Redesign

Redesigned the footer to match the upgraded contact section and present a more polished professional close.

What changed:
- Added an availability/status badge in the brand area
- Rewrote the footer positioning text for software, platform, and WordPress delivery
- Added primary and secondary footer CTAs:
  - `Start a Conversation`
  - `Download CV`
- Added professional value chips for platform engineering, CI/CD, WordPress, and production systems
- Rebuilt quick links with icons and hover movement
- Rebuilt direct contact rows with icons, cleaner labels, and readable profile names
- Added a footer bottom line with a selected-work link
- Updated copyright text to include 2026 and a valid homepage link

Main files:
- `index.html` (footer structure and copy)
- `css/styles.css` (footer layout, cards, interactions, and responsive behavior)

## Footer Balance Refinement

Refined the premium footer after visual review to make the columns feel more coherent and less uneven.

What changed:
- Added a `Recommended path` card inside the Explore panel
- Changed footer cards to stretch to equal height at desktop widths
- Bottom-aligned the social icons inside the direct contact panel
- Removed the desktop rule that forced footer panels to align only at the top

Main files:
- `index.html` (Explore panel supporting content)
- `css/styles.css` (equal-height footer panel behavior)

## Mobile Responsiveness Pass

Reviewed the homepage at mobile widths and tightened responsive behavior for the most recent layout changes.

What changed:
- Added a global horizontal overflow guard to prevent sideways scrolling on mobile
- Added small-screen hero rules for:
  - headline wrapping
  - stacked CTA buttons
  - stacked hero chips
  - constrained profile card width
- Added small-screen footer rules so footer CTAs stack full-width on phones
- Verified mobile behavior for:
  - hero
  - about
  - services
  - projects
  - process
  - contact
  - footer

Main file:
- `css/styles.css` (mobile overflow guard and small-screen refinements)

## Navbar Scroll Contrast Fix

Fixed a desktop navbar contrast issue where the header could appear transparent with low-contrast links after navigating to lower sections.

What changed:
- Updated the navbar scroll detection script to use `window.scrollTop()` instead of fixed-element offset
- Made the desktop fixed navbar use a consistent dark background instead of relying on a fragile transparent state
- Reinforced scrolled navbar text, active, hover, shadow, and backdrop styling
- Verified the navbar over the `About` section with a local browser screenshot

Main files:
- `js/scripts.js` (navbar scroll class detection)
- `css/styles.css` (desktop navbar contrast and scrolled state)
