# Clients

On the left side of web Admin Panel -> CLIENTS

The Clients page displays information about connected devices, including device name, connection type, IP address, MAC address, speed, and traffic.

## Modify Client Name and Type

If you want to modify name and type of a device, please click the three dots icon in the Action column, in the menu that pops up, click **Modify** item.

![clients page, three dots](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_three_dots.png){class="glboxshadow"}

![edit client device](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/edit_client_device.png){class="glboxshadow"}

## MAC Address

Many devices will use randomized MAC address, if the randomized MAC address is used, there will be a prompt.

![random mac prompt](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/randomized_mac_address.png){class="glboxshadow"}

**Note**: The rule here is that if the second character of the MAC address is 2, 6, A or E(Ignore case), then it is considered a randomized MAC address. However, some devices may use a different rule to generate a randomized MAC address, so it may not be accurate.

## Blocklist

Enable **Block** toggle to block client device. The access control rule is Blocklist by default, you can switch it to Allowlist from the top if needed.

![blocklist](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/blocklist.jpg){class="glboxshadow"}

![clients page](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/blocklist_whitelist.png){class="glboxshadow"}

**Blacklist**: Devices with MAC addresses on the prohibited list are not allowed to connect to this router.

**Allowlist**: Only devices with specific MAC addresses are allowed to connect, suitable for IoT devices and enterprise network management.

Starting from firmware 4.4.x, you can upload a block list in excel form or input Mac addresses manually to creat a **Block List**.

You can either import a list from a CSV file at **(1)** or input the Mac Address one by one at **(2)**.

![inputblock](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/inputblock.jpg){class="glboxshadow gl-80-desktop"}

![importcsv](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/importcsv.jpg){class="glboxshadow gl-80-desktop"}

![dragcsv](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/dragcsv.jpg){class="glboxshadow gl-80-desktop"}

![loadcsv](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/loadcsv.jpg){class="glboxshadow"}

![applycsv](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/applycsv.jpg){class="glboxshadow"}

**Note**: Blocking client is based on the MAC address of the device, so if the blocked device use a different MAC address next time, it can still connect to router.

## Speed

![clients page](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_speed.png){class="glboxshadow"}

The speed here is the average speed over 3 minutes.

- Open the current page for 10 seconds, the average speed of the last 10 seconds is displayed.
- Open the current page for 30 seconds, the average speed of the last 30 seconds is displayed.
- Open the current page for 60 seconds, the average speed of the last 60 seconds is displayed.
- Open current page for 3 minutes, the average rate of the last 3 minutes is displayed.
- Open current page for 10 minutes, the average rate of the last 3 minutes is displayed.

## Sort

The current sort type is displayed in the upper right corner, and you can switch to other sort types.

The default sort type:

- The self device is alway s on top
- In online client sector, the later the device is connected, the higher it is on top.

![clients page](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_sort.png){class="glboxshadow"}

## Limiting Speed

If you want to limit the speed of a device, please click the three dots icon in the Action column, in the menu that pops up, click **Limit Speed** item.

![clients page, three dots](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_three_dots.png){class="glboxshadow"}

![clients page](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_limit_speed_settings.png){class="glboxshadow"}

If a client has applied speed limitation, its up arrow and down arrow of speed will turn yellow.

![clients page](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/clients_limit_speed.png){class="glboxshadow"}

Click the three dots icon in the Action column to disable limiting.

## Client Details

If you need to view the IPv6 address of the client device. Or if the list does not show the column you need to view because you are browsing with a small-screen client device. Please click the three dots icon in the action column and then click the **View Details** item in the pop-up menu.

![view detail](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/view_detail.png){class="glboxshadow"}

After that, you can see all the information about the client device in the opened subpage, including all IPv6 addresses of the device.

![client detail](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/client_detail.png){class="glboxshadow"}

## Remove Offline Clients

In the offline clients sector, you can **Delete All** offline clients. If you want to remove specific client, please click the three dots icon in the action column, in the menu that pops up, click **Remove Client** item.

![remove clients](https://static.gl-inet.com/docs/router/en/4/interface_guide/clients/remove_client.png){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"}.
