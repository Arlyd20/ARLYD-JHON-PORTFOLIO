# Arlyd Jhon Condistable Portfolio

A responsive static portfolio built with semantic HTML, CSS, and vanilla JavaScript. No build step or package installation is required.

## Run locally

Open `index.html` in a browser. Google Fonts are loaded remotely; the page falls back to local sans-serif fonts if they are unavailable.

## Replace the placeholders

Search the project for `ADD `, `[ADD`, `your-username`, and `your-profile` to find content that needs your real information.

- **Profile photo:** replace the framed placeholder in the hero. Put your portrait in `images/profile/` and update the `.photo-placeholder` in `index.html` to use an `<img>` with descriptive `alt` text. Update the Open Graph image metadata to point to the portrait or a social-sharing image.
- **Projects:** edit the four `.project-card` elements in `index.html`. Change each `data-category` to `web`, `design`, `devops`, or `support`, update the title, summary, badges, and real links, and replace its `.project-art` placeholder with a project image using useful `alt` text. Keep `data-category` aligned with the filter buttons.
- **Experience:** edit the four `.timeline-item` elements in `index.html`. Replace the bracketed title, organization, date, and description with verifiable details, or remove entries that do not apply. The HTML comments mark the appropriate experience categories.
- **Education and certifications:** replace `[ADD UNIVERSITY]`, `[ADD YEAR]`, and the certification placeholders in `index.html`. Remove certification examples that you do not hold.
- **Contact and social links:** replace `[ADD EMAIL]`, `mailto:[ADD-EMAIL]`, and the sample GitHub, LinkedIn, and Facebook profile URLs in `index.html`. Update the footer links as well.
- **Location:** replace `[ADD LOCATION]` in the quick facts area or remove that fact.
- **Contact form:** the form is frontend-only and does not send or store submissions. Connect a form provider or your own backend where the form submit handler is marked in `js/script.js` and update the visible demo notice in `index.html`.
- **Branding:** update the page title, description, Open Graph metadata, and favicon in `index.html` if your public-facing details change.

## Structure

```text
index.html
css/style.css
js/script.js
images/favicon.svg
images/profile/profile-placeholder.svg
```

The project thumbnails are CSS illustrations so no stock photos or fabricated client work are used. Replace them with real project imagery when your work is ready to publish.