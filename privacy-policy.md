# Privacy Policy - Smart Home Compatibility Checker

Last updated: 2026-03-05

## What this extension does

Smart Home Compatibility Checker displays compatibility information for smart-home products on Amazon product pages.

## Data we process

- Product identifier (ASIN) from the current Amazon product page URL.
- Compatibility lookup request and response data required to show the badge.
- Local cache entries stored in the browser (IndexedDB), including ASIN and compatibility response.
- Unknown-product reports may include ASIN, product title, canonical product URL, and Amazon source domain.

## Data we do not collect

- Amazon account credentials
- Payment card data
- Full browsing history
- Personal messages or form input from websites

## How data is used

- To fetch and display compatibility information.
- To reduce repeated API calls via local caching.
- To improve product coverage when an ASIN is not yet in the compatibility database.

## Third-party services

- ExtensionPay may be used for payment and subscription status checks.
- Recurring subscription billing is processed by ExtensionPay/Stripe; this extension does not collect or store full payment card numbers.

## Data retention

- Local cache is automatically refreshed and effectively time-limited by TTL logic.
- Backend request logs should be retained only as needed for reliability and security operations.

## Security practices

- Environment variables are used for backend secrets.
- Input validation and ORM query parameterization are used to reduce injection risks.

## Your rights

If any personal data processing is introduced in future phases (accounts/subscriptions), users will be able to request access, correction, or deletion consistent with applicable privacy laws (including GDPR where applicable).

## Contact

Project contact email: `unifiedhomehq@gmail.com`
