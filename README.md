# Email Revenue Systems

Landing page for **Email Revenue Systems** — a Memphis-based email marketing agency that builds, manages, and optimizes The Email Revenue System™ for small businesses.

## Stack

- Single-file static HTML (`index.html`)
- Tailwind via CDN
- Fraunces (display serif), Inter (body), JetBrains Mono (labels) via Google Fonts
- Calendly inline widget for the multi-step lead form

## Local preview

Just open `index.html` in a browser. No build step.

## Deploy

Deployed to Vercel as a static site — no build configuration required.

## TODOs

- Replace the placeholder Calendly URL inside the inline `<script>` block (`CALENDLY_URL` constant) with the real booking link
- Wire steps 1 & 2 of the form to the actual lead capture backend (currently the form data is only passed forward to Calendly via prefill)
