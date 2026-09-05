# Apple Region Rules (apple-2)

Apple 分地区规则集合，支持多个国家和地区的代理配置。

## 📋 规则列表

### 🚀 推荐使用 CDN 加速版本（速度快且稳定）

| 地区 | 规则文件 | CDN 链接 | 原始链接 |
|------|--------|--------|--------|
| 🌐 **直连** | DIRECT.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/DIRECT.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/DIRECT.list) |
| 🇭🇰 **香港** | HK.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/HK.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/HK.list) |
| 🇭🇰 **香港增强** | HKA.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/HKA.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/HKA.list) |
| 🇯🇵 **日本** | JP.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/JP.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/JP.list) |
| 🇴🇴 **其他** | OK.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/OK.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/OK.list) |
| 🇸🇬 **新加坡** | SG.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/SG.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/SG.list) |
| 🇸🇬 **新加坡增强** | SGA.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/SGA.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/SGA.list) |
| 🇹🇼 **台湾** | TW.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/TW.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/TW.list) |
| 🇺🇸 **美国** | US.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/US.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/US.list) |
| 🇺🇸 **美国增强** | USA.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/USA.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/USA.list) |
| 🔄 **代理** | proxy.list | https://cdn.jsdelivr.net/gh/chenchu840-jpg/apple-2@main/proxy.list | [GitHub](https://raw.githubusercontent.com/chenchu840-jpg/apple-2/main/proxy.list) |

## ⚡ CDN 加速优势

- **🚀 速度快** - 全球 CDN 节点，自动选择最近服务器
- **🔒 稳定性高** - 不依赖 GitHub 服务器，可靠性强
- **🌍 全球适配** - 适合各地区用户，无地理限制
- **💯 完全免费** - jsDelivr 免费服务，无任何成本

## 📝 使用方法

### 在 Shadowrocket 中导入规则

1. 打开 Shadowrocket 应用
2. 选择 "配置" → "规则" → "+"
3. 复制上表中的 **CDN 链接**
4. 粘贴到 URL 输入框
5. 点击确认下载

### 地区选择建议

| 场景 | 推荐规则 |
|------|--------|
| 📍 **在中国大陆** | DIRECT.list + HK.list 或 SG.list |
| 📍 **在香港** | HKA.list + DIRECT.list |
| 📍 **在日本** | JP.list + DIRECT.list |
| 📍 **在新加坡** | SGA.list + DIRECT.list |
| 📍 **在台湾** | TW.list + DIRECT.list |
| 📍 **在美国** | USA.list + DIRECT.list |
| 🌐 **跨地区使用** | HKA.list + SGA.list + USA.list |

## 🔄 更新方式

所有规则文件都会定期更新，Shadowrocket 会自动检测更新。

## 📄 说明

- **DIRECT.list** - 直连规则，适合本地流量
- **HKA / SGA / USA** - "A" 后缀表示增强版本，包含更多节点和优化规则
- **proxy.list** - 代理配置规则

---

**最后更新**: 2026-09-05
