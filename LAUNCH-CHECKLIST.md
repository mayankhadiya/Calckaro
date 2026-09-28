# Search, analytics and advertising launch checklist

## Google Search Console

- Add and verify the exact URL-prefix property `https://calckaroindia.netlify.app/`.
- Submit `https://calckaroindia.netlify.app/sitemap.xml`.
- Inspect `/`, `/sip-calculator`, `/income-tax-calculator`, and `/home-loan-emi-calculator` individually.
- Confirm Google selected the same canonical URL shown on each page, then request indexing where appropriate.
- Review Page indexing, Core Web Vitals and search-performance reports after Google has crawled the site.

## Analytics

- Create a production web property and obtain its real measurement ID before adding tracking code.
- Configure consent where applicable before loading non-essential analytics.
- Track only non-financial events; never send salary, loan, deduction or investment inputs.
- Update the privacy policy when tracking is enabled.
- Netlify traffic, Search Console performance and GitHub activity are different metrics.

## Google AdSense

- Apply with the final canonical hostname and wait for approval.
- Add only the official script and real publisher ID from the approved account.
- Create `/ads.txt` only with the real publisher record; never deploy an example ID.
- Test that ad units do not obscure calculator inputs or results.
- Configure Google's certified consent flow where required.
- Update the privacy policy before ads or advertising cookies are enabled.

## Ongoing review

- Recheck income-tax logic after every relevant Finance Act or official notification.
- Avoid undated lender-rate claims; use the rate in the visitor's current offer.
- Record material corrections on the About page.
- Add calculators only with a working tool, formula, assumptions, official sources, reviewer and date.
