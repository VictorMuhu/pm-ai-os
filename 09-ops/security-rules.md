# Security Rules for PM AI OS

Rules for keeping the PM AI operating system secure, clean, and safe to use across contexts.

---

## General Principles

- do not store company-confidential documents in any repo in this system
- avoid storing real customer data, names, or identifying information
- never commit credentials, API keys, or access tokens to any repository
- when in doubt about whether content is safe to store, do not store it

---

## Allowed Content

The following content is appropriate for this system:

- reusable PM workflows and method definitions
- generalized templates and frameworks
- sanitized demo materials using fictional examples
- synthesized research with identifying details removed
- skill definitions, rubrics, and operating documentation

---

## Restricted Content

The following content must not be stored in any repository in this system:

- proprietary roadmaps or internal strategy documents from an employer
- internal customer interview transcripts or recordings
- internal dashboards or screenshots showing confidential metrics
- confidential metrics exports from company analytics systems
- legal agreements, financial data, or compliance documents
- anything marked confidential, restricted, or internal by an employer

---

## GitHub Guidelines

- all repositories in this system should remain private unless explicitly reviewed for public sharing
- use strong authentication: enable two-factor authentication on GitHub
- never commit secrets, credentials, tokens, or environment variables to any repository
- use `.gitignore` to prevent accidental commits of sensitive file types
- review repository contents before changing visibility from private to public

---

## Demo Safety

Anything placed in `pm-ai-demo` must be safe to show externally.

That means:

- all examples must be fictional and clearly not derived from a real employer
- no real customer names, company names, or internal product names
- no screenshots that reveal confidential interfaces or unreleased features
- no metrics or data points that could be traced back to a real company
- when in doubt, make the example more generic before adding it to the demo repo
