# GitHub 个人主页使用说明

## 文件用途

- `README.md`：个人主页介绍。
- `assets/research-banner.svg`：静态横幅，不依赖外部图片服务。
- `docs/SETUP.md`：本说明，可选上传，不会直接显示在个人主页。

## 手动上传

1. 登录 `xianjin-lin`，访问 [创建仓库](https://github.com/new)。
2. 仓库名填写 **`xianjin-lin`**，设为 **Public**，启用 README 后创建。
3. 将本文件夹内的 `README.md` 和 `assets/` 上传到仓库根目录，替换默认 README。
4. 提交后访问 [个人主页](https://github.com/xianjin-lin)，确认介绍和横幅正常显示。

仓库地址应为 `https://github.com/xianjin-lin/xianjin-lin`，不要加 `profile` 等后缀。
本功能不需要开启 GitHub Pages，也不需要配置 Actions。

## 日常维护

- 修改介绍、研究方向及项目：编辑根目录的 `README.md`。
- 增加项目：沿用 Selected Projects 的格式，填入真实公开仓库链接。
- 修改横幅文字和颜色：编辑 `assets/research-banner.svg`，保留文件路径即可。
- 首页重点使用 `<strong>文字</strong>`，避免中英文标点附近的加粗解析问题。
- 研究方向按兴趣表述；论文、成果和项目链接应在公开后再补充。
- 默认没有访问量统计、动态徽章或第三方统计卡片。

可在个人主页的 **Customize your pins** 中手动置顶两个代表项目：
`QHU-Cover-Letter-Template` 和 `budao-lepao-notes`。

参考：[GitHub 官方 Profile README 说明](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)。
