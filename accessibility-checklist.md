# Accessibility Checklist (CURATIONSLA)

## Landmarks
- <header>, <main>, <footer> used.
- Skip link present (#main-content).
- Search overlay uses role="dialog" + aria-modal="true" + labelled by heading.

## Focus
- Focus trap in search overlay.
- ESC closes search (keyboard support).
- Buttons use <button>; never divs.

## Color & Contrast
- Lime (#ebf998) on black passes contrast for UI labels (verify small text sizes > 12px).
- Avoid placing lime text on white for critical UI text.

## Semantics
- Comments wrapper: <section aria-label="Comments"> for context.
- Tables have <thead>, scope implicit; accessible for screen readers.

## Headings
- Post title h1, internal content headings h2/h3.

## Accessible Names
- Search open: aria-label="Search".
- Close button: aria-label="Close search".
- Back to top: aria-label="Back to top".

## Motion / Prefers Reduced
(Optional future) Add: @media (prefers-reduced-motion: reduce) { disable transforms/transitions }

## Links
- Underline is replaced by highlight background; color contrast OK.
- External sponsor link has rel="noopener".

## Forms
- Search input has aria-label.
- Placeholder descriptive.

## Other
- Ensure images have alt.
- Provide alt text for hero images if added later.

Done.