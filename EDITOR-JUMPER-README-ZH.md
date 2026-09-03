# Editor Jumper 中文说明

Editor Jumper 是面向 DevEco Studio、IntelliJ IDEA、Android Studio 及其他 IntelliJ Platform IDE 的开发效率插件。

选中代码后，在编辑器右键菜单中点击“跳转到：当前工具”，即可将项目、文件和选区起始位置交给 Cursor、Visual Studio Code、OpenAI Codex CLI、Claude CLI、Android Studio、Sublime Text 或 Zed。

插件会自动探测 PATH、Homebrew、用户目录和常见应用安装路径，也支持在 `Settings > Tools > Editor Jumper` 中自定义 CLI、参数模板、默认目标和界面语言。默认使用中文，也可以切换为英文。

参数模板支持 `{file}`、`{project}`、`{line}`、`{column}` 和 `{selection}` 变量。工具已经运行并打开项目时，插件会尽可能复用现有窗口。
