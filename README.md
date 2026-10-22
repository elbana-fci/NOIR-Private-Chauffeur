# NOIR — Private Chauffeur
Plain HTML, CSS and JavaScript; no build step or framework. Serve `dist/` with any static web server.

## Files
- `dist/index.html`: semantic page sections and booking dialog
- `dist/styles.css`: responsive layout, design tokens, reduced motion
- `dist/app.js`: service tabs, conditional inputs, capacity checks, itinerary review and download
- `dist/assets/`: vehicle photography from Unsplash

## What works
Four service types, mobile navigation, future date validation, vehicle capacity selection, contact validation, review, and a downloadable demo itinerary. No details are sent or stored persistently. No payment or live availability is implemented.

## Complete the service later
1. Replace the concept branding, fleet, images, location details and policies with verified business information.
2. Add a backend booking API and perform server-side validation, timezone handling, availability checks and pricing there.
3. Integrate address autocomplete, flight tracking and distance calculation with your chosen providers. Keep secret API keys on the server.
4. Replace the final demo handler with an authenticated request to your booking API. Only show confirmed status after an authoritative backend response.
5. Add payments, transactional email, dispatch/admin workflows and corporate billing as needed.

The site intentionally avoids fabricated testimonials, pricing and contact information. Vehicle classes are illustrative.
