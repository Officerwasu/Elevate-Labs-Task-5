# Task 5 - Network Traffic Analysis with Wireshark

## Files
- `My capture.pcapng` – The packet capture file.
- `Screenshots` – Screenshots from Wireshark during the capture.

## Protocols Observed

1. **TCP** – Used for reliable transport, forms the basis for many protocols including HTTP and HTTPS.
2. **UDP** – Lightweight, connectionless protocol, often used for DNS.
3. **DNS** – Domain Name System, translates human-readable domain names to IP addresses.
4. **HTTP** – Used for web page requests and responses.
5. **TLSv1.3** – Secure version of TLS used for encrypted web traffic (HTTPS).

## Observations

- Multiple TCP handshakes were captured indicating successful connections.
- DNS queries for sites like `google.com` and `youtube.com` were observed.
- HTTP packets show clear-text data exchange (before HTTPS is established).
- TLS traffic suggests secure browsing sessions (likely HTTPS to Google).

## Tools Used

- Wireshark for live packet capture and protocol filtering.

## Learning Outcome

This task strengthened my skills in network protocol identification, packet filtering, and understanding encrypted vs. unencrypted communication in real-time traffic.

