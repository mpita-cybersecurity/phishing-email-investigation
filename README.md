# Phishing Email Investigation

## Project Overview

This project is a beginner-level cybersecurity investigation of a simulated phishing email.

The purpose of the investigation is to identify common phishing and social-engineering indicators, assess the potential risks, and recommend appropriate security actions.

## Scenario

An employee received an email claiming to be from an IT Security Team. The email stated that the employee's account would be suspended within 24 hours unless they immediately verified their information through a provided link.

The email uses urgency and fear to encourage the recipient to take immediate action.

## Suspicious Email

**Sender:** IT Support `<it-support@securebank-verification.com>`

**Subject:** URGENT: Your account will be suspended today

**Message:**

> Dear Customer,
>
> We detected unusual activity on your account. Your account will be suspended within 24 hours unless you verify your information immediately.
>
> Please click the link below to verify your account:
>
> `https://securebank-verification.com/verify`
>
> Failure to complete verification may result in permanent account suspension.
>
> Regards,
> IT Security Team

## Investigation Findings

### 1. Urgency

The email claims that the account will be suspended within 24 hours.

This creates pressure and encourages the recipient to act without carefully checking the message.

### 2. Suspicious Sender

The sender uses the domain `securebank-verification.com`.

The domain should be independently verified before trusting the message.

### 3. Suspicious Link

The email asks the recipient to click a link to verify their information.

Users should avoid clicking suspicious links and should independently visit the organisation's official website instead.

### 4. Request for Information

The email asks the recipient to verify their information.

Requests for sensitive information through unexpected emails should be treated with caution.

### 5. Social Engineering

The message uses fear, urgency and the possibility of account suspension to influence the recipient's behaviour.

## Indicators of Phishing

| Indicator           | Finding                                        |
| ------------------- | ---------------------------------------------- |
| Urgency             | Account supposedly suspended within 24 hours   |
| Suspicious domain   | `securebank-verification.com`                  |
| Suspicious link     | Verification link included                     |
| Fear tactic         | Threat of account suspension                   |
| Information request | User is asked to verify information            |
| Social engineering  | Pressure is used to encourage immediate action |

## Risk Assessment

The email presents a potential risk because a user could be tricked into clicking the link and providing sensitive information to an attacker.

Potential consequences could include:

* Credential theft
* Identity theft
* Unauthorised account access
* Financial loss
* Exposure of personal information

## Recommended Actions

1. Do not click the link.
2. Do not provide personal or login information.
3. Report the email to the organisation's IT/security team.
4. Delete or quarantine the suspicious email.
5. If the link was clicked, change affected passwords and report the incident immediately.
6. Enable multi-factor authentication where available.

## Conclusion

The simulated email contains multiple characteristics commonly associated with phishing, including urgency, fear-based language, a suspicious domain, a verification link and a request for information.

The recommended response is to avoid interacting with the email, report it through the appropriate security process and verify any account-related communication through an independently trusted channel.

## Skills Demonstrated

* Phishing identification
* Social-engineering analysis
* Basic threat assessment
* Indicators of compromise identification
* Security incident documentation
* Security awareness
