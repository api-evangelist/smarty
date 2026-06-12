# Smarty (smarty)

Smarty (formerly SmartyStreets) is an address intelligence company that provides REST APIs for US and international address verification, validation, geocoding, and autocomplete at high volume. The platform supports over 210 million US addresses including 20 million non-USPS addresses, delivering up to 55 metadata points and ZIP9-level geocodes per lookup. Smarty offers both cloud-hosted and on-premises deployment options, supporting embedded-key and secret-key authentication. APIs are designed for high-throughput workloads, with US address lookups reaching up to 25,000 per second.

APIs.json: https://raw.githubusercontent.com/api-evangelist/smarty/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=smarty-api-evangelist&utm_content=repo

## Tags

Address Verification, Geocoding, Address Autocomplete, ZIP Code, Address Intelligence, Location Data, International Address, US Address

## APIs

| Name | Description | Human URL |
|------|-------------|-----------|
| US Street Address API | Verifies and validates US street addresses against the USPS database, returning standardized components, deliverability status, and up to 55 metadata points including ZIP9 geocodes. | https://www.smarty.com/products/apis/us-street-api |
| US Autocomplete Pro API | Provides real-time US address suggestions as users type, returning verified deliverable address candidates. | https://www.smarty.com/products/apis/us-autocomplete-api |
| US ZIP Code API | Looks up and validates US ZIP codes, returning city and state associations, county data, and geographic metadata. | https://www.smarty.com/products/apis/us-zipcode-api |
| US Reverse Geocode API | Converts latitude/longitude coordinates into US street addresses with full component breakdown. | https://www.smarty.com/products/apis/us-reverse-geocoding |
| US Address Enrichment API | Returns up to 350 property attributes for a US address including property characteristics and ownership data. | https://www.smarty.com/products/apis/us-address-enrichment-api |
| US Extract API | Extracts and validates US addresses from freeform unstructured text input. | https://www.smarty.com/products/apis/us-extract-api |
| International Street Address API | Verifies and standardizes street addresses for countries outside the United States. | https://www.smarty.com/products/apis/international-street-api |
| International Address Autocomplete API | Delivers real-time address suggestions for international addresses as users type. | https://www.smarty.com/products/apis/international-address-autocomplete-api |
| International Postal Code API | Validates and looks up postal codes for international locations with city, region, and geographic metadata. | https://www.smarty.com/products/apis/international-postal-code-api |

## Plans / Rate Limits / FinOps

- Plans: [plans/smarty-plans-pricing.yml](plans/smarty-plans-pricing.yml)
- Rate Limits: [rate-limits/smarty-rate-limits.yml](rate-limits/smarty-rate-limits.yml)
- FinOps: [finops/smarty-finops.yml](finops/smarty-finops.yml)

**Pricing summary:** Freemium — 42-day free trial (1,000 US lookups, 100 international). Professional US plans start at $50/month; international plans start at $95/month. No overages; quota depletion returns HTTP 402. Enterprise plans available with custom quotas.

**Rate limits:** Plan-based throughput of 25,000 lookups/second (US) and 3,500/second (international). Embedded-key requests have undisclosed per-IP security limits. HTTP 429 returned with a Retry-After header on throttling. Leaky Bucket algorithm.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.smarty.com/ |
| Documentation | https://www.smarty.com/docs |
| GitHub Organization | https://github.com/smartystreets |
| LinkedIn | https://www.linkedin.com/company/smarty-digital-llc |
| Blog | https://www.smarty.com/blog |
| Pricing | https://www.smarty.com/pricing |
| Status Page | https://status.smarty.com/ |
| Changelog | https://www.smarty.com/docs/changelog |
| X | https://x.com/smartycompany |

## Maintainers

- Kin Lane / kin@apievangelist.com
