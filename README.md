# ZIP Email Signature Generator

A simple web tool for creating consistent email signatures across Zero Invasive Predators (ZIP). This is hosted on GitHub pages, and should be quick and easy to use. Image links are stable, and shouldn't change in the future.

**Live tool:** https://zero-invasive-predators.github.io/zip-email-signature-generator/

## Why is it on GitHub Pages?

Gmail and other email clients cache signature images on their CDN. They need to fetch images from a permanent, reliable URL. GitHub Pages provides:

- **Permanent URLs** that won't change or break
- **Free, reliable hosting** with no maintenance required

If this page moves or URLs change, everyone will need to regenerate their signatures.

## Creating Your Signature

1. Visit the [signature generator](https://zero-invasive-predators.github.io/zip-email-signature-generator/)
2. Select the organisation you most closely represent from the dropdown
3. Fill in all the details you'd like to include (name, job title, email, phone, te reo Māori job title)
4. Click "Copy signature"
5. Paste into Gmail's signature settings

Your form data is saved locally in your browser, so you can return to make updates.

## File structure

```
├── index.html      # Main page
├── style.css       # Interface styling
├── main.js         # Signature generation logic
├── images/         # Logo files (served via GitHub Pages)
└── README.md       # This file
```
## Development

1. Clone the repository
2. Open `index.html` in a browser
3. Make changes and refresh to test
4. Push to `main` branch — GitHub Pages deploys automatically

## License

All rights reserved. This is an internal tool for Zero Invasive Predators Aotearoa.
