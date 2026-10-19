# 中文改写抽检 · 2026-10-19

- 提交数: 45
- 生成于: 2026-10-19T23:15:20.519503+08:00

## 1. 7.5 HWC Overlay Plane 与合成降级排查

- commit: `5904dad72ae8`
- 文件: `src/part2-performance/ch07-smoothness/05-hwc-overlay-composition-downgrade.md`
- run_id: `20261019-223020-cn-rewrite-7041be2c6d67c275`
- compare: gloss_per_1k 14.87→14.39, neg_per_1k 2.44→0.24, regloss 0→0, women 9→15, pass=True

## 2. 23.3 Native 与虚拟内存管理优化

- commit: `b43ac8f60650`
- 文件: `src/part5-app/ch23-memory-practice/03-native-virtual-memory-optimization.md`
- run_id: `20261019-220020-cn-rewrite-9186348384205d63`
- compare: gloss_per_1k 7.35→7.13, neg_per_1k 1.7→0.1, regloss 1→1, women 10→14, pass=True

## 3. 7.6 Accessibility、ContentCapture 与 Autofill 性能

- commit: `31fd09ceb7be`
- 文件: `src/part2-performance/ch07-smoothness/06-accessibility-contentcapture-autofill.md`
- run_id: `20261019-213020-cn-rewrite-755f2f17aea70529`
- compare: gloss_per_1k 4.91→4.81, neg_per_1k 2.2→0.13, regloss 0→0, women 6→11, pass=True

## 4. 4.8 ZRAM 压缩交换与应用重启延迟

- commit: `98678559dda5`
- 文件: `src/part1-fundamentals/ch04-memory/08-zram-compressed-swap-relaunch.md`
- run_id: `20261019-210020-cn-rewrite-ebd88334715f737e`
- compare: gloss_per_1k 6.78→6.5, neg_per_1k 4.52→0.16, regloss 0→0, women 0→18, pass=True

## 5. 13.12 Android 17 游戏引擎渲染链路

- commit: `e0d71a597b4d`
- 文件: `src/part2-performance/ch13-rendering-pipelines/12-game-engine.md`
- run_id: `20261019-203020-cn-rewrite-a0d0a1d78c449c0f`
- compare: gloss_per_1k 4.02→3.83, neg_per_1k 5.03→1.28, regloss 0→0, women 0→25, pass=True

## 6. 13.6 SurfaceControl 与 HardwareBufferRenderer

- commit: `06889ad79abb`
- 文件: `src/part2-performance/ch13-rendering-pipelines/06-surfacecontrol-hardwarebuffer-renderer.md`
- run_id: `20261019-200020-cn-rewrite-09dc67baf6287aa9`
- compare: gloss_per_1k 3.41→3.36, neg_per_1k 2.68→0.24, regloss 2→2, women 6→14, pass=True

## 7. 26.11 Battery Historian 与功耗指标集成

- commit: `b1804ed138d4`
- 文件: `src/part5-app/ch26-observability/11-battery-historian-performance-metrics-integration.md`
- run_id: `20261019-193020-cn-rewrite-3e02a7997f9379c0`
- compare: gloss_per_1k 7.76→7.51, neg_per_1k 2.76→2.17, regloss 1→1, women 7→9, pass=True

## 8. 24.5 移动网络架构、连接与容灾

- commit: `c4a3606a2d64`
- 文件: `src/part5-app/ch24-io-network/05-mobile-network-connection-resilience.md`
- run_id: `20261019-190020-cn-rewrite-dad9eee709aa36c1`
- compare: gloss_per_1k 4.31→4.31, neg_per_1k 0.72→0.08, regloss 7→7, women 4→8, pass=True

## 9. 22.3 Compose 性能、Compiler 与 Modifier.Node 诊断

- commit: `8d09ee6f580d`
- 文件: `src/part5-app/ch22-rendering-practice/03-compose-compiler-modifier-diagnostics.md`
- run_id: `20261019-183020-cn-rewrite-b99eea76e9b44213`
- compare: gloss_per_1k 3.7→3.68, neg_per_1k 1.43→0.0, regloss 0→0, women 10→19, pass=True

