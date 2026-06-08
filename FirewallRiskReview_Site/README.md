# Firewall Risk Review Landing Page

Static landing page for FirewallRiskReview.com.

## Deploy to Cloudflare Pages with GitHub

1. Create a new GitHub repository, for example `firewall-risk-review`.
2. Upload these files to the repository root.
3. In Cloudflare, go to **Workers & Pages**.
4. Create a new Pages project and connect the GitHub repo.
5. Use these settings:

- Framework preset: `None`
- Build command: leave blank or use `exit 0`
- Build output directory: `/`
- Production branch: `main`

## Custom domain

After deployment, add `FirewallRiskReview.com` under the Pages project **Custom domains** section.

## Form setup

The form currently uses a placeholder Formspree action:

```html
https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID
```

Replace it with your Formspree, Tally, Basin, Netlify Forms, or other form backend endpoint.
