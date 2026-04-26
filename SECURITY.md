# Security Policy

HoloCard UI is maintained as a public-facing premium UI component and portfolio product repository. This policy defines how security concerns should be reported, what is in scope for public review, and which implementation or commercial details must remain private.

## Public Edition Security Scope

This repository represents the Public Edition of HoloCard UI. Public materials may include product positioning, static interface previews, public source materials intentionally published in this repository, governance files, and safe evaluation materials.

This repository must not disclose or request disclosure of:

- private commercial package materials, unreleased design variants, or buyer-only deliverables
- private animation systems, visual direction files, audio design notes, or premium asset sources not intentionally published
- private payment, licensing, fulfillment, analytics, or customer-support implementation details
- customer data, buyer information, transaction records, license keys, or commercial account details
- API keys, tokens, OAuth credentials, service-account files, secrets, or environment variables
- private prompts, creative briefs, internal playbooks, pricing strategy, or launch materials
- production deployment methods, access-control logic, or private distribution workflows

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- browser security concerns in public code, including unsafe script injection, unsafe external links, or unsafe asset loading
- dependency, supply-chain, or build configuration concerns, if such files are later added
- repository configuration issues that affect integrity, trust, or disclosure handling

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct user risk:

- generic best-practice requests without a specific security impact
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- third-party platform issues outside this repository owner's control
- requests for private commercial files, buyer assets, unreleased visual systems, audio internals, or deployment details
- subjective design, animation, audio, or product-positioning preferences with no security impact

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, customer information, private commercial details, private asset references, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public product and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to unauthorized access, credential misuse, data theft, extortion, payment abuse, license-key abuse, scraping buyer-only materials, or attempts to obtain Private Commercial Edition materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

HoloCard UI is intended for lawful UI evaluation, portfolio presentation, frontend component review, and commercial product discussion. Reports, issues, pull requests, or discussions that enable credential misuse, payment abuse, buyer-data exposure, unsafe script behavior, or private material extraction may be closed or removed.