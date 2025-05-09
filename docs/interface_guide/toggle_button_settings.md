# Toggle Button Settings

Some models have a toggle button, and you can customize what this button does in the web admin panel.

## Supported models

| Router Model                   | Support   |
| :----------------------------- | :-------: |
| GL-BE3600 (Slate 7)            | √         |
| GL-MT3000 (Beryl AX)           | √         |
| GL-AXT1800 (Slate AX)          | √         |
| GL-MT1300 (Beryl)              | √         |
| GL-A1300 (Slate Plus)          | √         |
| GL-SFT1200 (Opal)              | √         |
| GL-MT300N-V2 (Mango)           | √         |
| GL-AR300M Series (Shadow)      | √         |
| GL-AR750S (Slate)              | √         |
| GL-AR750 (Creta)               | √         |

On the left side of web Admin Panel -> SYSTEM -> Toggle Button Settings.

![toggle button settings](https://static.gl-inet.com/docs/router/en/4/interface_guide/toggle_button_settings/toggle_button_settings.jpg){class="glboxshadow"}

Prior to firmware v4.8, there are four options, allowing users to customize the toggle button's functionality. 

- No Function
- AdGuard Home
- OpenVPN Client
- Tor
- WireGuard Client

Starting from v4.8, more options are introduced: Repeater, WiFi, and LED, and users can tailor the toggle button according to their needs.

- No Function
- Repeater
- Wi-Fi (Main/Guest Wi-Fi)
- VPN
- Tor 
- AdGuard Home 
- LED

![toggle button settings 4.8](https://static.gl-inet.com/docs/router/en/4/interface_guide/toggle_button_settings/toggle_button_settings_4.8.png){class="glboxshadow"}

When applying settings, you can decide whether or not to immediately enable/disable your selected feature based on the toggle switch's on/off(left/right) position.

**Note**: After a device reboot, the system will automatically apply the feature state according to the toggle switch position.

For example, if you configure the WireGuard Client to be controlled by the toggle switch: When the switch is LEFT (ON), the WireGuard Client starts automatically. When the switch is RIGHT (OFF), the WireGuard Client remains disabled.

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"} or [Contact us](https://www.gl-inet.com/contacts/){target="_blank"}.