## 10. 14.6 Android Tracing 基础设施与自定义 Trace

- commit: `3d6c9b3b1a77`
- 文件: `src/part3-tools/ch14-perfetto/06-android-tracing-infrastructure-custom-trace.md`
- run_id: `20261019-180020-cn-rewrite-525517fbaefaba9c`
- compare: gloss_per_1k 4.05→3.93, neg_per_1k 2.37→0.19, regloss 0→0, women 0→15, pass=True

## 11. 20.5 OOM、进程资源治理与 WebView Renderer 恢复

- commit: `d24ac22aa96f`
- 文件: `src/part5-app/ch20-stability/05-oom-webview-renderer-recovery.md`
- run_id: `20261019-173020-cn-rewrite-a8d54f08091df8e2`
- compare: gloss_per_1k 8.27→8.14, neg_per_1k 0.4→0.2, regloss 11→11, women 12→20, pass=True

## 12. 22.4 Compose 布局、测量与文字渲染

- commit: `f7244283ea61`
- 文件: `src/part5-app/ch22-rendering-practice/04-compose-layout-text-rendering.md`
- run_id: `20261019-170020-cn-rewrite-bb01376c7188d8ef`
- compare: gloss_per_1k 7.72→7.56, neg_per_1k 3.24→0.46, regloss 0→0, women 0→8, pass=True

## 13. 9.4 ANR 诊断案例集

- commit: `7f6b5f618008`
- 文件: `src/part2-performance/ch09-anr/04-case-studies.md`
- run_id: `20261019-163020-cn-rewrite-a030a427edf34101`
- compare: gloss_per_1k 10.12→9.93, neg_per_1k 2.19→0.0, regloss 4→4, women 15→16, pass=True

## 14. 4.7 内存规整与直接回收性能边界

- commit: `0c02ca2d6630`
- 文件: `src/part1-fundamentals/ch04-memory/07-memory-compaction-direct-reclaim.md`
- run_id: `20261019-160020-cn-rewrite-e574f072a43b0090`
- compare: gloss_per_1k 4.52→4.35, neg_per_1k 4.22→0.56, regloss 0→0, women 0→17, pass=True

## 15. 7.2 卡顿分析方法、典型场景与案例

- commit: `bea209e874c5`
- 文件: `src/part2-performance/ch07-smoothness/02-jank-methodology-scenarios-cases.md`
- run_id: `20261019-153020-cn-rewrite-1099e59d922bd79a`
- compare: gloss_per_1k 21.46→21.39, neg_per_1k 0.76→0.0, regloss 10→10, women 24→28, pass=True

## 16. 13.1 Android View 渲染管线与分析方法

- commit: `6d203787eed4`
- 文件: `src/part2-performance/ch13-rendering-pipelines/01-android-view-pipeline-analysis.md`
- run_id: `20261019-150020-cn-rewrite-f5a1be37257a69c2`
- compare: gloss_per_1k 17.6→17.13, neg_per_1k 0.0→0.0, regloss 5→5, women 7→18, pass=True

## 17. 15.10 三方性能库、Hook 与可观测性基础设施

- commit: `fa52af7125b1`
- 文件: `src/part3-tools/ch15-other-tools/10-third-party-hook-observability.md`
- run_id: `20261019-140020-cn-rewrite-ae86824cd613165f`
- compare: gloss_per_1k 12.53→12.03, neg_per_1k 0.38→0.0, regloss 9→9, women 11→30, pass=True

## 18. 26.3 线上排障、诊断通道与非 Play ROM 适配

- commit: `e68a16b43e7e`
- 文件: `src/part5-app/ch26-observability/03-online-troubleshooting-diagnostic-rom.md`
- run_id: `20261019-133020-cn-rewrite-d9713a40fd3489df`
- compare: gloss_per_1k 4.49→4.47, neg_per_1k 1.71→0.4, regloss 4→4, women 8→16, pass=True

