# HTTP 301/302 Redirect and Hop Chain Auditor

[![Redirect 301 Tracker](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/redirect-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-United%20States-00C853.svg)](https://ag.tavardt.com/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits redirect paths, infinite loop detection, link equity conservation, and crawl budget efficiency.

Developed and maintained by the search systems engineering and crawl efficiency division of **[TAVARDT USA](https://ag.tavardt.com/)**.

---

## HTTP Redirect and Hop Chain Audit Capabilities

* **Complete Hop Chain Tracing**: Comprehensive hop-by-hop tracking across 301, 302, 307, and 308 HTTP redirect responses.
* **Infinite Redirect Loop Detection**: Immediate identification of cyclic paths causing critical browser and crawler failures.
* **Link Equity and PageRank Conservation**: Alerts against long redirect chains (> 3 hops) that dilute equity and waste crawl budget.
* **Mixed Protocol Verification**: Identification of insecure intermediary downgrades from HTTPS to HTTP.
* **Redirect Efficiency Health Score**: Quantitative 0 to 100 score with prioritized technical remediation steps.

---

## Installation and Execution

Requires Python 3.8 or higher utilizing only Python standard libraries.

```bash
git clone https://github.com/TAVARDT-USA/redirect-301-tracker-us.git
cd redirect-301-tracker-us
python redirect_tracker.py https://company.com
```

To output results in structured JSON format:

```bash
python redirect_tracker.py https://company.com --json
```

---

## Comprehensive Web Diagnostic

For full web verification and deep redirect chain inspections:

* **[Official Redirect Checker Tool](https://tools.tavardt.com/redirect-checker/)**
* **[TAVARDT USA Enterprise Portal](https://ag.tavardt.com/)**

---

## Technical SEO and Site Migration Advisory

For enterprise platform migrations aligning with W3C Recommendations and IETF RFC 9110 Specifications, contact the specialists at **[TAVARDT USA](https://ag.tavardt.com/contact/)**.
