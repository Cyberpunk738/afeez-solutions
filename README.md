# Afeez Solutions

A business-facing website for Afeez Ademola Sule, prepared for `solutions.afeezdev.tech`.

## Source

- `dist/index.html`: page content and project data
- `dist/style.css`: responsive design
- `dist/script.js`: project filters, project notes, mobile navigation, email draft form
- `dist/assets/`: custom SVG identity, project screenshots, and supplied-site logos

No build step or runtime dependencies are required. Serve the `dist` directory with any static web host. For local development, run `python -m http.server 8080 --directory dist` and visit `http://localhost:8080`.

## Contact form

The form prepares a `mailto:` draft; it does not send email or store submissions. The visitor must review and send the email in their email application. The current contact is `info@afeezdev.tech`. A server-side form endpoint can be added separately.

## Project attribution

The five project URLs were supplied by the portfolio owner. Screenshots show their public homepages as reviewed on 4 November 2026. Project notes intentionally distinguish live organisation websites, website showcases, and the Greenly recreation. No client revenue, conversion, donation, or traffic results are claimed. Confirm commissioning and delivery scope before changing those labels. The underlying project sites and their imagery retain their respective ownership.

## Hosting

The Sites hosting configuration is maintained separately from the portable GitHub source. For another host, publish `dist/` as the output folder. The included `vercel.json` supports static deployment on Vercel. Setting a custom domain requires DNS configuration at the domain's DNS provider; DNS setup does not create an email mailbox.

## GitHub

GitHub repository: https://github.com/Cyberpunk738/afeez-solutions

The production preview is hosted through Sites. GitHub stores the portable website source; changes pushed to GitHub do not automatically update the Sites preview.
