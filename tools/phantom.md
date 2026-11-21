# Phantom

主体一致性视频生成（字节，ICCV 2025，arXiv 2502.11079）。给一张人物/物体**参考图**，生成的视频里该主体按参考图保持一致。官方放出 **Phantom-Wan-1.3B** 与 14B 权重，接在 Wan2.1 底座上；kijai 的 ComfyUI-WanVideoWrapper 已适配 1.3B（官方 2025-04-23 公告）。

## 干什么用

用定稿成图当「角色照」，之后每条视频里的人都按它长。真题：把 `urban-romance/images/1_2_越界的毛巾.png` 当参考，后续镜头里的 Lu 保持同一人。

## 现状

尚未接入；1.3B 权重与实验室底座同档，ComfyUI 侧靠第三方插件，能否跑通待实测。

## 出处

- <https://github.com/Phantom-video/Phantom>
- <https://github.com/kijai/ComfyUI-WanVideoWrapper>
- 查证日期：2026-11-21
