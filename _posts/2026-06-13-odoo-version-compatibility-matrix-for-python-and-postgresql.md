---
title: "Odoo version compatibility matrix for Python and PostgreSQL"
author: Daniel Reis
permalink: /odoo-version-compatibility-matrix-for-python-and-postgresql/
---

Per Odoo's official support policy, only the three most recent Long-Term
Support (LTS) versions receive active bug fixes and security updates. Older
releases are retired annually during the Experience event, moving them into
**End of Life (EOL)** status.

### Odoo Version Compatibility Matrix (Versions 14 to 20)

| Odoo Version     | Python Compatibility | Recommended Python | PostgreSQL Support | EOL Date / Status |
|------------------|----------------------|--------------------|--------------------|-------------------|
| **20.0 (Master)** | 3.10 - 3.12         | **3.12**           | 15 - 17            | **October 2027**  |
| **19.0**         | 3.10 - 3.12          | **3.12**           | 14 - 16            | **October 2026**  |
| **18.0**         | 3.10 - 3.12          | **3.12**           | 14 - 16            | **October 2025**  |
| **17.0**         | 3.10, 3.11           | **3.10**           | 13 - 15            | **October 2024**  |
| **16.0**         | 3.8 - 3.10           | **3.10**           | 12 - 15            | **October 2023**  |
| **15.0**         | 3.7 - 3.9            | **3.8**            | 11 - 13            | **October 2022**  |
| **14.0**         | 3.6 - 3.8            | **3.7**            | 10 - 12            | **October 2021**  |

## Ubuntu LTS alignment

| Ubuntu Version (LTS)      | Default Python | Native PostgreSQL | Release Date | Standard Support EOL |
|---------------------------|----------------|-------------------|--------------|----------------------|
| **26.04 (Resolute Raccoon)** | 3.14        | 18                | April 2026   | **May 2031**         |
| **24.04 (Noble Numbat)**  | 3.12           | 16                | April 2024   | **June 2029**        |
| **22.04 (Jammy Jellyfish)** | 3.10         | 14                | April 2022   | **June 2027**        |
| **20.04 (Focal Fossa)**   | 3.8            | 12                | April 2020   | **May 2025**         |
| **18.04 (Bionic Beaver)** | 3.6            | 10                | April 2018   | **June 2023**        |
| **16.04 (Xenial Xerus)**  | 3.5            | 9.5               | April 2016   | **April 2021**       |
| **14.04 (Trusty Tahr)**   | 3.4            | 9.3               | April 2014   | **April 2019**       |

### Production Risks of EOL Environments

* **Security Vulnerabilities:** Once a version hits its EOL date, it no longer
  receives critical security patches from upstream source maintainers. If your
  instances remain public-facing, they are exposed to unpatched framework
  flaws.
* **Module Ecosystem Freeze:** The Odoo App Store freezes active support tags
  over time. Third-party vendors phase out module maintenance for versions
  beneath Odoo 16, restricting your ability to add new marketplace
  enhancements cleanly.
