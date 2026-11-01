# personal-website

Static personal site (Home, Experience, Approach, Contact, plus a form confirmation page).
All content here is public-safe: it is published as-is. Do not add personal contact details.

Plain HTML and one stylesheet (`css/style.css`). No framework, scripts, trackers, analytics or third-party fonts.
Original layout; no template or outside source used.

## Contact form
- `contact.html` posts to Web3Forms. The access key in the form is a public identifier, not a secret.
- After sending, the form redirects to `https://odd-brew.github.io/personal-website/thanks.html`. If the site address changes (for example a custom domain), update the `redirect` value in `contact.html`.
