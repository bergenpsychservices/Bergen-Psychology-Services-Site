# Bergen Psychology Services

Static website for Dr. Alan Sheinfil, PhD. The revision introduces a concise homepage, dedicated therapy and approach pages, clear fees and consultation information, and a shared responsive design.

## Review status

The revision is on `draft/full-site-refinement` for review. It has not been merged or deployed. `main`, `CNAME`, and the existing hosting configuration are unchanged.

## Preview locally

From the repository directory:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. There is no build step or package installation. The consultation form uses the existing live StaticForms endpoint; do not submit test messages unless you intend to send them to the practice. The separately supplied review preview disables submissions.

## Pages and assets

- `index.html`: homepage
- `about.html`: professional background
- `services.html`: adult therapy overview
- `trauma-therapy.html`, `anxiety-mood-therapy.html`, `substance-use-therapy.html`: focused service information
- `approach.html`: collaborative CBT/ACT-informed treatment
- `faq.html`: practical details, fees, insurance, and appointments
- `get-started.html`: consultation request and contact details
- `privacy.html`, `good-faith-estimate.html`: website privacy and estimate rights
- `assets/site.css`, `assets/site.js`: shared styling and navigation enhancements
- `assets/fonts/`: self-hosted Fraunces and Source Sans 3, with licenses
- `sitemap.xml`, `robots.txt`: search discovery

Pages are plain HTML. Shared navigation, footer, metadata, and contact details must be kept consistent when editing. Original portrait, favicon, and logo source remain in `Images/`; the recolored logo is in `assets/`.

See [revision notes](docs/REVISION-NOTES.md) for scope, verification, and launch considerations.
