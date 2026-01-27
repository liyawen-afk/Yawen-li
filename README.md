# Academic Website for Dr. Yawen Li

This folder contains a static website draft for an academic personal website.

## Folder Structure

```
website/
├── index.md          # Home / Bio page
├── research.md       # Research interests and projects
├── publications.md   # Selected publications
├── teaching.md       # Teaching experience and courses
├── grants.md         # Grants and funded projects
├── contact.md        # Contact information
├── styles.css        # Stylesheet
├── profile.jpg       # Profile photo (copy from parent folder)
└── README.md         # This file
```

## Deployment Options

### Option A: GitHub Pages (Recommended)

1. Create a GitHub repository named `username.github.io`
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Use a static site generator like Jekyll (built into GitHub Pages) to convert Markdown to HTML

**Quick Jekyll setup:**
- Add a `_config.yml` file with basic settings
- GitHub Pages will automatically build and serve the site

### Option B: Simple HTML Conversion

1. Convert each `.md` file to `.html` using a Markdown converter
2. Add the CSS link to each HTML file: `<link rel="stylesheet" href="styles.css">`
3. Upload to any web host (Netlify, Vercel, university server)

### Option C: Google Sites Adaptation

To adapt this content for Google Sites:

1. **Create a new Google Site**
2. **Add pages** matching the structure (Home, Research, Publications, Teaching, Grants, Contact)
3. **Copy content** from each Markdown file, removing Markdown formatting
4. **Upload profile photo** and insert on Home page
5. **Apply styling** using Google Sites' built-in themes (choose a clean, minimal academic theme)

**Google Sites formatting tips:**
- Use "Title" for h1, "Heading" for h2, "Subheading" for h3
- Use collapsible sections for long publication lists
- Use table feature for grants table
- Add navigation automatically via Pages panel

## Content Notes

- All content sourced from provided CV
- Profile photo should be copied to this folder and renamed `profile.jpg`
- Update email link format for your preferred contact method
- Add actual links to Google Scholar, ORCID, ResearchGate on contact page

## Customization

- **Colors:** Edit CSS variables in `:root` section of `styles.css`
- **Fonts:** Change font-family in `body` selector
- **Layout:** Adjust `--max-width` for wider/narrower content area

## To Do Before Publishing

- [ ] Copy profile photo to this folder
- [ ] Verify all information is current
- [ ] Add links to Google Scholar, ORCID, etc.
- [ ] Confirm email address is correct
- [ ] Add office location/room number if desired
