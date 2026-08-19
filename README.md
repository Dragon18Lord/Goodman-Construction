# Goodman Construction Website

A responsive, single-page residential general contracting website built for GitHub Pages. It includes service sections, a filterable project portfolio, image lightbox, mobile navigation, project process, and a project-summary estimate form.

## Company information included

- **Company:** Goodman Construction
- **Office:** 281-907-2808
- **Address:** 5211 Spanish Pak Dr, Houston, TX 77066
- **Service area:** Greater Houston Area

No email address was supplied, so the website does not publish a placeholder email. The estimate form formats and copies the visitor's project details, then directs them to call the office. A direct-submission service can be added later when a company email or form endpoint is available.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this package to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. GitHub will provide the public website URL after deployment completes.

## Project structure

```text
index.html
styles.css
script.js
.nojekyll
assets/
  favicon.svg
  images/
```

## Editing the portfolio

Gallery cards are in the `#gallery` section of `index.html`. Each card includes:

- `data-category` for filtering
- `data-title` for the lightbox caption
- `data-image` for the full image
- an `<img>` source and accessible alt text

Available categories are `kitchen-bath`, `remodeling`, `outdoor`, and `exterior`.

## Image notes

The supplied HEIC/JPG project photos were converted to web-optimized WebP files. Original uploads were not modified.
