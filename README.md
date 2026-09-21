# DavidBastian.me Version 1

A dependency-free static website prepared for GitHub and Azure Static Web Apps.

## Before publishing

1. Open `assets/site.js` and verify `CONTACT_EMAIL`. It is currently `contact@davidbastian.me`.
2. Open `index.html` and review all public biographical and descriptive copy.
3. Replace the placeholder terms and privacy pages with counsel-reviewed language before enabling any production intake process.
4. Do not treat the Version 1 email workflow as a secure portal. It does not provide authentication, email verification, document upload, case management, database storage, malware scanning, audit evidence, or an administrator dashboard.

## GitHub upload

Create a new repository, choose **Add file > Upload files**, and upload the CONTENTS of this folder so `index.html` is at the repository root. Commit the files.

## Azure Static Web Apps

Create a Static Web App connected to the GitHub repository. Use these build settings:

- App location: `/`
- API location: leave blank
- Output location: leave blank

Azure will add a GitHub Actions workflow and publish the site.

## Custom domain

After the Azure site works at its generated address, add `davidbastian.me` under the Static Web App custom-domain settings. Azure will provide the DNS record needed at GoDaddy. Enter the exact record shown by Azure, then complete validation.

## Version 1 behavior

The engagement form validates required fields, creates a local reference number, and opens a pre-addressed email in the visitor's default email application. The site does not transmit or store the form independently.

## Future production portal

The handoff document describes a later system with verified identity, stored case records, versioned acceptance evidence, documents, private administration, security controls, and operational processes. Those capabilities require a backend and legal/security review and are intentionally not represented as complete in this Version 1 static site.
