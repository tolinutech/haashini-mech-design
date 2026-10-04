# Haashini Mech Design Website — V2

This version uses the yellow + grey visual direction from page 1 of the company profile.

## Open the website
Double-click `index.html`, or open the folder in VS Code and use Live Server.

## EASIEST WAY TO REPLACE THE LOGO
1. Prepare the real logo as PNG, SVG, JPG or WebP.
2. If possible, save it as `logo.svg` and replace:
   `assets/logo.svg`
3. If the real file is PNG/JPG instead:
   - copy it into `assets/`
   - open `index.html`
   - find `assets/logo.svg`
   - replace both occurrences with e.g. `assets/logo.png`

There are 2 logo references: header and hero/footer.

## EASIEST WAY TO REPLACE PRODUCT IMAGES
Current placeholder files:
- assets/products/design-projects.svg
- assets/products/trolleys.svg
- assets/products/pallets.svg
- assets/products/fixtures.svg

Option A — easiest:
Convert/save the provided product images using those same filenames and overwrite the placeholder files.

Option B:
If images are JPG/PNG, copy them to `assets/products/`, then edit `index.html`.
Example:
  OLD: assets/products/trolleys.svg
  NEW: assets/products/material-trolley.jpg

## HOW TO CHANGE TEXT
Open `index.html` in VS Code.
Use Ctrl+F to search the exact text you see on the webpage.
Change only the words between HTML tags.

Example:
  <h3>Fixtures</h3>
can become:
  <h3>Assembly Fixtures</h3>

## HOW TO CHANGE COLOURS
Open `styles.css`.
At the top is this section:

:root {
  --yellow: #f7b844;
  --grey: #a7a7a7;
  --charcoal: #282828;
}

Change those values and the whole site updates.

## CONTACT FORM
The contact form is currently visual only.
Before launch we can connect it to:
- Email
- Formspree
- Web3Forms
- WhatsApp
- your own backend

## CONTACT DETAILS
Search `index.html` for:
- 63820 14169
- 93451 04697
- haashinidesign@gmail.com
- Chennai & Pudukkottai

## SAFE EDITING TIP
Before making changes:
1. Copy the complete folder.
2. Rename the copy, e.g. `haashini-backup`.
3. Edit the working copy.
This makes it easy to undo mistakes.
