# 从 FlClash 迁移到 Bettbox

如果您是 **FlClash** 的用户，您可以无缝切换到 **Bettbox**。Bettbox 在完全继承 FlClash 优秀特性的基础上，针对视觉体验和网络稳定性做了大量深度优化。

---

### 🎨 为什么要迁移到 Bettbox？

相比原版 FlClash，Bettbox 带来了以下增强：

* **功耗优化**：针对 Android 后台保活机制进行了策略调整，降低待机耗电。
* **内核预调优**：预设了更适合手机网络环境的 DNS 与缓存参数。

---

### 🛠️ 迁移步骤

> Bettbox 与 FlClash 的配置格式 100% 兼容。

#### 1. 导出配置
在 **FlClash** 中：
* 前往 <kbd>配置</kbd> 列表。
* 点击您正在使用的配置条目，选择 <kbd>导出为文件</kbd> 或直接复制订阅链接。

#### 2. 安装 Bettbox
* 前往 [这里](https://t.me/appshub_channel) 下载最新 APK。
* **注意**：Bettbox 与 FlClash 包名不同，可以共存，但不能同时开启 VPN 服务。

#### 3. 导入并开启
* 在 **Bettbox** 中点击 <kbd>+</kbd> 号重新导入。
* 建议进入 <kbd>设置</kbd> -> <kbd>路由设置</kbd>，重新确认“应用分流”开关，因为新安装的应用需要重新授予 VPN 权限。

---

### ⚠️ 迁移注意事项

#### 关于包名 (Package Name)
* Bettbox 使用了独立的包名，这意味着如果您在系统设置里针对 FlClash 设置了“电池不优化”或“常驻通知栏”，您需要在 **Bettbox** 上重新设置一次。

#### 关于订阅更新
* 迁移后，请在 Bettbox 中手动执行一次 <kbd>更新订阅</kbd>，以确保获取到最新的节点列表。

#### 关于配置冲突
* 如果您在 FlClash 中开启了 `自动启动`，建议在迁移后关闭它，以免两个应用在开机时竞争 VPN 权限。

---

### ❓ 常见问题

**Q: 为什么我导入了 FlClash 的配置后无法测速？**
A: 请检查 <kbd>更多</kbd> -> <kbd>资源</kbd>，确保 GeoIP 和 GeoSite 数据库已下载完整。

**Q: 原版 FlClash 的功能都在吗？**
A: 不一定，比如IP显示功能Bettbox就没有
