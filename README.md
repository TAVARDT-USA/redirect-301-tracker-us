# HTTP 301/302 Redirect and Hop Chain Auditor

[![Redirect 301 Tracker](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/redirect-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits redirect paths, infinite loop detection, link equity conservation, and crawl budget efficiency.

***

## HTTP Redirect and Hop Chain Audit Capabilities

* **Complete Hop Chain Tracing**: Comprehensive hop-by-hop tracking across 301, 302, 307, and 308 HTTP redirect responses.
* **Infinite Redirect Loop Detection**: Immediate identification of cyclic paths causing critical browser and crawler failures.
* **Link Equity and PageRank Conservation**: Alerts against long redirect chains (> 3 hops) that dilute equity and waste crawl budget.
* **Mixed Protocol Verification**: Identification of insecure intermediary downgrades from HTTPS to HTTP.
* **Redirect Efficiency Health Score**: Quantitative 0 to 100 score with prioritized technical remediation steps.

***

## Installation and Execution

Requires Python 3.8 or higher utilizing only Python standard libraries.

```bash
git clone https://github.com/TAVARDT-USA/redirect-301-tracker-us.git
cd redirect-301-tracker-us
python redirect_tracker.py https://company.com
```

To output results in structured JSON format:

```bash
python redirect_tracker.py https://company.com -json
```

***

## Technical SEO and Site Migration Advisory

For enterprise platform migrations aligning with W3C Recommendations and IETF RFC 9110 Specifications, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/
* **Diagnostic Suite:** https://tools.tavardt.com/
* **Technical Contact:** https://ag.tavardt.com/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
