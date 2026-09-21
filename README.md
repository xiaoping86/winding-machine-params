# 绕线机参数设置 / 机卡参数

HBuilder X 可打包的 HTML5+ 安卓应用：绕线机（定子）参数管理、查询、导入导出、样品图片。

**仓库地址：** https://github.com/xiaoping86/winding-machine-params

## 功能

- 型号参数保存 / 查询 / 列表载入
- CSV 参数导入导出（兼容 Excel）
- 样品图片：选图预览，点「保存」写入 `Download/样品图片/型号名.jpg`
- 主题：经典工业 / iOS 扁平
- 界面疏密度、字体大小（持久化）
- 权限：普通 / 管理员 / 超级管理员

## 重要：补齐主程序

若仓库中的 `index.html` 仍是占位页，请将本地完整的 `index.html` 上传覆盖：

1. 打开仓库 → `index.html`
2. 删除或编辑后，使用 **Add file → Upload files** 上传完整文件
3. 提交即可

## 使用方式

### 浏览器

打开 `index.html`。

### HBuilder X 打包安卓

1. 新建 5+ App，放入本仓库文件
2. `manifest.json` 中 `launch_path` 为 `index.html`（小写）
3. 配置存储权限后云打包或真机运行

## 默认密码

| 角色 | 默认密码 |
|------|----------|
| 普通管理员 | `888888` |
| 超级管理员 | 源码中 `SUPER_PASSWORD` |

开源后请自行修改密码。

## 文件

| 文件 | 说明 |
|------|------|
| `index.html` | 主程序 |
| `manifest.json` | HBuilder X 配置 |
| `绕线机参数_2026-08-31.csv` | 示例数据 |
| `LICENSE` | MIT |

## License

MIT
