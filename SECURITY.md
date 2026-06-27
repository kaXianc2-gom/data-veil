# 安全策略 / Security Policy

## 支持的版本

| 版本 | 支持状态 |
|------|----------|
| v1.5.x | ✅ 活跃支持 |
| < v1.5.0 | ❌ 不支持 |

## 报告漏洞

如果你发现安全漏洞，**请勿公开提交 Issue**。

请通过 GitHub Security Advisory 私下报告：
1. 进入 [Security](https://github.com/kaXianc2-gom/data-veil/security) 标签
2. 点击 "Report a vulnerability"
3. 描述漏洞详情和复现步骤

我会在 48 小时内确认并给出处理方案。

## 隐私承诺

DataVeil 的核心设计原则是所有数据处理均在浏览器本地完成：
- **不上传任何数据到服务器** — 文件解析、PII 检测、脱敏处理均在浏览器内存中完成
- **不使用第三方遥测/分析** — 无 Google Analytics、无 Sentry、无任何追踪
- **无持久化服务端存储** — 关闭浏览器后所有数据自动清除

## 依赖安全

DataVeil 内联了 SheetJS，无运行时 CDN 依赖。如发现依赖库漏洞，请以上述方式报告。
