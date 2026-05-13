---
title: Configuring DNS
---

Pointing your domain to your server.

## Cloudflare DNS
We recommend using **Cloudflare** for DNS management, even if you bought your domain elsewhere.
*   **Why**: It provides free SSL, DDoS protection, and fast propagation.

### How to set it up
1.  **Sign up** for Cloudflare.
2.  **Add a Site**: Enter your domain name.
3.  **Select Free Plan**.
4.  **Update Nameservers**: Go to your domain registrar (where you bought the domain) and change the nameservers to the ones provided by Cloudflare.
5.  **Manage DNS Records**: Add `A` records (IP address) or `CNAME` records (alias) in the Cloudflare dashboard to point to your host (Vercel, Netlify, etc.).
