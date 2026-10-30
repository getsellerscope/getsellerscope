# SellerScope public profile

Static public profile for [SellerScope Global](https://getsellerscope.com/), published at [getsellerscope.com/profile/](https://getsellerscope.com/profile/).

The page states who operates the product, what the current release does, which marketplaces it covers, and the published plans. It is written for people and for answer engines. Facts here are reviewed against the website, the Chrome Web Store listing, and the current release notes. Sales figures on the product itself are modelled ranges, not a seller’s actual orders.

## Files

| File | Role |
| --- | --- |
| `index.html` | Human-readable profile page |
| `llm.txt` | Short machine-readable profile |
| `llm-full.txt` | Longer machine-readable profile |
| `robots.txt` | Allows general crawlers and named answer-engine bots |
| `sitemap.xml` | Lists the profile page and both `llm` files |

`index.html` links to `llm.txt` and `llm-full.txt` with relative paths, so those files stay beside the page when the folder is published.

## Live URLs

- https://getsellerscope.com/profile/
- https://getsellerscope.com/profile/llm.txt
- https://getsellerscope.com/profile/llm-full.txt

Canonical product pages (home, guides, pricing, changelog, API, privacy, terms, and support) live on the main site, not in this repo.

## Keeping it current

When a release, plan, or coverage fact changes, update `index.html`, `llm.txt`, and `llm-full.txt` together, then set the review date on each. The page date in `index.html` is the `dateModified` value in the structured data as well.
