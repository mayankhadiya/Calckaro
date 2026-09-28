# CalcKaro Launch Checklist (Manual Steps)

> These items require external account access and cannot be completed from repository code alone.

## 1) Domain and indexing

- [ ] Confirm canonical domain strategy (currently `https://calckaroindia.netlify.app`).
- [ ] If switching to custom domain, update canonical tags, OG URLs, `robots.txt`, and `sitemap.xml`.
- [ ] Add and verify property in Google Search Console.
- [ ] Submit sitemap: `https://calckaroindia.netlify.app/sitemap.xml`.
- [ ] Use URL Inspection for homepage + each calculator route.

## 2) Netlify and route checks

- [ ] Confirm clean routes work: `/sip-calculator`, `/income-tax-calculator`, `/home-loan-emi-calculator`, `/about`, `/contact`, `/privacy-policy`, `/disclaimer`.
- [ ] Confirm `.html` URLs redirect via `_redirects`.
- [ ] Confirm `404.html` renders for unknown routes.

## 3) Optional analytics (not pre-enabled)

- [ ] Choose analytics provider and create property/account.
- [ ] Add provider script using placeholders in `analytics.example.html`.
- [ ] Update `privacy-policy.html` to reflect actual analytics usage.
- [ ] Configure consent banner/consent mode if legally required for your traffic regions.

## 4) Optional AdSense (not pre-enabled)

- [ ] Apply for AdSense and wait for approval.
- [ ] Replace ad placeholders with official AdSense snippets only after approval.
- [ ] Create a live `ads.txt` from `ads.txt.example` with real publisher ID.
- [ ] Verify `https://<your-domain>/ads.txt` is publicly reachable.
- [ ] Update privacy policy language once ads are actually active.

## 5) Content trust and maintenance

- [ ] Re-verify income-tax assumptions with official Income Tax Department/CBDT sources before each FY update.
- [ ] Re-verify lender-rate examples or keep them generic if not maintained.
- [ ] Update visible “Last reviewed” dates whenever assumptions change.
- [ ] Re-check JSON-LD snippets against visible content after edits.

## 6) Final quality checks

- [ ] Validate HTML pages render without JS errors in browser.
- [ ] Validate no fake ratings/reviews/credentials are introduced.
- [ ] Validate no secrets or credentials are committed.
