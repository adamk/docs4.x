# DNS

On the left side of web Admin Panel -> NETWORK -> DNS

If you set custom DNS servers, any dns name will be resolved through the DNS servers set here instead of the one obtained from wan, repeater, cellular, hotspot sharing or VPN configuration DNS server.

![dns](https://static.gl-inet.com/docs/router/en/4/interface_guide/dns/dns_page.png){class="glboxshadow"}

**DNS Rebinding Attack Protection:** Turning on this option may cause private DNS lookup failure. If your network has a captive portal please disable this option.

**Override DNS Settings for All Clients:** If enabled, your router will override unencrypted DNS settings for all clients.

**Allow Custom DNS to Override VPN DNS:** If this option is enabled, once you have set custom DNS, packets transmitted through the VPN tunnel will be resolved using the custom DNS override instead of the DNS server settings from the VPN connections.

## DNS Server Settings

There are four modes.

- Automatic, use the gateway of the parent router.

    ![automatic](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/dns_server_settings_automatic.png){class="glboxshadow"}

- Encrypted DNS

    ![encrypted dns](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/dns_server_settings_encrypted_dns.png){class="glboxshadow"}

    **Encrypted Type** has four type, DNS over TLS, DNSCrypt-Proxy, DNS over HTTPS, Oblivious DNS over HTTPS.

    - For DNS over TLS, the DNS Provider has two options, NextDNS and Cloudflare.

    - For DNSCrypt-Proxy, DNS over HTTPS and Oblivious DNS over HTTPS, they can select DNS Server.

        ![dnscrypt-proxy](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/dnscrypt-proxy.png){class="glboxshadow"}

- Manual DNS

    ![manual dns](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/dns_server_settings_manual_dns.png){class="glboxshadow"}

- DNS Proxy

    ![dns proxy](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/dns_server_settings_dns_proxy.png){class="glboxshadow"}

    The router will forward all DNS requests to this DNS server. This might be useful if you are already running another DNS server or Pi-hole in your network.

## Edit Hosts

Requests from clients will be resolved preferentially using the static DNS rules you write in Hosts.

![hosts](https://static.gl-inet.com/docs/router/en/4/tutorials/dns/edit_hosts.png){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
