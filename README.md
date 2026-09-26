# MBZ Miami USA — Website Proposal

Functional, navigable website proposal for **MBZ Miami USA Corp.** (vehicle export and ocean freight, Miami Gardens, FL).

Static site (HTML + CSS + vanilla JS, no build step). Ready for GitHub Pages.

## Pages (hash routing)
| Route | Content |
|---|---|
| `#home` | Video hero, tracking search, proof strip, 4-step process, client portal, services, CTA |
| `#services` | Six services + Container vs RoRo comparison |
| `#track` | Sample shipment: route, timeline, documents, arrival photos |
| `#quote` | Instant estimator + firm-quote request form |
| `#about` | Company, FMC OTI license, facility, BBB rating |
| `#contact` | Phone/WhatsApp, warehouse address, hours |
| `#proposal` | Comparison vs current site and competitor, next steps |

## Run locally
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Publish with GitHub Pages
Settings → Pages → Source: `Deploy from a branch` → Branch `main` / `(root)`.

## Pending confirmation with MBZ
- Estimator rates and transit times are **sample figures**.
- Tracking data is a **sample shipment**; to be connected to the MBZ system (React + PostgreSQL + ECS on AWS).
- Confirm services (RoRo, auction pickup, insurance), destinations, email and WhatsApp number.
- Spanish version (EN/ES switch).

## Structure
```
index.html
ship.mp4         hero video (muted, 10 s loop, 720p)
poster.jpg       video poster
frame-*.jpg      stills used on inner pages
```
