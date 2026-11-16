# Happ — isolated public test fixtures

**TEST DATA ONLY. DO NOT CONNECT.** The files contain two deliberately nonworking VLESS endpoints in RFC 5737 TEST-NET address space, with fictional UUIDs. No real VPN configuration or personal details are published.

| File | Purpose | Status |
| --- | --- | --- |
| [standard-list-demo.txt](standard-list-demo.txt) | H-01b: two dummy nodes; verify HTTP import and manual subscription refresh | Verified on Happ iOS 6.4.0; second dummy label was updated |
| [routing-profile-demo.txt](routing-profile-demo.txt) | H-01c: separate two-dummy-node feed with a `happ://routing/add/{base64}` provider routing profile | **NOT YET IMPORTED; parser/runtime compatibility UNVERIFIED** |

The H-01c embedded profile is named `H01C-DEMO-RULES-NO-CONNECT`. Its only example destination patterns use the reserved `.invalid` domain: `domain:example.invalid` as DIRECT and `domain:blocked-example.invalid` as BLOCK. No real websites are used as demo-specific routing targets. This profile is not meant for production use and must never be selected for traffic tests.

**Never select or connect to any H01B/H01C demo node.** Existing personal VPN configurations and subscriptions should not be changed while studying these fixture files.

These files are intentionally public for testing a mobile HTTPS subscription client. A real VPN subscription must be delivered through a separate controlled and revocable HTTPS service; keep real IP addresses, UUIDs, credentials and private project documents out of public repositories.

Official Happ routing documentation: https://github.com/HappDev/happ_su/blob/main/dev-docs/routing.md
