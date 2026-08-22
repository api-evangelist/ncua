# National Credit Union Administration (NCUA)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The National Credit Union Administration (NCUA) is the independent federal agency created by the U.S. Congress to regulate, charter, and supervise federal credit unions. With the backing of the full faith and credit of the U.S. Government, NCUA operates and manages the National Credit Union Share Insurance Fund, insuring the deposits of account holders in all federal credit unions and the overwhelming majority of state-chartered credit unions.

## APIs and Data Services

NCUA provides several public data APIs and tools for accessing credit union financial data:

### Credit Union Locator API
A JSON-based API powering the NCUA Credit Union Locator tool at mapping.ncua.gov. Supports searching credit union offices by name, charter number, or address with radius-based geographic filtering. Returns office locations, coordinates, contact details, and site functions.

- **URL:** https://mapping.ncua.gov/

### 5300 Call Report Quarterly Data
Publicly available financial performance data for all federally insured credit unions based on their quarterly Call Report (Form 5300) filings. Available as bulk ZIP downloads in comma-delimited text format from March 1994 to present.

- **URL:** https://ncua.gov/analysis/credit-union-corporate-call-report-data/quarterly-data
- **Contact:** 5300@ncua.gov

### Custom Data Query Tool
An interactive tool for querying financial information from the 5300 Call Report cycle. Filter by charter number, region, type, city, state, zip, assets, loans, shares, investments, and net income across reporting cycles back to 2004.

- **URL:** https://webapps2.ncua.gov/CustomQuery/

### CUOnline Data Web Service
A bulk data web service providing real-time access to call report data for registered industry data aggregators. Requires registration with NCUA including a technical point of contact and static IP address.

- **URL:** https://ncua.gov/regulation-supervision/regulatory-reporting/cuonline
- **Contact:** 5300@ncua.gov

### CUSO Registry
Searchable public registry of Credit Union Service Organizations (CUSOs), their services, financial relationships, and affiliated credit unions.

- **URL:** https://cusoregistry.ncua.gov/Search/Search

## Links

- **Website:** https://ncua.gov/
- **Open Data:** https://ncua.gov/data
- **Newsroom/Blog:** https://ncua.gov/news/latest-news
- **LinkedIn:** https://www.linkedin.com/company/national-credit-union-administration
- **X (Twitter):** https://x.com/TheNCUA

## Pricing

All NCUA data services are free of charge. The CUOnline bulk web service is also free but requires registration.

## Contact

- **General Data:** BImail@ncua.gov
- **Call Report / CUOnline:** 5300@ncua.gov
- **Technical Support:** OneStop@ncua.gov | 1-800-827-3255
