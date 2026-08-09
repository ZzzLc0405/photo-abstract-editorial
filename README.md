# Photo Abstract Editorial

将一张照片转化为“原始摄影区域 + 抽象记忆面板 + 诗意英文标题”的竖向编辑作品的 Codex Skill。它保留照片的真实内容，并仅从照片本身提炼空间关系、构图节奏和色彩关系；它不是滤镜、照片重画或风格迁移。

The skill includes the complete prompt in both Chinese and English.

## 使用方法

1. 将整个 `photo-abstract-editorial` 文件夹复制到你的 Codex skills 目录，例如 `~/.codex/skills/`。
2. 开启新的 Codex 对话，上传一张希望处理的照片。
3. 直接提出需求，例如：

   > 使用 `photo-abstract-editorial` 将这张照片制作成摄影与抽象面板组合的编辑作品。

4. Skill 会将原图保留在成品的上方或主要区域，并在下方创建由原图关系推导出的极简抽象面板。成品中只保留一个原创英文标题（可选副标题）。

也可以直接打开下列文件，并将其作为图像生成提示词使用：

- 中文版：[references/photo-abstract-editorial-prompt.zh-CN.md](references/photo-abstract-editorial-prompt.zh-CN.md)
- English version: [references/photo-abstract-editorial-prompt.en.md](references/photo-abstract-editorial-prompt.en.md)

## 支持的图片格式

可直接使用常见的渲染后栅格图片：`JPEG` / `JPG`、`PNG`、`WebP` 和静态 `GIF`。如果 GIF 包含动画，请先选定并导出一个代表性帧。

相机 RAW、`DNG`、`CR2` / `CR3`、`NEF`、`ARW`、`RAF`、`HEIC`、`TIFF`、`SVG` 和 `PDF` 不属于本 Skill 的直接输入格式。请先保留原文件不变，再导出一份中性、非破坏性的 sRGB `JPEG` 或 `PNG`：不得在转换时进行创意调色、修图、生成式扩展或裁切。若当前环境无法可靠转换，应请用户提供渲染后的 `JPEG` 或 `PNG`，而不是声称已直接处理原始格式。

## 可自由调整的部分

这套提示词应当被视为高质量起点，而不是不可变的版式规范。请按自己的审美和项目需求修改以下参数：

- **照片与面板的比例**：可调整摄影区域和抽象面板的高度占比、画布比例，以及抽象母题的大小与留白。
- **颜色**：可修改象牙色面板背景、照片提取色的饱和度、主色与强调色的数量和倾向。
- **抽象形式**：可选择或混合色块、柔和有机质量、弧形笔触、短条、层叠色带、简化建筑质量、细线、点状标记等形式。
- **版式与文字**：可调整母题位置、标题位置、字体气质、标题长度和是否使用副标题。
- **抽象程度**：可根据题材在“关系优先”和“保留少量身份特征”之间调整，例如让地标建筑或小型物件保留更多辨识线索。

调整时建议保留两条核心原则：

1. 上传照片始终是唯一内容来源，照片区域不应被重画、扩展或改写。
2. 抽象面板中的每个重要元素都应能追溯到原照片中真实存在的空间、色彩或结构事实。

## 内容结构

```text
photo-abstract-editorial/
├── SKILL.md                         # Skill 工作流程与约束
├── agents/openai.yaml               # Codex 界面元数据
├── references/
│   ├── photo-abstract-editorial-prompt.zh-CN.md
│   └── photo-abstract-editorial-prompt.en.md
└── assets/examples/                 # 5 张成品输出示例与说明
```

`assets/examples` 中的图片是完整的成品输出参考，而不是待处理的输入照片。请参阅[示例说明](assets/examples/README.md)了解每张图片展示的规则。它们仅用于理解预期行为；不要将其中的主题、色彩或构图复用于新的作品。
