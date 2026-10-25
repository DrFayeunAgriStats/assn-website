# ASSN website

Website concept for the Association of Seed Scientists of Nigeria, including leadership, membership, conferences and links to the Nigerian Journal of Seed Science.

## Deploy to Vercel

Import `DrFayeunAgriStats/assn-website` into Vercel. Use the repository root, Framework Preset **Other**, build command `node scripts/build.mjs`, and output directory `dist`. No dependencies, database or secrets are required. The committed `vercel.json` configures the build and output directory.

The build uses Vercel's production project URL for social metadata. After connecting a custom domain, set the optional `SITE_URL` environment variable to its full HTTPS address and redeploy.

## Local build

Use Node.js 22 or newer:

```sh
node scripts/build.mjs
```

Serve `dist` using a static HTTP server. Navigation uses hash routes (`#home`, `#about`, `#membership`, `#journal`, `#events`, `#governance`, `#contact`).

## Edit the site

- `public/index.html`: page copy, styles and navigation.
- `public/assets/`: deployed photos, logo, journal artwork and draft membership application.
- `docs/ASSN_Website_Review_Memo.pdf`: executive decisions still required before launch; not included in the deployed site.

The concept review banner and explicit placeholders remain intentional. Fees, payment details, public contact details, presidential welcome text and proposed vision/mission wording require association approval. The next host is OAU; its date and theme are not fixed. The membership application is a draft downloadable form, not an online submission system. Journal operations remain on the existing NJSS portal.

The fellows photograph has an AI-edited background. The logo and journal cover artwork were adapted from supplied images. Verify final branding and photo approvals before public launch.

## Ownership and access

The GitHub repository is private. Vercel website visibility is controlled separately. Do not upload credentials, internal financial records or unapproved personal information.
