# Free hosting guide (static sites)

The template is plain HTML, so it can be hosted free. Check each provider's current free-plan terms before promising anything to clients.

## Recommended: Cloudflare Pages
1. Create a free account at cloudflare.com.
2. Workers & Pages > Create > Pages > Upload assets.
3. Name the project after the client (e.g. `sri-sai-tailors`), then drag the client's folder in and deploy.
4. You get a free `yourname.pages.dev` address.
5. To use a custom domain (e.g. `srisaitailors.in`), buy it from any registrar (about 600-800 rupees/year), then add it under Custom domains in the project.

## Alternatives
- **Netlify:** drag and drop the folder at app.netlify.com/drop.
- **GitHub Pages:** one repo per client, then Settings > Pages.

## Per-client workflow (about 1-2 hours)
1. Copy the `shop-template` folder and rename it to the client's name.
2. Replace the `{{TOKENS}}` listed at the top of `index.html` (Find & Replace).
3. Set `data-theme` to `shop`, `service` or `clinic`.
4. Add the client's photos in an `images/` folder.
5. Test on your phone, then upload to Cloudflare Pages.
6. Set up their Google Business Profile with the website link.
7. Send the link on WhatsApp and collect the second 50%.

## What to charge for
Hosting is free, but you charge for the work: updates, domain renewal, and support (the 500 rupee/month care plan).
