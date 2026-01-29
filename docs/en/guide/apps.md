# 📱 App Split Tunneling

The App Split Tunneling feature allows you to specify which apps should use the proxy and which should bypass it. This is extremely useful for resolving issues such as "banking apps failing to log in," "high game latency," or "slow access to local services."

### 🛠 Steps to Configure

1. **Access Settings**: Tap `Settings` in the bottom navigation bar -> `Routing Settings`.
2. **Find Split Tunneling**: Tap `App Split Tunneling`.
3. **Choose Work Mode**:
    * **Blacklist Mode**: Selected apps will **Connect Directly** (bypass proxy), while all others go through the proxy.
    * **Whitelist Mode**: Only selected apps will go through the proxy, while everything else **Connects Directly**.
4. **Search and Select**: Find the corresponding apps in the list (e.g., WhatsApp, PayPal) and check them.
5. **Apply Settings**: Settings are saved automatically. If the VPN is already running, it is recommended to tap "Restart Service" to ensure the routing table is refreshed.

---

### ⚠️ Important Notes
* **System Apps**: Unless you fully understand how they work, it is NOT recommended to select "System Components." Doing so may cause system update failures or delays in push notifications.
