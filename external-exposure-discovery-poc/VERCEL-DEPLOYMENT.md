# Vercel deployment — synthetic POC page

## Current state

The static test page is located at this directory's `index.html`. It is synthetic-only and safe for public preview. It does not modify the production website or domain DNS.

## Import the existing GitHub repository

1. In Vercel, choose **Add New → Project**.
2. Import the existing repository: `vjsundar/AIscan`.
3. In project configuration, set **Root Directory** to `external-exposure-discovery-poc`.
4. Use the default static deployment settings; no build command or framework preset is required for this plain HTML page.
5. Deploy to the generated Vercel preview domain first.
6. Verify the page title and marker `HVX-POC-CAMPAIGN-7Q4M2` on the preview URL.

## Domain safety

- Do not add `harvexhub.com` as a Vercel domain during this POC setup.
- Do not change DNS records.
- Do not configure production aliases.
- Keep the preview URL and deployment limited to this synthetic test.
- Remove the preview deployment and synthetic page after the agreed test window.

## Repository note

This repository also contains documentation and test fixtures. Setting the Vercel root directory to this folder makes the static page the deployment root.
