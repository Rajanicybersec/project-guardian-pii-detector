# project-guardian-pii-detector
This project implements a real-time PII (Personally Identifiable Information) detector and redactor designed for Project Guardian 2.0
The solution protects against data leakage and fraud by scanning incoming data streams (CSV/JSON logs) for sensitive information such as phone numbers, Aadhaar numbers, passport numbers, UPI IDs, names, emails, addresses, IP/device IDs and applying masking/redaction rules.

The output clearly labels whether each record contains PII (is_pii) and ensures that no raw PII propagates downstream.

This system directly addresses risks from fraudulent orders, refund scams, OTP thefts, and log leaks caused by unmonitored endpoints and external API integrations.
