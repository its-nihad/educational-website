# Eastberg Educational Institution — Website

A clean, modular multi-page static website built for **Eastberg Educational Institution** using standalone HTML, CSS, and vanilla JavaScript.

## Color Theme & Typography

- **Primary Burgundy:** `#8C2C3F` (headings, primary buttons, banners, and structural accents)[span_0](start_span)[span_0](end_span)
- **Golden Amber:** `#FCB433` (highlights, badges, borders, and hover accents)[span_1](start_span)[span_1](end_span)
- **Pure White:** `#FFFFFF` (main page canvas and card surfaces)[span_2](start_span)[span_2](end_span)
- **Headings & Brand:** `Montserrat` (loaded via Google Fonts)[span_3](start_span)[span_3](end_span)
- **Body & UI Text:** `Poppins` (loaded via Google Fonts)[span_4](start_span)[span_4](end_span)

## Project Structure

Each page is kept as a separate, self-contained HTML file:

- `index.html` — Main homepage introducing Eastberg, academic programs, highlights, and admissions call-to-action
- `about.html` — Institution overview, key statistics, mission & vision, and leadership council
- `course grid.html` — Filterable course catalogue (All Programs, Undergraduate, Postgraduate, Diploma)
- `blog_details.html` — Article view featuring campus stories, takeaways, and author details
- `gallery.html` — Filterable campus gallery covering labs, events, and workshops
- `contact us.html` — Campus contact information and an enquiry form with submission feedback
- `error.html` — Custom `404` page with quick navigation back to home or courses
- `maintenance.html` — Scheduled maintenance notice page with support contact details

## Getting Started

1. Place all `.html` files inside the same project folder so relative links (`index.html`, `about.html`, `course grid.html`, `blog_details.html`, `gallery.html`, `contact us.html`, `error.html`, `maintenance.html`) work seamlessly.
2. Open `index.html` (or any page) directly in a web browser, or serve the folder using a local development server such as VS Code Live Server.

## Customization Notes

- **Colors & Fonts:** Update the CSS custom properties (`--primary`, `--accent`, `--white`, `--surface`) and Google Fonts `<link>` in each page's `<head>` if you want to adjust styling globally[span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span).
- **Form & Filter Logic:** The enquiry form in `contact us.html` and category filters in `course grid.html` and `gallery.html` run client-side; connect the form handler to your preferred backend or form service when deploying live.