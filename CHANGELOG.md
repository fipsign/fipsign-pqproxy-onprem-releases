## [1.0.5] - 2026-07-28

### Initial Release

- Post-quantum TLS reverse proxy with X25519MLKEM768 (NIST FIPS 203)
- Token signing with ML-DSA-65 (NIST FIPS 204)
- Web-based administration dashboard
- Management API
- Offline-verifiable license system
- Multi-domain support with SNI routing
- BYOC (bring your own certificate) for incoming client connections
- Custom/self-signed CA support for backend TLS connections ("Backend speaks TLS")
- Real client IP forwarding (socket, Proxy Protocol, or configurable header)
- Corporate LAN backends supported
- Prometheus metrics endpoint
- Backend health status endpoint and dashboard badge, with webhook alerts for sustained outages and recovery
- Webhook alert notifications for license and certificate expiry
- Certificate expiry monitoring and alerts
- Update notifications in dashboard
- Trial and standard license tiers
- Connection logs and audit trail
