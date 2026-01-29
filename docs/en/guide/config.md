# 📥 Subscription Guide

Managing subscriptions in Bettbox is highly consistent with FlClash. Whether you are using a subscription URL or a local file, you can get started quickly.

---

### 1. Auto-Sync (Import from URL)

This is the most recommended method as it supports automatic node updates.

**Steps:**

1.  **Copy Link**: Obtain a Clash subscription URL from your service provider.
2.  **Open Configuration**: Go to the <kbd>Configuration</kbd> page in the bottom navigation bar.
3.  **Add Profile**: Tap the <kbd>+</kbd> button in the bottom right and select <kbd>Import from URL</kbd>.
4.  **Save Config**: Enter a name, paste the URL, and set the update interval.
5.  **Activate**: Tap the configuration card in the list to ensure it is selected.

---

### 2. Manual Import (Import from File)

Use this method if you have already downloaded a configuration file in `.yaml` format.

**Steps:**

1.  Tap the <kbd>+</kbd> button and select <kbd>Import from File</kbd>.
2.  In the system file picker, locate and select your configuration file.
3.  Once imported, the file will be stored locally within the Bettbox directory.

---

### 3. QR Code Import

**Steps:**
1. Go to the <kbd>Configuration</kbd> page in the bottom navigation bar.
2. Tap the <kbd>+</kbd> button and select <kbd>Scan QR Code</kbd>.
3. **Two Recognition Methods**:
    * **Direct Scan**: Point your camera at a subscription QR code on a computer screen or other device.
    * **Album Recognition**: If the QR code is saved on your phone, tap the <kbd>Image Icon</kbd> on the scanning screen to import from your gallery.
4. Confirm the name after recognition and tap <kbd>Save</kbd>.

---

### 4. Advanced: Editing Configuration Files

Bettbox features a built-in lightweight YAML editor, allowing you to fine-tune configurations directly.

* **How to**: In the configuration list, tap the **More (three dots)** on the card -> <kbd>Edit File</kbd>.
* **Use Cases**: Manually adding DNS rules, modifying routing modes, or adjusting custom policy groups.

---

### ⚠️ Troubleshooting

| Symptom | Possible Cause | Solution |
| :--- | :--- | :--- |
| **Parsing Failed** | URL is not in standard Clash format | Use a subscription converter before importing. |
| **Update Timeout** | Cannot connect to the sub-server | Check your network or try changing your DNS. |
| **0 Nodes Displayed** | No valid Proxy fields in config | Check if the subscription has expired or contact your provider. |

---

### 💡 Compatibility with FlClash

Since Bettbox is developed based on FlClash, at the configuration level:
* **100% Compatible**: Any configuration that runs on FlClash can be used directly in Bettbox.
* **Identical Logic**: The logic for importing, latency testing, and switching nodes is exactly the same—zero migration cost.
* **Better Performance**: Bettbox has underlying optimizations for loading large configuration files.

---

[Back to Feature Guide](en/guide/README.md) | [App Split Tunneling](en/guide/apps.md)
