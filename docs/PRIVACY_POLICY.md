# Privacy Policy — Domain & SSL Watcher

**Last updated:** July 10, 2026

Domain & SSL Watcher ("the Extension") helps you monitor domain registration and SSL certificate expiration dates. This policy explains what information the Extension handles and how.

## Summary

- Your monitored domain list and settings are stored **locally in your browser**.
- We do **not** operate a backend server that receives or stores your domain list.
- The Extension queries **public** domain and certificate services only for domains **you add**.
- We do **not** sell user data.

## Information stored locally

The Extension uses Chrome `storage` to save, on your device:

- Domain names you choose to monitor
- Alert thresholds, check interval, language, and timezone preferences
- Notification and webhook settings (Pro)
- ExtensionPay subscription status (Pro)

This data stays in your browser unless you uninstall the Extension or clear extension data.

## Information sent over the network

When you run a check, the Extension may contact public services such as RDAP/WHOIS providers, certificate transparency logs, and SSL analysis endpoints **only for domains you added**. These requests retrieve expiry-related metadata. The Extension does **not** collect or transmit your browsing history or the content of web pages you visit.

If you enable **Webhook alerts (Pro)**, alert messages are sent to the webhook URL **you configure** (e.g. Slack, Discord, Feishu, Telegram).

## Pro subscriptions (ExtensionPay)

Optional Pro features are billed through [ExtensionPay](https://extensionpay.com/). When you subscribe, log in, or restore a purchase, ExtensionPay may process information such as your **email address** and subscription status. Payment card details are handled by ExtensionPay’s payment processor; the Extension does not access your card number.

ExtensionPay’s handling of payment data is governed by ExtensionPay’s own policies.

## Permissions

| Permission | Purpose |
|----------|---------|
| `storage` | Save your domain list and settings locally |
| `alarms` | Run scheduled expiry checks in the background |
| `notifications` | Show desktop alerts for expiring domains/SSL |
| `tabs` | Open ExtensionPay checkout/login pages when you choose to upgrade or manage Pro |
| Host access (`https://*/*`, `http://*/*`) | Query public expiry data for user-added domains only |

## Data sharing

We do not sell, rent, or trade user data. We do not use data for creditworthiness or lending. We do not use data for purposes unrelated to domain and SSL expiry monitoring.

## Data retention

Local data remains until you remove domains, reset the Extension, or uninstall it. Subscription records are managed through ExtensionPay according to their retention practices.

## Children

The Extension is not directed at children under 13.

## Changes

We may update this policy. The “Last updated” date will reflect changes.

## Contact

For privacy questions or support:

- **Email:** art.lanphoon@gmail.com 
- **GitHub Issues:** https://github.com/1900/Domain-SSL-Watcher/issues 

---

*Replace contact URLs/email before publishing.*
