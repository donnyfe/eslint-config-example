# README

eslint9.x 扁平化配置样例

## 常见问题

### 1. 规则冲突

**规则源：**

1. eslint规则
2. eslint-vue
3. prettier规则
4. IDE扩展设置的规则

> 注： IDE扩展设置以 VSCode 为例，快捷键 `Ctrl + ,` / `Command + ,` 唤出设置面板，通过输入框输入`Format` 关键词可见扩展设置。

**规则配置所在：**

1. editorconfig
2. eslint.config.js
3. prettierrc.json
4. vscode设置中的工作区，即项目根目录中常见的 `.vscode/setting.json`
5. vscode设置中的用户配置 `setting.json`

**规则配置原则：**

1. 尽量统一一致的格式化程序，避免出现多个格式化程序作用同一个文件产生多次格式化的效果
2. 尽量避免使用多个规则源中相同作用的规则以致互相影响
