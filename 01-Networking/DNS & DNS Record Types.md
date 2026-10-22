

## 1. What is DNS?

**DNS (Domain Name System)** converts domain names into IP addresses.

Example: `google.com` → IP address

## 2. How DNS Works

1. User enters `google.com` in browser.
2. Browser checks its DNS cache.
3. If not found, it queries a DNS resolver.
4. Resolver finds the IP address using DNS servers.
5. IP address is returned to the browser.
6. Browser connects to the website's server.

## 3. DNS Record Types

- **A Record:** Domain → IPv4 address.
- **AAAA Record:** Domain → IPv6 address.
- **MX Record:** Specifies mail servers for a domain.
- **TXT Record:** Stores text information; used for verification and email security (SPF/DKIM).
- **CNAME Record:** Makes one domain name an alias of another domain name.

## 4. Examples

- **A:** `example.com` → `192.0.2.1`
- **AAAA:** `example.com` → `2001:db8::1`
- **MX:** `example.com` → `mail.example.com`
- **TXT:** `example.com` → SPF or verification text
- **CNAME:** `www.example.com` → `example.com`
## 5. Cybersecurity Importance

- **A/AAAA:** Identify the IP address a domain resolves to.
- **MX:** Helps identify a domain's email infrastructure.
- **TXT:** Can reveal SPF policies and domain verification details.
- **CNAME:** Can reveal aliases and misconfigured DNS records.