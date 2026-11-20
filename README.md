# SHYAMORA website (GitHub Pages)

This repository is a static HTML website for SHYAMORA Seller Solutions. The published site remains compatible with GitHub Pages; no build step or package installation is required.

## Publish

1. In GitHub, open **Settings → Pages** and keep the existing publishing source. If configuring it for the first time, select the desired branch and the repository root (`/(root)`).
2. Keep `index.html` in the published root. The supporting pages (`privacy.html`, `terms.html`, `kyc.html`, and `thank-you.html`) and `shyamora-logo.png` must remain beside it.
3. Commit changes to the branch/folder configured in Pages. GitHub Pages will publish the static files; allow a few minutes for deployment.
4. Check **Actions** or **Settings → Pages** for the deployment status, then verify the website, navigation, legal pages, and logo at the existing Pages URL.

## Enquiry form setup

The contact form submits directly from the browser to FormSubmit (`https://formsubmit.co/shyamorasellersolutions@gmail.com`) so it works without a server-side application or GitHub Pages build. Before relying on it:

1. Publish the site and submit a test enquiry using an address you control.
2. FormSubmit will send an activation email to `shyamorasellersolutions@gmail.com`. Open that message and activate the endpoint. The form will not deliver submissions until this step is completed.
3. Submit another test and confirm receipt and the redirect to `thank-you.html`. Check spam folders as needed.
4. Review FormSubmit's current privacy, retention, spam-protection, and availability terms before using it for business enquiries. The form includes a honeypot field; do not collect sensitive information in a static public form.

If FormSubmit is not suitable, replace the form endpoint with a provider you control (for example, a configured hosted form service or a serverless function) and update the privacy notice accordingly. Never place API secrets in client-side HTML.

## Details to confirm before launch

- Confirm SHYAMORA's service scope, operational availability, and the USD pricing model before making commercial commitments. This site describes custom USD quotes rather than inventing fee amounts.
- Confirm the contact email and existing WhatsApp contact are current. Existing email and WhatsApp links are retained.
- Privacy and terms pages are general website notices, not legal advice. Have them reviewed for the jurisdictions and data practices that apply to your business.

The site uses inline CSS/JavaScript, a system-font stack, and the existing logo asset; it does not require external libraries or a bundler.