## 19. 20.6 Native 内存泄漏的线上分层监控

- commit: `d557a4f614e4`
- 文件: `src/part5-app/ch20-stability/06-native-memory-leak-online-monitoring.md`
- run_id: `20261019-130020-cn-rewrite-d83be0ac4ff8268f`
- compare: gloss_per_1k 10.08→10.0, neg_per_1k 1.96→0.45, regloss 0→0, women 9→14, pass=True

## 20. 3.1 Input 分发、拦截与安全边界

- commit: `ebbe754447e7`
- 文件: `src/part1-fundamentals/ch03-input/01-input-dispatch-interception-security.md`
- run_id: `20261019-123020-cn-rewrite-f624a63d21e4b75a`
- compare: gloss_per_1k 2.4→2.26, neg_per_1k 3.02→0.61, regloss 0→0, women 0→14, pass=True

## 21. 22.6 Compose First 与 View/Compose 互操作性能实战

- commit: `955981fb40dc`
- 文件: `src/part5-app/ch22-rendering-practice/06-compose-view-interop.md`
- run_id: `20261019-120020-cn-rewrite-5210bbd5de099fe5`
- compare: gloss_per_1k 1.89→1.78, neg_per_1k 3.25→0.25, regloss 0→0, women 0→16, pass=True

## 22. 20.13 Native 动态库安全发布、装载与回滚

- commit: `bf46683d6c53`
- 文件: `src/part5-app/ch20-stability/13-native-dcl-secure-loading.md`
- run_id: `20261019-113020-cn-rewrite-538e592a92dca35e`
- compare: gloss_per_1k 6.06→5.8, neg_per_1k 5.12→0.0, regloss 0→0, women 0→9, pass=True

## 23. 8.4 Kotlin Coroutine、Flow 与线程调度实践

- commit: `8601f5927fbb`
- 文件: `src/part2-performance/ch08-responsiveness/04-coroutine-performance.md`
- run_id: `20261019-110020-cn-rewrite-2c74af7dc7ecae16`
- compare: gloss_per_1k 3.53→3.37, neg_per_1k 3.71→0.0, regloss 0→0, women 0→15, pass=True

## 24. 4.5 16 KB Page Size 与 Android 性能

- commit: `cbedd3e0f875`
- 文件: `src/part1-fundamentals/ch04-memory/05-16kb-page-size.md`
- run_id: `20261019-103020-cn-rewrite-ab14067a4c39efd9`
- compare: gloss_per_1k 5.93→5.56, neg_per_1k 1.67→0.17, regloss 0→0, women 6→11, pass=True

## 25. 2.7 GPU 渲染与图形 API 选型

- commit: `84d333a4c360`
- 文件: `src/part1-fundamentals/ch02-rendering/07-gpu-rendering-graphics-api.md`
- run_id: `20261019-100020-cn-rewrite-3d5d14f889e56553`
- compare: gloss_per_1k 18.3→18.03, neg_per_1k 1.91→0.24, regloss 8→8, women 11→21, pass=True

## 26. 22.16 WebView 性能优化实战

- commit: `3cdf95e326e1`
- 文件: `src/part5-app/ch22-rendering-practice/16-webview-optimization.md`
- run_id: `20261019-093020-cn-rewrite-a96724d8e1c9f625`
- compare: gloss_per_1k 11.24→11.13, neg_per_1k 2.13→0.14, regloss 2→2, women 9→10, pass=True

## 27. 8.7 Play Integrity API 性能与集成延迟

- commit: `d55bb6edd2d9`
- 文件: `src/part2-performance/ch08-responsiveness/07-play-integrity-api-performance.md`
- run_id: `20261019-090020-cn-rewrite-7fa603efcb3a5ae0`
- compare: gloss_per_1k 3.09→2.93, neg_per_1k 6.19→0.21, regloss 0→0, women 0→11, pass=True

