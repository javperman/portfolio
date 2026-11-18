# Sources and verification

Accessed 2026-11-18 unless noted.

| Claim | Source | Status |
|---|---|---|
| Product is a Japanese exit-agency SaaS (退職代行) | [taishokureset.com](https://taishokureset.com) | Public |
| Public service flow starts with LINE and uses web forms | [taishokureset.com](https://taishokureset.com) | Public |
| Public legal disclosure page exists | [taishokureset.com/tokushoho](https://taishokureset.com/tokushoho) | Public, HTTP 200 |
| Public Instagram channel | [instagram.com/taishokureset](https://www.instagram.com/taishokureset/) | Public, HTTP 200 |
| Next.js surface | HTTP response header `x-powered-by: Next.js` | Public |
| Cloudflare edge | HTTP response header `server: cloudflare` and `cf-ray` | Public |
| Production since 2026-11-08 | Author attestation (co-founder), 2026-11-18 | **Private/unverifiable publicly** |
| Role: Co-Founder & Tech Lead | Author attestation (co-founder), 2026-11-18 | **Private** |
| Stack: Cloudflare D1/KV, Vertex AI, Cloud Run, Telnyx, NextAuth | Author attestation (technical lead), 2026-11-18 | **Private** |
| Public flow detail (case handling, calls, completion/cancellation/payment) | Public website + author attestation | Mixed |
| No source code, prompts, schema, pricing, panel, customer data or metrics published | Publication authorization, 2026-11-18 | Scope decision |

## Notes

- The public 特商法 page contains the seller's name, address and phone number.
  Those details are **not copied** into this repository; the page is linked only.
- The exact production date is known from the author's launch record. No public
  timestamp (sitemap/Wayback/HTTP header) independently proves it; the LinkedIn
  launch post is not linked here to avoid embedding a personal post URL without
  review. This is marked as author attestation, not independent verification.
- Stack details beyond Next.js/Cloudflare are from the author's knowledge of the
  private production system. They are intentionally described at box level.
- No customer names, case details, prices, internal metrics, analytics IDs or
  endpoints are included.
- The authorization covers the product name, the author's role, the public flow,
  the high-level architecture and public links. It excludes code, credentials,
  prompts, schema, operator panel, pricing logic, customer data and internal
  metrics.
