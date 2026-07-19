---
applyTo: "src/main/kotlin/**/*.kt"
---

# 配置与持久化规则

1. 具体数值放入 `ImyvmAnnouceLiteConfig`，不在业务代码中硬编码具体数值。
2. 配置成员变化同步检查 `CONFIG.loadAndSave()` 与 `CONFIG.save()` 调用逻辑。
