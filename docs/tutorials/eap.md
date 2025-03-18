# How to Connect to an Extensible Authentication Protocol (EAP) Network

## Introduction

You can connect GL.iNet routers to EAP (Extensible Authentication Protocol) Wi-Fi network which requires username and password authentication on GL.iNet routers.

This guide will introduce two ways to connect GL.iNet routers to an EAP Wi-Fi network: via Admin Panel and via LuCI.

## Supported models

| Router Model                   | Support   |
| :----------------------------- | :-------: |
| GL-BE3600 (Slate 7)            | √         |
| GL-X2000 (Spitz Plus)          | √         |
| GL-B3000 (Marble)              | √         |
| GL-MT6000 (Flint 2)            | ●         |
| GL-MT3000 (Beryl AX)           | ●         |
| GL-X3000 (Spitz AX)            | -         |
| GL-XE3000 (Puli AX)            | -         |
| GL-AXT1800 (Slate AX)          | √         |
| GL-A1300 (Slate Plus)          | √         |
| GL-MT2500/GL-MT2500A (Brume 2) | -         |
| GL-SFT1200 (Opal)              | -         |
| GL-MT1300 (Beryl)              | -         |
| GL-AX1800 (Flint)              | √         |
| GL-AR750S (Slate)              | √         |
| GL-AR750 (Creta)               | √         |
| GL-XE300 (Puli)                | √         |
| GL-E750/GL-E750V2 (Mudi)       | √         |
| GL-X750/GL-X750V2 (Spitz)      | √         |
| GL-B1300 (Convexa-B)           | √         |
| GL-AP1300 (Cirrus)             | √         |
| GL-X300B (Collie)              | √         |
| GL-AR300M Series (Shadow)      | √         |
| GL-MT300N-V2 (Mango)           | -         |

!!! note

    The models marked with ● do not support connecting to EAP networks when being installed the default firmware, but we provide native OpenWrt 24 firmware for these models which can be installed to support connecting to EAP networks. Here is the [link](https://dl.gl-inet.com/){target="_blank"} of download center.

## Connect via web Admin Panel

1. Visit the web Admin Panel, go to INTERNET -> Repeater section, click **Connect**.

    ![repeater connect](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/repeater_connect.png){class="glboxshadow"}

    It will scan the available networks. You can find and select the EAP SSID to connect directly.

    ![scan available networks](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/scan_available_wifi.png){class="glboxshadow"}

    Or click **Join Other Network** in the upper right, manually join the EAP network.

    ![join other network](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/join_other_network.png){class="glboxshadow"}

2. Input the **SSID**.

    ![input ssid](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/ssid.png){class="glboxshadow"}

3. Select **Security** as WPA/WPA2/WPA3 Enterprise.

    ![select security](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/select_security.jpg){class="glboxshadow"}

4. Input the **Username** and **Password**. Then click **Apply** to connect.

    ![input username and Password](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/username_and_password.jpg){class="glboxshadow"}

## Connect via LuCI

GL-iNet web Admin Panel only supports few EAP types for now. You may need to connect via LuCI page in most situations.

1. Log in to [LuCI](https://docs.gl-inet.com/router/en/4/faq/what_is_luci/) page.

2. In the LuCI page, go to Network -> Wireless.

    ![wireless](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/luci_network_wireless.png){class="glboxshadow"}

3. Click **Scan** on 2.4G section or 5G section.

    ![scan](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/luci_wireless_scan.png){class="glboxshadow"}

4. Join the network you want.

    ![join network](https://static.gl-inet.com/docs/router/en/4/tutorials/eap/luci_join_network.png){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.












