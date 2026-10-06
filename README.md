# 旅行照片画法 Skill

把旅行照片改成像素游戏、积木微缩、手绘动画或拼豆风格。四套自制 Skill 都包含可复制的详细中文 Prompt；使用时需要支持上传照片并编辑参考图的图像工具。

整理：美式牛马指挥官 · 2026-10-06

| 画法 | Skill 文件夹 | 单独下载 |
| --- | --- | --- |
| 像素游戏 | [travel-photo-pixel](travel-photo-pixel/SKILL.md) | [像素 Skill ZIP](downloads/travel-photo-pixel.zip) |
| 积木微缩 | [travel-photo-bricks](travel-photo-bricks/SKILL.md) | [积木 Skill ZIP](downloads/travel-photo-bricks.zip) |
| 手绘动画 | [travel-photo-animation](travel-photo-animation/SKILL.md) | [动画 Skill ZIP](downloads/travel-photo-animation.zip) |
| 拼豆风格 | [travel-photo-beads](travel-photo-beads/SKILL.md) | [拼豆 Skill ZIP](downloads/travel-photo-beads.zip) |

## 用 Skill

1. 在仓库页面点 **Code → Download ZIP**，下载并解压。只要一种画法，也可以点上表的单独 ZIP，打开文件页面后选择下载原始文件。
2. 把需要的完整文件夹复制到 `~/.codex/skills/`。保留文件夹内的 `SKILL.md` 和 `references`，不要只复制一个 Markdown 文件。
3. 打开新的 Codex 对话，上传要处理的照片，然后发送：

```text
使用 $travel-photo-pixel，把这张旅行照片做成像素游戏风。
保留原图比例、主景位置和人物数量，不要新增景点或角色。
```

把 Skill 名称换成上表中其他名称，就能选择其他画法。没有图像编辑工具的环境只能输出提示词，无法直接生成成品。

## 不装 Skill，直接用 Prompt

上传自己的照片，复制对应的中文完整模板：

- [像素游戏 Prompt](travel-photo-pixel/references/prompt.zh-CN.md)
- [积木微缩 Prompt](travel-photo-bricks/references/prompt.zh-CN.md)
- [手绘动画 Prompt](travel-photo-animation/references/prompt.zh-CN.md)
- [拼豆风格 Prompt](travel-photo-beads/references/prompt.zh-CN.md)

方括号用于填写主景、相对位置、道路或水面走向、醒目的细节。没有填写的部分可以让工具看照片判断；不要把老街、桥和红灯笼等示例内容套到其他照片上。

第一次先保持原比例、原视角和原主色。结果不理想时指出最明显的一项，再让工具对照原图调整。每次仍附原照片，避免把多轮生成结果当成原场景。

## 示例与效果范围

每套 `references/example-prompt.en.txt` 是本期四张风格示例实际使用的英文提示词，生成工具为内置 `image_gen`。本期输入图是生成的虚构江南老街，**不是个人旅行实拍**。

新增的中文模板与 Skill 做了文件结构和引用核对，没有重新逐张生成测试，也未在所有照片、模型或版本上实测。不同照片与模型可能产生不同细节，不保证成品完全一致。

拼豆图片是风格效果图，不能直接当作准确可制作的网格、品牌色号或豆粒数量表；积木图片也不是实体套装或拼装说明书。像素图不保证可直接作为游戏素材。

## photo-abstract-editorial 与来源

照片与抽象记忆面板组合的 `photo-abstract-editorial` 来自 **ZzzLlc0405（@AM.）**：

- [原作者仓库与获取方法](https://github.com/ZzzLc0405/photo-abstract-editorial)
- [原作者中文 Prompt](https://github.com/ZzzLc0405/photo-abstract-editorial/blob/main/references/photo-abstract-editorial-prompt.zh-CN.md)
- [原作者授权说明](https://github.com/ZzzLc0405/photo-abstract-editorial/blob/main/LICENSE.md)

它不属于本仓库四套自制 Skill，本仓库没有复制或重新打包原 Skill、完整 Prompt 或作者示例。请从原仓库自行获取，并按原作者许可证使用；商业使用与商业分发需按原作者要求取得授权。

四套自制工作流和中文模板由本期编辑整理；英文示例提示词来自本期已完成的参考图编辑任务。仓库不包含私人照片、账号凭据或本地缓存路径。


