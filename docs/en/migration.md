# Migrating from FlClash to Bettbox

If you are a **FlClash** user, you can seamlessly switch to **Bettbox**. While inheriting all the excellent features of FlClash, Bettbox introduces extensive optimizations for visual experience and network stability.

---

### 🎨 Why Migrate to Bettbox?

Compared to the original FlClash, Bettbox offers the following enhancements:

* **Power Optimization**: Adjusted background persistence strategies specifically for Android to reduce standby battery drain.
* **Core Pre-tuning**: Pre-configured DNS and cache parameters optimized for mobile network environments.

---

### 🛠️ Migration Steps

> Bettbox is 100% compatible with FlClash configuration formats.

#### 1. Export Configuration
In **FlClash**:
* Go to the <kbd>Configuration</kbd> list.
* Tap your active profile and select <kbd>Export as File</kbd> or simply copy your subscription URL.

#### 2. Install Bettbox
* Download the latest APK [here](https://t.me/appshub_channel).
* **Note**: Bettbox and FlClash use different package names and can coexist, but they cannot run VPN services simultaneously.

#### 3. Import and Activate
* In **Bettbox**, tap the <kbd>+</kbd> icon to re-import your profile.
* It is recommended to go to <kbd>Settings</kbd> -> <kbd>Routing Settings</kbd> to re-confirm your "App Split Tunneling" toggles, as newly installed apps require fresh VPN permission grants.

---

### ⚠️ Migration Notes

#### About Package Name
* Bettbox uses a unique package name. This means if you previously configured "Battery Optimization" or "Persistent Notification" for FlClash in system settings, you will need to apply those settings again for **Bettbox**.

#### Subscription Updates
* After migrating, please manually execute <kbd>Update Subscription</kbd> in Bettbox to ensure you have the latest node list.

#### Configuration Conflicts
* If you have `Auto-start` enabled in FlClash, we recommend disabling it to prevent the two apps from competing for VPN permissions during boot-up.

---

### ❓ FAQ

**Q: Why can't I perform a speed test after importing my FlClash config?**

A: Please go to <kbd>More</kbd> -> <kbd>Resources</kbd> and ensure that the GeoIP and GeoSite databases are fully downloaded.

**Q: Does it retain all the features from the original FlClash?**

A: Over 90% of the original features are present, with several new enhancements and exclusive features added.
