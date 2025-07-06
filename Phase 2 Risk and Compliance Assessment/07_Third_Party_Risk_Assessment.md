# Third-Party Risk Assessment

## Overview
Identifying potential risks from dependencies on external services or components.

| Third-Party Service      | Usage                              | Risk           | Mitigation Plan                         |
|--------------------------|------------------------------------|----------------|-----------------------------------------|
| Google Cloud             | Hosting environment                | Medium         | IAM roles, firewall rules               |
| OpenCart CMS             | E-commerce platform                | Medium         | Keep updated, apply patches             |
| MySQL                    | Database service                   | High           | Harden config, strong credentials       |
| External Payment Gateway | Not yet implemented (planned)     | TBD            | Use PCIDSS-compliant provider           |

> These services must be continuously monitored for updates, outages, and vulnerabilities.
