# Trane Technologies (trane-technologies)

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
