# Indicators of Compromise (IOCs)

## Overview

This document records the indicators identified during the simulated phishing email investigation.

IOCs are pieces of information that can assist security analysts when investigating potentially malicious activity.

## Identified Indicators

| Type          | Indicator                                      | Description                                         |
| ------------- | ---------------------------------------------- | --------------------------------------------------- |
| Email Address | `it-support@securebank-verification.com`       | Sender address used in the simulated phishing email |
| Domain        | `securebank-verification.com`                  | Domain used in the suspicious email                 |
| URL           | `https://securebank-verification.com/verify`   | Verification link included in the email             |
| Subject       | `URGENT: Your account will be suspended today` | Subject uses urgency to pressure the recipient      |

## Risk

The identified indicators should be treated as suspicious within the context of this simulated investigation.

The domain and URL should not be accessed directly without appropriate security controls and further investigation.

## Recommended Actions

* Do not visit the suspicious URL.
* Do not provide credentials or personal information.
* Report the suspicious email to the appropriate security team.
* Block or quarantine confirmed malicious indicators according to organisational procedures.
* Investigate related email messages and security logs for additional activity.

## Conclusion

The collected indicators provide useful information for further investigation and security monitoring.

In a real-world incident, analysts would correlate these indicators with email security logs, DNS records, network traffic and other available security data.
