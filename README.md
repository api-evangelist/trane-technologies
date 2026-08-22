# Trane Technologies (trane-technologies)

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

Trane Technologies plc (NYSE: TT) is an Ireland-domiciled global climate
innovator that designs, manufactures, sells, and services HVAC, transport
refrigeration, and building-automation systems under the **Trane**,
**Thermo King**, and **American Standard Heating & Air Conditioning**
brands. Spun off from Ingersoll-Rand in 2020, the company reported
~US$23.9B in revenue, ~45,000 employees, and operations in 61 countries.

Its digital surface centers on **Trane Connect** (cloud building portal),
**Tracer SC+** and **Symbio** controllers for commercial building
automation, and the **Thermo King TracKing / ConnectedSuite** telematics
platform for transport refrigeration units (TRUs). A partner-gated
developer portal is hosted at `developer.devops.chvac.trane.com`; no
self-serve public API catalog is published.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/trane-technologies/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Partner
- **x-type:** company
- **x-tier:** 3

## Tags

HVAC, Cold Chain, Telematics, Building Automation, IoT, Refrigeration,
Transport Refrigeration, BACnet, Smart Buildings, Fortune 500

## APIs

### Trane Developer Portal

Partner-facing developer portal at `developer.devops.chvac.trane.com`
for Trane Commercial HVAC ("CHVAC") cloud and controls APIs. Gated,
no public OpenAPI catalog outside of partner enrollment.

- **Portal:** [developer.devops.chvac.trane.com](https://developer.devops.chvac.trane.com/)
- **Systems Integration:** [Trane Connectivity & Cloud Services](https://www.trane.com/commercial/north-america/us/en/services/operate-maintain-repair/connectivity-and-cloud-services/systems-integration.html)

### Trane Connect

Secure, cloud-based customer portal for remote monitoring, schedules,
alarms, and trends on Trane-connected buildings; programmatic access
via the partner developer portal.

### Tracer SC+ Building Automation System

Commercial building automation controller supporting BACnet/IP,
BACnet MS/TP, BACnet Secure Connect, Modbus (RTU and TCP/IP), and
LonTalk, with Trane APIs and integration toolkits for third-party
equipment.

### Trane Symbio Digital Equipment Controllers

Equipment-level controllers (chillers, RTUs, AHUs) communicating
over BACnet (MS/TP, IP, Zigbee), Modbus (client/server), and
Air-Fi wireless; integrates upstream into Tracer SC+ and Trane
Connect.

### Thermo King TracKing Telematics

Flagship telematics platform for transport refrigeration units
(trailers, trucks, vans, rail) exposing reefer setpoints, supply
and return air, alarms, door events, fuel, location, and operating
mode. Web-service integration is granted by Thermo King support;
ecosystem includes Samsara, Motive, Mapon, Teletrac Navman, Alvys.

### Thermo King ConnectedSuite

Umbrella of TracKing, TracKing Pro, Smart Trailer Telematics, and
the Remote Operating Center for refrigerated transport fleets.

### Trane Residential Connected Thermostats

ComfortLink II XL1050 / XL850, LINK UX360, XL824, XR724 smart
thermostats; no public consumer developer API today.

### BrainBox AI (Trane Technologies)

Autonomous HVAC-optimization AI platform; enterprise cloud
integrations only — no public developer API portal.

## Common Properties

- [Trane Technologies Website](https://www.tranetechnologies.com/)
- [Trane Commercial](https://www.trane.com/commercial/)
- [Trane Residential](https://www.trane.com/residential/)
- [Thermo King](https://www.thermoking.com/na/en.html)
- [American Standard](https://www.americanstandardair.com/)
- [Trane Developer Portal](https://developer.devops.chvac.trane.com/)
- [Connectivity and Cloud Services](https://www.trane.com/commercial/north-america/us/en/services/operate-maintain-repair/connectivity-and-cloud-services.html)
- [Systems Integration](https://www.trane.com/commercial/north-america/us/en/services/operate-maintain-repair/connectivity-and-cloud-services/systems-integration.html)
- [Trane Technologies eLibrary](https://elibrary.tranetechnologies.com/)
- [Software & Firmware Downloads](https://www.trane.com/commercial/north-america/us/en/products-systems/building-management---automation/trane-controls-software-downloads.html)
- [GitHub Organization](https://github.com/Trane-Technologies)
- [LinkedIn](https://www.linkedin.com/company/trane-technologies/)
- [News Room](https://www.tranetechnologies.com/en/index/news-and-events.html)
- [Investor Relations](https://www.tranetechnologies.com/en/index/investor-relations.html)
- [Sustainability](https://www.tranetechnologies.com/en/index/sustainability.html)
- [Careers](https://careers.tranetechnologies.com/)
- [Contact](https://www.tranetechnologies.com/en/index/contact-us.html)

## Artifacts

- [Plans & Pricing](plans/trane-technologies-plans-pricing.yml)
- [Rate Limits](rate-limits/trane-technologies-rate-limits.yml)
- [FinOps](finops/trane-technologies-finops.yml)
- [JSON-LD Context](json-ld/trane-technologies-context.jsonld)
- [Vocabulary](vocabulary/trane-technologies-vocabulary.yml)

## Notable Absences

- No public, self-serve OpenAPI / Swagger catalog (developer portal is partner-gated).
- No public pricing for any digital surface; everything is dealer / sales-quoted.
- No public GitHub repos (the `Trane-Technologies` org exists but is empty / private).
- No public rate-limit, SLA, or status page for the developer surface.
- No public residential thermostat API (Seam lists Trane support as inquiry-only).

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
