# MoveLedger — redirect map review before a website migration

[Use the free redirect map checker](https://getmoveledger.com/?utm_source=github&utm_medium=referral&utm_campaign=repository) · [Try a redirect-chain example](https://getmoveledger.com/?example=chain&utm_source=github&utm_medium=referral&utm_campaign=repository#workspace) · [Templates and guides](https://getmoveledger.com/resources.html?utm_source=github&utm_medium=referral&utm_campaign=repository)

MoveLedger reviews a **planned CSV redirect map** before deployment. It is for developers, technical SEOs and small web agencies preparing website migrations. The hosted free checker accepts up to **1,000 exact-match rules** without an account, and processes migration files in your browser.

## What the live checker does

- Finds redirect loops, self-redirects, chains, duplicate sources and conflicting destinations.
- Compares the map with optional old-URL and destination inventories.
- Accepts `source,target`, Shopify `Redirect from,Redirect to`, and Webflow `Old path,Redirect to path` CSV headers.
- Filters findings and exports a findings CSV or printable review report.
- Includes worked examples and downloadable templates.

```csv
source,target,status
/old-guide,/guide,301
/guide,/learn/guide,301
```

This example contains a two-hop chain. The checker makes the route visible so a reviewer can decide whether `/old-guide` should point directly to `/learn/guide`.

## Useful migration resources

- [Redirect map CSV template and column guide](https://getmoveledger.com/redirect-map-template.html?utm_source=github&utm_medium=referral&utm_campaign=repository)
- [Find and review redirect chains](https://getmoveledger.com/redirect-chains.html?utm_source=github&utm_medium=referral&utm_campaign=repository)
- [Shopify redirect CSV review](https://getmoveledger.com/shopify-redirect-csv.html?utm_source=github&utm_medium=referral&utm_campaign=repository)
- [Webflow redirect CSV template and import checklist](https://getmoveledger.com/webflow-redirect-csv.html?utm_source=github&utm_medium=referral&utm_campaign=repository)
- [Website migration field guide](https://getmoveledger.com/guide.html?utm_source=github&utm_medium=referral&utm_campaign=repository)

## Scope and privacy

This is **structural review of supplied rules**, not a live HTTP crawler. It does not test server responses, apply redirects, support regular expressions, or guarantee a migration or search ranking outcome. Origins, case, query strings and trailing slashes remain distinct. A finding-free report is not launch approval.

Redirect maps, project names and findings text stay in the browser. The live site offers optional first-party usage measurement; read the [privacy and measurement notice](https://getmoveledger.com/privacy.html).

## About this repository

The code here is an early public preview snapshot, not the current production deployment source. For the current product, limits, privacy notice and resources, use [getmoveledger.com](https://getmoveledger.com/?utm_source=github&utm_medium=referral&utm_campaign=repository). The planned paid agency edition is not open for sales.

## Feedback

Agency SEO or migration practitioner? [Share what your workflow needs](https://getmoveledger.com/feedback.html?utm_source=github&utm_medium=referral&utm_campaign=repository): four optional choices, no signup or email. This is product research, not a purchase or reservation.

If you find a reproducible checker problem, an issue with a small **invented or anonymized** CSV example is useful. Do not post client URLs, private migration plans or credentials. Include the expected result and the result you observed.
