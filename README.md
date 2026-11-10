# Agnes 公开插件仓库

Agnes 的公开插件目录。应用内「插件 → 公开」会读取根目录的 `skills.json` 清单。

## 插件

| 插件 | 作者 | 分类 | 说明 |
| --- | --- | --- | --- |
| [壁纸工坊](plugins/wallpaper-studio) | safe | 界面 | 主界面静态/动态壁纸，多格式、链接、填充与显示参数 |

## 清单格式

`skills.json` 为数组，每项包含：

```json
{
  "name": "显示名称",
  "description": "一句话介绍",
  "version": "1.0.0",
  "icon": "Palette",
  "category": "style",
  "author": "safe",
  "path": "plugins/插件目录"
}
```

插件目录至少包含 `plugin.json` 与 `README.md`。
