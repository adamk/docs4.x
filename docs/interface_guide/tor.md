# Tor

Tor (derived from **The Onion Router**) is a free and open-source software for enabling anonymous communication. It helps users to explore the internet with privacy. [Learn More about the Tor](https://www.torproject.org/){target="_blank"}.

**Note**: This feature is currently in beta, and may be problematic in some countries. When Tor is enabled, the following features will not work properly: 

  - VPN
  - DNS
  - IPv6
  - ADGuard Home.

## Supported models

| Router Model                   | Support   |
| :----------------------------- | :-------: |
| GL-BE9300 (Flint 3)            | √         |
| GL-BE3600 (Slate 7)            | √         |
| GL-X2000 (Spitz Plus)          | -         |
| GL-B3000 (Marble)              | √         |
| GL-MT6000 (Flint2 )            | √         |
| GL-X3000 (Spitz AX)            | √         |
| GL-MT3000 (Beryl AX)           | √         |
| GL-AXT1800 (Slate AX)          | √         |
| GL-A1300 (Slate Plus)          | √         |
| GL-MT2500/GL-MT2500A (Brume 2) | √         |
| GL-SFT1200 (Opal)              | *         |
| GL-S1300 (Convexa-S)           | √         |
| GL-MT1300 (Beryl)              | *         |
| GL-AX1800 (Flint)              | √         |
| GL-AR750S (Slate)              | -         |
| GL-AR750 (Creta)               | -         |
| GL-AR300M Series (Shadow)      | -         |
| GL-MT300N-V2 (Mango)           | -         |
| GL-XE300 (Puli)                | -         |
| GL-E750 (Mudi)                 | *         |
| GL-X750 (Spitz)                | -         |
| GL-B1300 (Convexa-B)           | -         |
| GL-AP1300 (Cirrus)             | √         |
| GL-X300B (Collie)              | -         |
| GL-MV1000/GL-MV1000W (Brume)   | √         |

*Some models do not have built-in Tor supported, but users can manually use plug-in the re-install the Tor. Click [here](#manual-install) for details.

## Setup

On the left side of web Admin Panel -> VPN -> Tor.

Click the toggle switch to enable it, then click **Apply** button. You can also choose a **Custom Exit Nodes**.

![gl.inet Tor](https://static.gl-inet.com/docs/router/en/4/tutorials/tor/tor.png){class="glboxshadow"}

Wait a while, depending on your network, and it will show connected.

![gl.inet Tor connected](https://static.gl-inet.com/docs/router/en/4/tutorials/tor/tor_connected.png){class="glboxshadow"}

## Manual install

*Some models can manually use plug-in the re-install the Tor, but it may affect the CPU load and making the system response slower.

On the left side of web Admin Panel -> APPLICATIONS -> Plug-ins.

Search **gl-sdk4-ui-torview**, and install.

![torview](https://static.gl-inet.com/docs/router/en/4/tutorials/tor/torview.jpg){class="glboxshadow"}

![torpage](https://static.gl-inet.com/docs/router/en/4/tutorials/tor/torpage.jpg){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"} or [Contact us](https://www.gl-inet.com/contacts/){target="_blank"}.
