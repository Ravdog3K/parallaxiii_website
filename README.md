# Parallax III website

Static site for GitHub Pages: Home, About, and Contact.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Publish on GitHub Pages

1. Create a new GitHub repository (public for free Pages, or private with GitHub Pro).
2. Push this folder as the repo root (keep `index.html` at the root).
3. In the repo: **Settings → Pages → Build and deployment**.
4. Set **Source** to **Deploy from a branch**.
5. Choose branch `main` (or `master`) and folder `/ (root)`, then Save.
6. After a minute or two, the site will be at `https://<user>.github.io/<repo>/`.

Optional: for a custom domain, add a `CNAME` file containing your domain and configure DNS per GitHub’s docs.

## Notes

- Update the email on `contact.html` before going live.
- Logo assets live in `assets/` (from Stationary).
