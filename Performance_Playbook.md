# The Performance & Optimization Playbook

## Guiding Principle
A beautiful page that is slow is a broken page. A Google PageSpeed score of 90+ is the goal.

- **Image Optimization:** All images must be compressed before use. Use modern formats like `.webp` wherever possible.
- **Lazy Loading:** All images and iframes below the fold **must** use the `loading="lazy"` attribute. This is non-negotiable.
- **Font Loading:** Use `font-display: swap;` in `@font-face` rules to ensure text is visible immediately.