## 28. 26.15 ART 动态方法追踪与 JVMTI 边界

- commit: `13e6d65552a4`
- 文件: `src/part5-app/ch26-observability/15-art-dynamic-tracing-jvmti.md`
- run_id: `20261019-083020-cn-rewrite-bf95039cf88d3cdd`
- compare: gloss_per_1k 2.4→3.84, neg_per_1k 3.24→0.12, regloss 0→0, women 0→10, pass=True

## 29. 2.9 SurfaceFlinger 合成、FrontEnd 与事务队列

- commit: `502010bba8d4`
- 文件: `src/part1-fundamentals/ch02-rendering/09-surfaceflinger-frontend-transaction.md`
- run_id: `20261019-080720-cn-rewrite-fc9fdc918383fbe6`
- compare: gloss_per_1k 18.52→18.94, neg_per_1k 0.97→0.08, regloss 17→17, women 10→24, pass=True

## 30. 17.12 千万级 DAU 的 APM 端侧架构

- commit: `f437160ea6ed`
- 文件: `src/part3-tools/ch17-apm/12-apm-client-architecture.md`
- run_id: `20261019-073020-cn-rewrite-16b745ac792dec90`
- compare: gloss_per_1k 7.31→3.56, neg_per_1k 1.07→0.89, regloss 0→0, women 3→13, pass=True

## 31. 1.16 应用分发、安装验证与 PackageManager 性能

- commit: `8b0bac64c337`
- 文件: `src/part1-fundamentals/ch01-architecture/16-package-distribution-install-verification.md`
- run_id: `20261019-070020-cn-rewrite-2ae06b76112dee41`
- compare: gloss_per_1k 6.26→0.42, neg_per_1k 0.49→0.49, regloss 0→0, women 24→24, pass=True

## 32. 17.7 实验室测试工具与设备 Benchmark

- commit: `792e9e1ba12d`
- 文件: `src/part3-tools/ch17-apm/07-lab-tools-device-benchmarks.md`
- run_id: `20261019-063020-cn-rewrite-f2e8fcf33846f36c`
- compare: gloss_per_1k 7.97→1.88, neg_per_1k 0.27→0.09, regloss 0→0, women 17→21, pass=True

## 33. 25.10 应用体积分析与优化：DEX、Native SO 与资源

- commit: `ddf919027ea9`
- 文件: `src/part5-app/ch25-power-size/10-apk-r8-resource-optimization.md`
- run_id: `20261019-060020-cn-rewrite-0604e4991ed9367b`
- compare: gloss_per_1k 6.13→3.43, neg_per_1k 1.52→0.05, regloss 0→0, women 15→16, pass=True

## 34. 22.7 View、Compose 动画与共享元素性能

- commit: `85bb6170ff1d`
- 文件: `src/part5-app/ch22-rendering-practice/07-view-compose-animation-shared-transition.md`
- run_id: `20261019-053020-cn-rewrite-259a8bb7023da310`
- compare: gloss_per_1k 5.08→4.34, neg_per_1k 1.81→0.0, regloss 0→0, women 6→8, pass=True

## 35. 4.1 Android 与 Linux 内存管理全景

- commit: `f49ab4713926`
- 文件: `src/part1-fundamentals/ch04-memory/01-android-linux-memory-overview.md`
- run_id: `20261019-050020-cn-rewrite-7eda697fa949b690`
- compare: gloss_per_1k 5.04→1.54, neg_per_1k 2.74→0.0, regloss 0→0, women 16→21, pass=True

## 36. 2.8 BufferQueue、Gralloc 与 Sync Fence

- commit: `037750e981b3`
- 文件: `src/part1-fundamentals/ch02-rendering/08-bufferqueue-gralloc-sync-fence.md`
- run_id: `20261019-043020-cn-rewrite-2a07f2fc9b354218`
- compare: gloss_per_1k 7.15→2.3, neg_per_1k 0.26→0.0, regloss 0→0, women 10→13, pass=True

