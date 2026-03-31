# Responsive Email Campaign Boilerplate
A responsive HTML email foundation built for marketing campaign workflows.

This project demonstrates a modular, table-based email template coded from scratch for cross-client reliability. It includes a 600px container layout, a reusable single-column structure, a stackable two-column content module, Outlook-safe CTA patterns, responsive behavior for smaller screens, and placeholder tracking conventions for campaign links.

The template is organized for a practical email workflow:
- `src/email-template.html` contains the editable source version
- `dist/index.html` contains the generated inlined version for testing or send preparation

## Features
- 600px responsive email container
- Single-column campaign base
- Stackable two-column content module
- Bulletproof CTA button with Outlook VML fallback
- Mobile-responsive layout adjustments
- Hidden preheader support
- Footer with preference and unsubscribe placeholders
- UTM-ready campaign links
- Local source and inlined output workflow
- Dark mode enhancement styles for supporting clients
- Tested across major email clients including Gmail, Outlook, and Apple Mail

## Project Structure
```text
email-boilerplate/
    package.json
    src/
        email-template.html
        assets/
            logo.svg
            1200x600.svg
            536x300.svg
    dist/
        index.html
        asssets/
            logo.svg
            1200x600.svg
            536x300.svg
    README.md
```

## Live Preview
Demo the template here: https://email-boilerplate.netlify.app/

## Screenshots
### Mobile dark mode preview
<img width="207" height="448" alt="Mobile dark mode preview i" src="https://github.com/user-attachments/assets/315f8da0-97b7-460b-b499-78a5ca5e5b12" />
<img width="207" height="448" alt="Modbile dark mode preview 2" src="https://github.com/user-attachments/assets/59221944-b4b6-49a5-b90a-a261c9452d81" />



