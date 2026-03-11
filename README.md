# Verbora Landing Page

Premium static landing page for the Verbora mobile app.

## Stack

- HTML
- CSS
- Small vanilla JavaScript (scroll reveal only)

## Run Locally

You can open `index.html` directly in a browser, or run a local static server:

```bash
cd /Users/User/Desktop/verbora-site
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy To GitHub Pages

1. Create a new GitHub repository and push this folder.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` (or `master`) and `/ (root)`
4. Click `Save`.
5. Wait 1-3 minutes for deployment.
6. Open the published URL shown in the Pages settings.

## Project Structure

- `index.html`: Page markup and content sections
- `styles.css`: Visual system, layout, and animations

## Notes

- No framework or build step required.
- Ready for GitHub Pages as-is.
