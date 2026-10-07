# SETU Novus Email Signature Generator

A simple web-based tool for SETU Novus staff to generate a consistent, approved email signature for use in Microsoft Outlook.

## What the tool does

Staff enter their own details:

- English name
- Irish name, optional
- Qualifications, optional
- Job title
- SETU email address

The generator then creates a formatted SETU Novus email signature using the approved logo, website, address details, colours and layout.

Staff can copy the completed signature directly into Outlook.

## How to use

1. Open the SETU Novus Email Signature Generator.
2. Enter your details.
3. Check the signature preview.
4. Click **Copy signature**.
5. Open Outlook.
6. Go to **Settings → Accounts → Signatures**.
7. Create a new signature.
8. Paste the copied signature into the signature editor.
9. Set it as the default signature if required.
10. Save your changes.

## Notes

- Irish name is optional.
- Qualifications are optional.
- The email address should use the `@setu.ie` domain.
- Branding, logo, website and layout are fixed to help maintain consistency.
- Personal details are processed in the browser and are not submitted to a database.

## Repository structure

```text
novus-email-signature-generator/
├── index.html
├── LICENSE
├── README.md
└── setu-novus-logo.png