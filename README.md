# SellerScope public profile

Static public profile for [SellerScope Global](https://getsellerscope.com/). The profile files are in this repository: [github.com/getsellerscope/getsellerscope](https://github.com/getsellerscope/getsellerscope).

The page states who operates the product, what the current release does, which marketplaces it covers, and the published plans. It is written for people and for answer engines. Facts here are reviewed against the website, the Chrome Web Store listing, and the current release notes. Sales figures on the product itself are modelled ranges, not a seller’s actual orders.

## Files

| File | Role |
| --- | --- |
| `index.html` | Human-readable profile page |
| `llm.txt` | Short machine-readable profile |
| `llm-full.txt` | Longer machine-readable profile |
| `robots.txt` | Allows general crawlers and named answer-engine bots |
| `sitemap.xml` | Lists the profile page and both `llm` files |

`index.html` links to `llm.txt` and `llm-full.txt` with relative paths, so those files stay beside the page in the repository.

## Profile files on GitHub

- [Human profile](https://github.com/getsellerscope/getsellerscope/blob/main/index.html)
- [Short profile](https://github.com/getsellerscope/getsellerscope/blob/main/llm.txt)
- [Full profile](https://github.com/getsellerscope/getsellerscope/blob/main/llm-full.txt)

Canonical product pages (home, guides, pricing, changelog, API, privacy, terms, and support) live on [getsellerscope.com](https://getsellerscope.com/), not in this repo.

## Keeping it current

When a release, plan, or coverage fact changes, update `index.html`, `llm.txt`, and `llm-full.txt` together, then set the review date on each. The page date in `index.html` is the `dateModified` value in the structured data as well.
