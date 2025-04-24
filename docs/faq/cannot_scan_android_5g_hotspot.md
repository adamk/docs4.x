# Cannot Scan Android 5G Hotspot

If you cannot scan your android phone 5G hotspot, it may be related to the WiFi country code.

Some Android phones set their 5G hotspot to a US channel by default. If your GL.iNet router wasn't originally purchased in the US, you might experience this issue. You can change your GL.iNet router's WiFi country code in LuCI page as per the steps below.

**Step 1. Login LuCI**

Login your GL.iNet router, at the left side bar choose **SYSTEM -> Advanced Settings -> Go to LuCI**, login with the same admin password.

**Step 2. Edit WiFi settings**

Go to **Network -> Wireless** select 5G WiFi and edit, If you are using GL-MT3000, **Network -> MTK WiFi**.

![5gwifi](https://static.gl-inet.com/docs/router/en/4/tutorials/5ghotspot/5gwifi.jpg){class="glboxshadow"}

![mtkwifi](https://static.gl-inet.com/docs/router/en/4/tutorials/5ghotspot/mtkwifi.jpg){class="glboxshadow"}

**Step 3. Select U.S. as country code**

Select U.S. for your 5G WiFi.

![5gus](https://static.gl-inet.com/docs/router/en/4/tutorials/5ghotspot/5gus.jpg){class="glboxshadow"}

Remember **Save & Apply** before logout.

![saveapply](https://static.gl-inet.com/docs/router/en/4/tutorials/5ghotspot/saveapply.jpg){class="glboxshadow"}

---

Still have questions? Visit our [Community Forum](https://forum.gl-inet.com){target="_blank"} or [Contact us](https://www.gl-inet.com/contacts/){target="_blank"}.