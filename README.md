# 象棋棋谱资料库

本工作区仅保存中国象棋棋谱、开局数据和课程整理文档，不包含桌面应用、规则引擎、构建脚本或产品工程文件。

## 主要内容

- `content/openings.json`：开局体系数据。
- `content/mainline-wxf.json`、`content/zhongpao-*.json`：中炮及主线棋谱数据。
- `content/zhongpao-棋谱.md`、`content/zhongpao-棋谱.html`：中炮棋谱。
- `content/huangdanqing-opening-tree.md`：黄丹青课程开局分支树（无分析版）。
- `content/huangdanqing-opening-analysis.md`：黄丹青课程开局分支与棋理（有分析版）。
- `content/huangdanqing-repertoire-complete-15.md`：15 门完整课程的逐着文字手册。
- `content/huangdanqing-repertoire.html`：可离线打开的交互棋谱，支持分支树、父子变化跳转、脱谱练习和快捷键。
- `content/huangdanqing-move-completion-log.md`：逐步着法补充记录。

## 黄丹青课程进度

[课程索引](content/huangdanqing-moves/index.json)覆盖 48 个课程条目；`content/huangdanqing-moves/` 保存逐课源数据、正式 JSON 与校验记录。原课程视频和转录未纳入仓库。

- 已启动 30 门：402 条变化、1769 个半回合。
- 完整 15 门：C03–C07、C15、C16、C23、C24、C39–C44，共 228 条变化、1001 个半回合。
- 部分完成 15 门：C08–C14、C25–C27、C30–C34，共 174 条变化、768 个半回合；精确缺口保留在各课 `pending_demonstrations` 中。

各课校验记录为实际运行结果，覆盖 UCCI 合法性、中文记谱和 FEN 连续性。独立人工复核状态以各文件为准；未运行 Pikafish，不提供引擎评分。
