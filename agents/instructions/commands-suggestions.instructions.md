---
applyTo: "src/main/kotlin/**/commands/**/*.kt"
---

# 命令规则

1. 命令在 `CommandRegister.register()` 中注册。
2. 参数在同一文件提取，再调用 application 对应实现。
3. 没有合适调用时，在对应模块实现。
4. 避免只有 ID 可用的命令参数；可读名称存在时提供 Provider 或建议项。
5. 命令参数存在可枚举取值时提供对应 SuggestionProvider 建议项。
