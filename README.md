# KICKS ROOM

Sneaker and streetwear content media.

## Publishing to GitHub Pages

1. Create a new repository on GitHub (e.g. `kicks-room`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Set branch to `main`, folder to `/ (root)`
6. Click **Save**

Your site will be live at:

```
https://<your-username>.github.io/kicks-room/
```

## URL Reference (for API applications)

| Purpose | URL |
|---|---|
| Website | `https://<your-username>.github.io/kicks-room/` |
| Terms of Service | `https://<your-username>.github.io/kicks-room/terms.html` |
| Privacy Policy | `https://<your-username>.github.io/kicks-room/privacy.html` |
| Contact | `https://<your-username>.github.io/kicks-room/contact.html` |

Use the Terms and Privacy URLs when applying for TikTok Developer API or other platform API access.

## Files

```
index.html      — Home page
terms.html      — Terms of Service
privacy.html    — Privacy Policy
contact.html    — Contact
style.css       — Styles (shared across all pages)
```

## Security Notes

- Never upload client secrets or API keys to this repository.
- Use environment variables for sensitive credentials.
- Do not commit `.env` files or any file containing tokens or passwords.
