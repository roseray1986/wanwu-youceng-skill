# 万物有层 · 知识纸雕剧场

> 把复杂知识，展开成一个看得懂的微缩世界。

**万物有层** 是一个面向任意 Agent 的知识视觉化 Skill。它把一个知识问题拆成三个连续的因果状态，并产出统一母场景、纸雕分镜、竖屏视频方案和手机封面。

它不绑定 TRAE、Codex 或任何特定生图模型。

## 下载

[下载最新通用安装包](https://github.com/roseray1986/wanwu-youceng-skill/releases/latest/download/knowledge-paper-theater-v3-universal.zip)

下载后查看压缩包根目录的 \`INSTALL_通用Agent.md\`。

## 它能做什么

- 为知识短视频筛选更有停留力的选题和反差钩子；
- 把原理压缩为三个彼此推动的可视化状态；
- 用同一套纸雕世界、镜头、材质与色彩表达因果，不做三张互不相关的配图；
- 输出封面、旁白节奏、字幕与音效锚点；
- 检查竖屏安全区、文字可读性、事实与视觉隐喻的边界；
- 在新题材测试后，复盘并迭代可复用的方法。

## 不依赖生图模型

Skill 会先检查当前 Agent 的能力，再走可完成的路径：

| 当前能力 | 输出方式 |
| --- | --- |
| 有生图或已有参考图 | 先固定一个统一母场景，再延展三幕 |
| 无生图，但有 SVG / HTML / Canvas / 幻灯片能力 | 制作可编辑的分层纸雕分镜 |
| 没有绘图或渲染能力 | 交付完整制作包：分镜、镜头、文案、提示词、资产清单 |
| 没有 TTS 或视频渲染能力 | 冻结旁白与语义节奏，等待真实音频后再逐字同步 |

没有任何一种模型，不会让 Skill 停在“无法执行”；但它也不会把未生成的内容说成已生成。

## 安装

将解压出的 \`knowledge-paper-theater\` 文件夹放入你的 Agent 所识别的 Skills 目录，再重载 Skills。常见目录示例：

\`\`\`text
<项目根目录>/.agents/skills/knowledge-paper-theater/
<用户目录>/.codex/skills/knowledge-paper-theater/
<用户目录>/.claude/skills/knowledge-paper-theater/
\`\`\`

确认 \`SKILL.md\` 位于该文件夹的第一层。

## 调用示例

\`\`\`text
使用 knowledge-paper-theater，把“没有事故为什么高速也会堵车”做成一条抖音知识短片方案。
先检查你是否具备生图、矢量绘制、渲染和旁白能力；按可用能力选择执行路径。
\`\`\`

## 已发布案例

| 案例 | 说明 |
| --- | --- |
| [台风、铁锈、爆米花](https://github.com/roseray1986/wanwu-youceng-skill/releases/download/v1.0.0/knowledge-paper-theater-showcase-v8-all-scenes-safe-final.mp4) | 用三类知识题材验证统一世界、旁白与安全区流程 |
| [鲁珀特之泪](https://github.com/roseray1986/wanwu-youceng-skill/releases/download/v1.0.0/prince-ruperts-drop-final-1080x1920.mp4) | 材料科学题材：圆头抗砸、细尾一断爆碎 |

## 设计原则

1. 先让观众看到问题，再介绍制作方法；
2. 美学服务理解：层次、遮挡、折叠和光线都必须承担信息；
3. 三幕必须有因果连续性；
4. 重要文字必须在可编辑版式层，而不是交给图片模型；
5. 技术内容明确区分事实、简化和视觉隐喻。
