# AI Kit

AI Kit builds tools on Cloudflare Workers: edge APIs and admin templates.

## Projects

| Repository | What it does | License |
|---|---|---|
| [nhtsa-edge-api](https://github.com/AIKitLLC/nhtsa-edge-api) | Offline [VIN](https://en.wikipedia.org/wiki/Vehicle_identification_number) decoder that runs inside a Cloudflare Worker, built from [NHTSA](https://www.nhtsa.gov/)'s public [vPIC](https://vpic.nhtsa.dot.gov/) data and verified against NHTSA's own [SQL](https://developer.mozilla.org/en-US/docs/Glossary/SQL). Live at [data.ai-kit.net](https://data.ai-kit.net). | MIT |
| [cloudflare-admin-template](https://github.com/AIKitLLC/cloudflare-admin-template) | Back-office starter on Cloudflare: Payload [CMS](https://developer.mozilla.org/en-US/docs/Glossary/CMS) v3, Next.js, Cloudflare D1 ([SQLite](https://www.sqlite.org/about.html)) and R2 storage. | MIT |

## How we build

- TypeScript on Cloudflare Workers, with D1 and R2.
- Both repositories run automated CI checks on pull requests and on pushes to the main branch. vPIC data refreshes for nhtsa-edge-api run through an automated workflow.

## Contact

Open an issue in the relevant repository.

Not affiliated with Cloudflare.
