# Privacy Policy - Smart Home Compatibility Checker

Last updated: 2026-05-20

## What this extension does

Smart Home Compatibility Checker displays compatibility information for smart-home products on Amazon product pages.

## Data we process

- Product identifier (ASIN) from the current Amazon product page URL.
- Compatibility lookup request and response data required to show the badge.
- Local cache entries stored in the browser (IndexedDB), including ASIN and compatibility response.
- Unknown-product reports may include ASIN, product title, canonical product URL, and Amazon source domain.
- Product data captured from Amazon product pages you visit, including product title, brand, feature bullets, technical specifications, detected ecosystem labels, image URL, and source product URL. This capture is used to improve compatibility data accuracy.
- Error reports may include ASIN, product title, canonical product URL, Amazon source domain, the selected error type, and the description text you submit.

## Data we do not collect

- Amazon account credentials
- Payment card data
- Full browsing history
- User identifiers, email addresses, or names through the compatibility checker itself
- Personal messages or form input from websites

## How data is used

- To fetch and display compatibility information.
- To reduce repeated API calls via local caching.
- To improve product coverage when an ASIN is not yet in the compatibility database.
- To improve compatibility data quality using product details captured from product pages you choose to view.
- To triage and correct compatibility issues reported through the extension.

Some compatibility information may be generated or completed with AI-assisted enrichment. AI-estimated compatibility information may be inaccurate and should be verified with the manufacturer before purchase or installation.

## Third-party services

- ExtensionPay may be used for payment and subscription status checks.
- Recurring subscription billing is processed by ExtensionPay/Stripe; this extension does not collect or store full payment card numbers.
- Backend enrichment may use OpenAI for structured compatibility gap-fill when deterministic sources are incomplete.
- Compatibility enrichment may reference public data sources such as Home Assistant manifests, Matter DCL certification data, Blakadder Zigbee data, Z-Wave JS device configuration, optional openHAB Z-Wave definitions, and matterdatabase data.

## Data retention

- Local cache is automatically refreshed and effectively time-limited by TTL logic.
- Backend request logs should be retained only as needed for reliability and security operations.
- Captured product data is stored by ASIN and updated when newer product page data is received.
- Unknown-product reports and error reports are retained while they are useful for catalog quality and triage.

## Security practices

- Environment variables are used for backend secrets.
- Input validation and ORM query parameterization are used to reduce injection risks.

## Your rights

If any personal data processing is introduced in future phases (accounts/subscriptions), users will be able to request access, correction, or deletion consistent with applicable privacy laws (including GDPR where applicable).

## Contact

Project contact email: `unifiedhomehq@gmail.com`
