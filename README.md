# PQ-Proxy On-Premise — Releases

Official releases of PQ-Proxy On-Premise, a post-quantum reverse proxy
(X25519MLKEM768 / NIST FIPS 203) for self-hosted deployment.

## Getting Started

### 1. Request a license

- **Trial (14 days, 1 domain):** [onprem.fipsign.dev](https://onprem.fipsign.dev)
- **Standard (365 days, up to 10 domains):** [onprem.fipsign.dev/purchase](https://onprem.fipsign.dev/purchase)

You will receive an email with a download link for your `license.pqp` file.

### 2. Copy your license to the server

```bash
scp license.pqp root@YOUR_SERVER_IP:/root/
```

### 3. Run the installer

```bash
curl -fsSL https://proxyonprem.fipsign.dev/install -o install.sh && bash install.sh
```

### 4. Access your dashboard

```
http://YOUR_SERVER_IP:9090/dashboard
```

---

## Useful Commands

**Reconfigure:**
```bash
bash install.sh --reconfigure
```

**Update to latest version:**
```bash
docker compose pull && docker compose up -d
```

---

## License Tiers

| Feature | Trial | Standard |
|---------|-------|----------|
| Duration | 14 days | 365 days |
| Domains | 1 | up to 10 |
| All features | ✓ | ✓ |

---

## Documentation

Full documentation: [fipsign.dev/proxy-guide#onprem](https://fipsign.dev/proxy-guide#onprem)

## Support

[support@fipsign.dev](mailto:support@fipsign.dev)
