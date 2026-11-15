# MOR — Mortis Imperium Alliance Hub

A static GitHub Pages website. The home page is built as real HTML/CSS (not a poster image), with the MOR Alliance Playbook content and a top navigation menu.

## Publish with GitHub Pages
1. Create or open your public repository.
2. Upload the contents of this folder to the repository root (the `index.html` file must be at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Navigation
- **HOME** jumps to the playbook home page.
- **USEFUL INFORMATION** opens a hover dropdown on desktop and a click dropdown on mobile.
- External links open in a new tab.

## Language selector
The navigation includes English, German, French, Spanish, Portuguese, Korean, Japanese, Chinese (Simplified), and Russian. Page translation is provided automatically by Google Translate. Visitors' language choice is saved in their browser. Machine translation can occasionally mistranslate game-specific terminology or alliance names.

## Header and link behaviour
The supplied MOR Alliance Playbook banner is displayed full-width at the top of the home page. Resource links open in the same browser tab.

## Embedded resource layout
The page layout is **Header → Menu → Body → Footer**. Selecting a Useful Information card loads its URL into the body iframe, with a Back to Home control. Some third-party sites may block iframe embedding through their security policy; for those sites, a direct same-tab fallback link is shown.

The Useful Information cards load their selected site inside the page body using an iframe. Some third-party providers may block iframe embedding; in that case use the direct link displayed below the frame.
