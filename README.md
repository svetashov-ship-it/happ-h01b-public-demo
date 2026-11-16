# Happ H-01b — public demonstration subscription

**DEMO ONLY. NOT A FUNCTIONING VPN.**

This public repository contains exactly two *fictitious* VLESS/TCP/TLS server entries for testing HTTPS subscription import in Happ iOS 6.4.0.

- File: [standard-list-demo.txt](standard-list-demo.txt)
- Addresses: RFC 5737 documentation networks `192.0.2.10` and `198.51.100.20`.
- UUIDs and SNI examples are fictitious.
- **Do not connect to either demo server.** They cannot provide VPN service.
- No real subscription credentials, VPN server addresses, secrets, client logs, or private project documents belong in this repository.

Test the import through **Happ → + → URL подписки**. It should show two `H01B-DEMO-*-NO-CONNECT` nodes in a separate group. This is a planned client-side check, not a verified claim.

The public host file is intentionally disposable. For production VPN subscriptions use a separate access-controlled service and maintain the private architecture repository separately.
