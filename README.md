# Gorgyon Receipt System

A static A4 receipt editor for GitHub Pages.

## Features
- Editable receipt fields
- Live service and payment calculations
- A4 receipt layout
- Download PDF button
- Print Receipt button
- PDF contains the receipt only, without the editing toolbar
- No server/database required

## GitHub Pages deployment
1. Create a new GitHub repository, e.g. `gorgyon-receipt`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. GitHub will provide the Pages URL.

## Important
The PDF library is loaded from cdnjs, so the browser needs internet access when generating the PDF.
