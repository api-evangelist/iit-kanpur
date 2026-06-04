# Indian Institute of Technology Kanpur (iit-kanpur)

The Indian Institute of Technology Kanpur (IIT Kanpur), founded in 1959 in Kanpur, Uttar Pradesh, is one of India's premier engineering and research institutions, ranked #263 in the QS World University Rankings 2025. This repository catalogs IIT Kanpur's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. IIT Kanpur does not operate a unified central developer portal; its verifiable public programmatic surface centers on the P.K. Kelkar Library's Koha integrated library system.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/iit-kanpur/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=iit-kanpur-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, India, Open Access, Library, Metadata

## APIs

- **PKK Library OAI-PMH** — Live OAI-PMH 2.0 metadata-harvesting endpoint over the P.K. Kelkar Library Koha catalogue (repository name "PKK Library", oai_dc supported). Docs: https://libserv.iitk.ac.in/ | Identify: https://libserv.iitk.ac.in/cgi-bin/koha/oai.pl?verb=Identify
- **PKK Library Koha ILS-DI** — Koha ILS-DI discovery-interface web service for bibliographic, holdings, patron, and circulation operations (Koha 23.11). Docs: https://libserv.iitk.ac.in/cgi-bin/koha/ilsdi.pl

## Plans / Rate Limits / FinOps

- Plans: [plans/iit-kanpur-plans-pricing.yml](plans/iit-kanpur-plans-pricing.yml)
- Rate Limits: [rate-limits/iit-kanpur-rate-limits.yml](rate-limits/iit-kanpur-rate-limits.yml)
- FinOps: [finops/iit-kanpur-finops.yml](finops/iit-kanpur-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.iitk.ac.in/
- LinkedIn: https://www.linkedin.com/school/indian-institute-of-technology-kanpur/
- Review: [review.yml](review.yml)

## Notes

All cataloged APIs were probed live during research. The PKK Library OAI-PMH endpoint returned a valid OAI-PMH 2.0 Identify and ListMetadataFormats response; the Koha ILS-DI page resolved (HTTP 200). The Koha SRU endpoint returned HTTP 404 and is not cataloged. The Pingala ERP/SIS portal (https://pingala.iitk.ac.in/) is login-gated with no documented public API. No single official institutional GitHub organization was confirmed — only student-club and academic-department orgs (e.g., cseAtIITK, pclubiitk) exist — so no organization-level GitHub property is asserted. No endpoints were fabricated; properties reflect only confirmed, publicly reachable URLs.

## Maintainers

- Kin Lane — kin@apievangelist.com