## 37. 24.4 MediaStore、Photo Picker 与媒体转码

- commit: `f3055e903fdb`
- 文件: `src/part5-app/ch24-io-network/04-mediastore-photo-picker-transcoding.md`
- run_id: `20261019-040020-cn-rewrite-2f7948aecadc3106`
- compare: gloss_per_1k 2.37→0.74, neg_per_1k 3.92→0.08, regloss 2→0, women 0→7, pass=True

## 38. 2.16 折叠屏显示切换、窗口连续性与渲染性能

- commit: `ca27c64ca66e`
- 文件: `src/part1-fundamentals/ch02-rendering/16-foldable-display-pipeline-performance.md`
- run_id: `20261019-033020-cn-rewrite-f691e632e2f077c8`
- compare: gloss_per_1k 2.65→0.0, neg_per_1k 3.21→0.27, regloss 0→0, women 12→16, pass=True

## 39. 19.4 Power HAL、schedutil 与 Power Stats

- commit: `4cc2b5894931`
- 文件: `src/part4-system/ch19-oem/04-power-hal-schedutil-power-stats.md`
- run_id: `20261019-030020-cn-rewrite-3575c680b35da708`
- compare: gloss_per_1k 7.07→4.84, neg_per_1k 2.28→1.04, regloss 2→0, women 25→25, pass=True

## 40. 15.11 GPU 调试与 AGI 单帧分析

- commit: `712ce7a53168`
- 文件: `src/part3-tools/ch15-other-tools/11-gpu-debug-agi-frame-analysis.md`
- run_id: `20261019-023020-cn-rewrite-ce91ce318085a792`
- compare: gloss_per_1k 4.34→1.21, neg_per_1k 1.36→0.13, regloss 0→0, women 18→20, pass=True

## 41. 18.2 AOSP 源码编译与调试环境

- commit: `dd7aeacd5148`
- 文件: `src/part4-system/ch18-aosp/02-aosp-build.md`
- run_id: `20261019-020020-cn-rewrite-085fb30954575fc5`
- compare: gloss_per_1k 8.62→6.37, neg_per_1k 4.58→1.33, regloss 0→0, women 0→12, pass=True

## 42. 14.4 Perfetto 指标自动化与分析平台

- commit: `aeb5ccd21387`
- 文件: `src/part3-tools/ch14-perfetto/04-perfetto-metrics-automation-platform.md`
- run_id: `20261019-013020-cn-rewrite-643a31dd47360eba`
- compare: gloss_per_1k 3.6→1.53, neg_per_1k 2.27→0.19, regloss 0→0, women 8→9, pass=True

## 43. 2.3 VSync、Choreographer 与 SurfaceFlinger 调度

- commit: `9a2d9ef70677`
- 文件: `src/part1-fundamentals/ch02-rendering/03-vsync-choreographer-sf-scheduling.md`
- run_id: `20261019-010020-cn-rewrite-bf3a94cc77218ef2`
- compare: gloss_per_1k 6.81→0.92, neg_per_1k 1.47→0.07, regloss 2→1, women 34→32, pass=True

## 44. 3.4 手势识别算法与性能优化

- commit: `5c07a62efd6d`
- 文件: `src/part1-fundamentals/ch03-input/04-gesture-recognition-performance.md`
- run_id: `20261019-003020-cn-rewrite-2827583fb2550533`
- compare: gloss_per_1k 3.44→1.42, neg_per_1k 3.68→0.71, regloss 0→0, women 0→11, pass=True

## 45. 25.7 应用层 CPU 优化实战指南

- commit: `5ded7e7f644f`
- 文件: `src/part5-app/ch25-power-size/07-application-cpu-optimization.md`
- run_id: `20261019-000020-cn-rewrite-fda680b6568c7d5c`
- compare: gloss_per_1k 7.1→0.7, neg_per_1k 3.37→0.0, regloss 0→0, women 0→11, pass=True
