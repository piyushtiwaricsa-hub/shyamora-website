# SHYAMORA Seller Solutions — GitHub Pages

This repository is a static HTML website for SHYAMORA Seller Solutions, an India-focused e-commerce operations support company. GitHub Pages deployment remains static; no build step, package installation, paid API, or external JavaScript library is required.

## Publish

1. In GitHub, open **Settings → Pages** and keep the existing publishing source. If configuring it for the first time, select the desired branch and repository root (`/(root)`).
2. Keep `index.html`, `privacy.html`, `terms.html`, `kyc.html`, `thank-you.html`, and `shyamora-logo.png` in the published root. Existing page routes and the original logo asset are retained.
3. Commit changes to the branch/folder configured in Pages. GitHub Pages will publish the static files; allow a few minutes for deployment.
4. Check **Actions** or **Settings → Pages** for deployment status, then verify the homepage, navigation, legal pages, KYC page, and logo at the Pages URL.

## Enquiry form setup

The contact form submits directly from the browser to FormSubmit (`https://formsubmit.co/shyamorasellersolutions@gmail.com`), without a server-side application. Form delivery is an external service and requires activation:

1. Publish the site and submit a test enquiry using an address you control.
2. FormSubmit will send an activation email to `shyamorasellersolutions@gmail.com`. Open that message and activate the endpoint. Submissions will not be delivered until activation is complete.
3. Submit another test and verify receipt and the redirect to `thank-you.html`. Check spam folders as needed.
4. Review FormSubmit's current privacy, retention, spam-protection, and availability terms before using it. The form includes a honeypot field and should not be used to collect passwords or sensitive personal data.

If FormSubmit is not suitable, configure a form provider or serverless endpoint you control, update the form action and redirect, and revise the privacy notice accordingly. No form backend credentials are stored in this repository.

## Before launch

- Confirm that the published INR starting prices (₹7,999, ₹14,999 and ₹24,999 per month), enterprise scope, service details, working hours, and any final quotations are commercially accurate. Plans are starting prices, not unlimited commitments; applicable taxes are extra.
- Confirm that `shyamorasellersolutions@gmail.com` and WhatsApp `+91 9302373454` are current.
- Shopify, Amazon, Flipkart, Meesho, Delhivery and Shiprocket are mentioned as examples of platforms/ecosystems only; the site does not claim official partnerships or integrations.
- Review the privacy and terms notices for the jurisdictions and data practices that apply to your business; they are general website notices, not legal advice.
- Test the enquiry endpoint after activating it. Until FormSubmit activation is complete, the form cannot deliver enquiries.

The site uses inline CSS/JavaScript, a system-font stack, the existing logo, and native browser form validation. No build step is needed.
