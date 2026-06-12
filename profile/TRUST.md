# Trust & engineering — AIOR (`aiorcom`)

Public summary of how AIOR builds and operates software. **No production secrets, hostnames, or customer data** are published here.

## Who we are

**AIOR Teknoloji Limited Şirketi** — engineering, software, design, AI, hosting and digital infrastructure.  
Website: [aior.com](https://aior.com) · Contact: [hi@aior.com](mailto:hi@aior.com)

## How we build (summary)

| Practice | What it means for you |
|----------|------------------------|
| **Private source** | Production code lives in private repositories — not public forks. |
| **Review before merge** | Changes to production branches require pull request + review. |
| **Automated checks** | CI validates builds; dependency and secret scanning on our toolchain. |
| **Single deploy authority** | Production releases come from a controlled Pilot environment — not from intern laptops. |
| **Risk-tiered releases** | Low-risk static updates vs payment/domain changes follow stricter gates. |
| **2FA + SSO** | Organization-wide 2FA; **GitHub Enterprise `aior` SAML** via Microsoft Entra (Enterprise Account app — already configured). |

## Security disclosure

Report vulnerabilities **privately** — do not open public issues with exploit details.

- Email: **hi@aior.com** (subject: `SECURITY`)
- KEP: aior@hs01.kep.tr  
- Platform policy: [SECURITY.md in private platform repo — request via email for scope]

We aim to acknowledge reports within **48 hours**.

## Compliance & location

- Registered company: **AIOR Teknoloji Limited Şirketi**, Bursa, Türkiye  
- BTK approved hosting provider listing (see org profile badge)  
- Customer data handled per our [Privacy Policy](https://aior.com/privacy) and applicable KVKK/GDPR principles  

## What this org page is not

- Not a download site for proprietary products  
- Not a support ticket channel — use [aior.com/contact](https://aior.com/contact) or WHMCS client area  
- Not a list of private client repositories  

## Open source

Only the organization profile repository (`.github`) is public under this org. Product code remains private unless explicitly released.

---

<sub>Last updated by AIOR engineering governance · [aior.com](https://aior.com)</sub>
