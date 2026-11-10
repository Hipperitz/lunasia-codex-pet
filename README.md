# Lunasia Codex Pet · 露尼西亚

适用于 Codex 桌面应用的露尼西亚（Lunasia）自定义宠物素材包。

![露尼西亚待机动画](docs/idle.gif)

## 下载

- [下载宠物包 ZIP](https://github.com/Hipperitz/lunasia-codex-pet/releases/latest/download/Lunasia-Codex-Pet.zip)
- [查看发布版本](https://github.com/Hipperitz/lunasia-codex-pet/releases)
- [ZIP 校验值](SHA256SUMS.txt)

ZIP 内含 `lunasia/pet.json`、`lunasia/spritesheet.webp` 和中文安装说明。该包需要支持自定义宠物的 Codex 桌面应用。

## Windows 安装

1. 下载并解压 `Lunasia-Codex-Pet.zip`。
2. 完全退出 Codex 应用。
3. 将解压得到的整个 `lunasia` 文件夹复制到 `%USERPROFILE%\.codex\pets\`。
4. 重新打开 Codex，在宠物选择界面选择 **Lunasia**。

安装后的目录应为：

```text
%USERPROFILE%\.codex\pets\
└─ lunasia\
   ├─ pet.json
   └─ spritesheet.webp
```

若已有同名 `lunasia` 文件夹，请先备份再替换。若宠物未出现在列表中，检查路径是否多套了一层文件夹，再完全退出并重启 Codex。其他操作系统或后续 Codex 版本的兼容性尚未验证。

## 文件

| 文件 | 用途 |
| --- | --- |
| `lunasia/pet.json` | 宠物标识、名称及图集路径 |
| `lunasia/spritesheet.webp` | 透明背景动画图集 |
| `Lunasia-Codex-Pet.zip` | 可直接下载的完整安装包 |
| `docs/idle.gif` | 待机动画预览 |

## 声明

这是以《少女前线》角色露尼西亚为主题的非官方同人作品，与 OpenAI、Codex 或《少女前线》官方无关联，未获其背书。角色及相关标识的权利归原权利人所有；本仓库不授予第三方角色或图像的商业使用权。
