# VACE

视频创作与编辑一体框架（通义，ICCV 2025）。官方定位 all-in-one，三类任务可自由组合：**R2V**（参考图出视频）、**V2V**（整条视频改风格）、**MV2V**（遮罩局部改——圈出一块改一块），官方举的例子有 Move-Anything、Swap-Anything、Reference-Anything、Expand-Anything、Animate-Anything。官方直接提供 **VACE-1.3B** 权重与 ComfyUI 集成。

## 干什么用

真题两条：一是把 `1_2_越界的毛巾.png` 定稿图当条件，长出 `videos/1_毛巾.md` 那条 9:16 一镜到底——正是 journal「视频只需生成图片和图片之间的关系」的工具版；二是生成分镜哪里不对，MV2V 圈出来只改那块。

## 现状

尚未接入；VACE-1.3B 是另一份 1.3B 档权重，与现有底座不通用，能否跑通待实测。

## 出处

- <https://github.com/ali-vilab/VACE>
- Wan 官方 README 的 VACE 条目（1.3B/14B 两档）
- 查证日期：2026-11-21
