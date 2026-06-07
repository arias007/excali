# excali

好魔改的 excalidrae。

这是基于 Obsidian Excalidraw 插件魔改的版本，重点改成更适合笔记、批注和交互式 Markdown 图片涂鸦的使用方式。

## 主要魔改

- 紧凑顶部工具栏，把常用按钮集中到上方。
- 右侧和底部工具按钮合并到同一工具栏区域。
- 撤销、重做等常用按钮靠左放置。
- 元素复制、删除、编辑等操作菜单尽量贴近被选中的元素显示。
- 画笔工具支持二级笔位。
- 二级笔横排显示，点 `+` 可新增更多笔。
- 每支笔独立记住颜色、粗细、样式等画图配置。
- 二级笔图标会跟随当前配置实时变化。
- 长按二级笔可删除笔位。
- 切到笔工具时显示二级笔，切到其他工具时隐藏。
- 优化交互式 Markdown/图片导入后的涂鸦层级，涂鸦不会跑到图片下面。
- 修复含图片 Markdown 导入后的显示位置和自适应问题。
- 优化导入内容的大框显示，让图片和批注区域更适合笔记使用。

## 安装说明

当前插件 ID 仍保留为：

```text
obsidian-excalidraw-plugin
```

这样可以继续覆盖安装到原 Excalidraw 插件目录，例如：

```text
E:/note/.obsidian/plugins/obsidian-excalidraw-plugin
```

如果手动安装，可以把构建后的插件文件放入 Obsidian 库的插件目录：

```text
<你的 Vault>/.obsidian/plugins/obsidian-excalidraw-plugin
```

然后在 Obsidian 设置里启用该插件。

## 开发与打包

安装依赖：

```powershell
npm install
```

打包：

```powershell
npm run build
```

主要输出文件通常包括：

```text
main.js
manifest.json
styles.css
```

## 注意

- 这是个人魔改版本，不是原作者官方版本。
- 为了兼容当前 Obsidian 安装路径，插件 ID 暂未改名。
- 如果已经安装官方 Excalidraw 插件，覆盖安装前请先备份原插件目录。

## 来源

基于原项目修改：

https://github.com/zsviczian/obsidian-excalidraw-plugin

原项目 License 保留，详见 `LICENSE`。
