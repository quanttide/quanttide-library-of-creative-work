# FlowEdit / FlowAlign（WANAlign2.1）

免训练视频编辑，都长在 **Wan2.1-T2V-1.3B** 上：不训练、不反演，拿已生成的视频加一句文字指令改内容。合集仓 WANAlign2.1 = FlowAlign（ICLR 26）+ 注意力掩码分区独立调编辑强度（DIFS），保留区与修改区互不打扰。

## 干什么用

真题：`videos/1_毛巾` 分镜手部崩了——不整条重抽，只改手那一处、其余帧原样保留，正是 essay「一次只改一个变量」的工具版。

## 实测数据

其 README 对比（A100 80GB）：WANAlign2.1 **75 秒**改一条，WANEdit2.1 150 秒，FlowDirector 540 秒。已被官方 Wan 仓与 FlowEdit 官方收录进 community work（2025-12）。

## 现状

尚未接入；基于与实验室同档的 1.3B 底座，能否跑通待实测。

## 出处

- <https://github.com/KyujinHan/Awesome-Training-Free-WAN2.1-Editing>
- <https://arxiv.org/abs/2412.08629>（FlowEdit）
- 查证日期：2026-11-21
