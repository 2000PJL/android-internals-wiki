# 中文改写抽检 · 2026-10-22

- 提交数: 46
- 生成于: 2026-10-22T23:15:20.439850+08:00

## 1. 1.20 音频链路（Audio Pipeline）延迟与性能

- commit: `09b0e428795d`
- 文件: `src/part1-fundamentals/ch01-architecture/20-audio-pipeline-performance.md`
- run_id: `20261022-223020-cn-rewrite-7eb48a57e0b67f35`
- compare: gloss_per_1k 5.55→5.43, neg_per_1k 0.79→0.0, regloss 0→0, women 10→13, pass=True

## 2. 1.12 ActivityManager 组件调度、进程优先级与锁模型

- commit: `bf81879a560d`
- 文件: `src/part1-fundamentals/ch01-architecture/12-activitymanager-process-lock-priority.md`
- run_id: `20261022-220020-cn-rewrite-c86ac2c677e7fe35`
- compare: gloss_per_1k 4.47→4.43, neg_per_1k 0.18→0.0, regloss 1→1, women 10→22, pass=True

## 3. 4.8 ZRAM 压缩交换与应用重启延迟

- commit: `7e29fa293a2f`
- 文件: `src/part1-fundamentals/ch04-memory/08-zram-compressed-swap-relaunch.md`
- run_id: `20261022-213020-cn-rewrite-ebd88334715f737e`
- compare: gloss_per_1k 6.5→6.44, neg_per_1k 0.16→0.0, regloss 0→0, women 18→21, pass=True

## 4. 22.15 Vulkan 管线缓存与 Impeller 着色器编译实战

- commit: `87666e0693a9`
- 文件: `src/part5-app/ch22-rendering-practice/15-vulkan-impeller-shader-compilation.md`
- run_id: `20261022-210020-cn-rewrite-427637d83b2efe4a`
- compare: gloss_per_1k 5.97→5.93, neg_per_1k 0.41→0.0, regloss 0→0, women 20→31, pass=True

## 5. 1.14 Android 17 BroadcastQueue 进程级调度与广播性能边界

- commit: `9870795c4245`
- 文件: `src/part1-fundamentals/ch01-architecture/14-broadcastqueue-scheduling-performance.md`
- run_id: `20261022-203020-cn-rewrite-67fce7bba00c4565`
- compare: gloss_per_1k 5.74→5.37, neg_per_1k 0.66→0.0, regloss 0→0, women 13→14, pass=True

## 6. 26.11 Battery Historian 与功耗指标集成

- commit: `16ecffe32eaa`
- 文件: `src/part5-app/ch26-observability/11-battery-historian-performance-metrics-integration.md`
- run_id: `20261022-200020-cn-rewrite-3e02a7997f9379c0`
- compare: gloss_per_1k 7.51→7.4, neg_per_1k 2.17→0.0, regloss 1→1, women 9→16, pass=True

## 7. 24.5 移动网络架构、连接与容灾

- commit: `d13266cbb960`
- 文件: `src/part5-app/ch24-io-network/05-mobile-network-connection-resilience.md`
- run_id: `20261022-193020-cn-rewrite-dad9eee709aa36c1`
- compare: gloss_per_1k 4.31→4.41, neg_per_1k 0.08→0.08, regloss 7→7, women 8→11, pass=True

## 8. 3.4 手势识别算法与性能优化

- commit: `d44abc718ce1`
- 文件: `src/part1-fundamentals/ch03-input/04-gesture-recognition-performance.md`
- run_id: `20261022-190020-cn-rewrite-2827583fb2550533`
- compare: gloss_per_1k 2.85→2.73, neg_per_1k 0.71→0.0, regloss 0→0, women 11→15, pass=True

## 9. 17.7 实验室测试工具与设备 Benchmark

- commit: `16b475597f81`
- 文件: `src/part3-tools/ch17-apm/07-lab-tools-device-benchmarks.md`
- run_id: `20261022-183020-cn-rewrite-f2e8fcf33846f36c`
- compare: gloss_per_1k 10.07→10.24, neg_per_1k 0.09→0.0, regloss 3→3, women 21→28, pass=True

## 10. 20.5 OOM、进程资源治理与 WebView Renderer 恢复

- commit: `0cc7f944b4d2`
- 文件: `src/part5-app/ch20-stability/05-oom-webview-renderer-recovery.md`
- run_id: `20261022-180019-cn-rewrite-a8d54f08091df8e2`
- compare: gloss_per_1k 8.14→8.05, neg_per_1k 0.2→0.0, regloss 11→11, women 20→25, pass=True

## 11. 18.2 AOSP 源码编译与调试环境

- commit: `3f53bc0eb37e`
- 文件: `src/part4-system/ch18-aosp/02-aosp-build.md`
- run_id: `20261022-173020-cn-rewrite-085fb30954575fc5`
- compare: gloss_per_1k 10.03→9.93, neg_per_1k 1.29→0.0, regloss 1→1, women 12→13, pass=True

## 12. 9.4 ANR 诊断案例集

- commit: `f3be76dc3f0e`
- 文件: `src/part2-performance/ch09-anr/04-case-studies.md`
- run_id: `20261022-170020-cn-rewrite-a030a427edf34101`
- compare: gloss_per_1k 9.93→9.79, neg_per_1k 0.0→0.0, regloss 4→4, women 16→24, pass=True

## 13. 8.7 Play Integrity API 性能与集成延迟

- commit: `5712a02083bc`
- 文件: `src/part2-performance/ch08-responsiveness/07-play-integrity-api-performance.md`
- run_id: `20261022-163020-cn-rewrite-7fa603efcb3a5ae0`
- compare: gloss_per_1k 2.93→2.83, neg_per_1k 0.21→0.2, regloss 0→0, women 11→19, pass=True

## 14. 7.2 卡顿分析方法、典型场景与案例

- commit: `b9878bfa550a`
- 文件: `src/part2-performance/ch07-smoothness/02-jank-methodology-scenarios-cases.md`
- run_id: `20261022-160020-cn-rewrite-1099e59d922bd79a`
- compare: gloss_per_1k 21.39→21.1, neg_per_1k 0.0→0.0, regloss 10→10, women 28→31, pass=True

## 15. 13.1 Android View 渲染管线与分析方法

- commit: `e9d17f12d698`
- 文件: `src/part2-performance/ch13-rendering-pipelines/01-android-view-pipeline-analysis.md`
- run_id: `20261022-153020-cn-rewrite-f5a1be37257a69c2`
- compare: gloss_per_1k 17.13→16.9, neg_per_1k 0.0→0.0, regloss 5→5, women 18→22, pass=True

## 16. 15.10 三方性能库、Hook 与可观测性基础设施

- commit: `24d1dd7e52cd`
- 文件: `src/part3-tools/ch15-other-tools/10-third-party-hook-observability.md`
- run_id: `20261022-150020-cn-rewrite-ae86824cd613165f`
- compare: gloss_per_1k 12.03→11.94, neg_per_1k 0.0→0.0, regloss 9→9, women 30→34, pass=True

## 17. 15.11 GPU 调试与 AGI 单帧分析

- commit: `140b8bfb3a67`
- 文件: `src/part3-tools/ch15-other-tools/11-gpu-debug-agi-frame-analysis.md`
- run_id: `20261022-143020-cn-rewrite-ce91ce318085a792`
- compare: gloss_per_1k 12.28→12.17, neg_per_1k 0.12→0.0, regloss 4→4, women 20→26, pass=True

## 18. 26.3 线上排障、诊断通道与非 Play ROM 适配

- commit: `1721ced931e2`
- 文件: `src/part5-app/ch26-observability/03-online-troubleshooting-diagnostic-rom.md`
- run_id: `20261022-140020-cn-rewrite-d9713a40fd3489df`
- compare: gloss_per_1k 4.47→4.46, neg_per_1k 0.4→0.0, regloss 4→4, women 16→19, pass=True

## 19. 3.1 Input 分发、拦截与安全边界

- commit: `da96115eba0b`
- 文件: `src/part1-fundamentals/ch03-input/01-input-dispatch-interception-security.md`
- run_id: `20261022-133020-cn-rewrite-f624a63d21e4b75a`
- compare: gloss_per_1k 2.26→2.23, neg_per_1k 0.61→0.0, regloss 0→0, women 14→17, pass=True

## 20. 2.16 折叠屏显示切换、窗口连续性与渲染性能

- commit: `0896ba284a07`
- 文件: `src/part1-fundamentals/ch02-rendering/16-foldable-display-pipeline-performance.md`
- run_id: `20261022-130020-cn-rewrite-f691e632e2f077c8`
- compare: gloss_per_1k 15.47→15.28, neg_per_1k 0.25→0.24, regloss 3→3, women 16→22, pass=True

## 21. 22.6 Compose First 与 View/Compose 互操作性能实战

- commit: `f8c08ef8dbfa`
- 文件: `src/part5-app/ch22-rendering-practice/06-compose-view-interop.md`
- run_id: `20261022-123020-cn-rewrite-5210bbd5de099fe5`
- compare: gloss_per_1k 1.78→1.69, neg_per_1k 0.25→0.0, regloss 0→0, women 16→23, pass=True

## 22. 4.5 16 KB Page Size 与 Android 性能

- commit: `501813fede92`
- 文件: `src/part1-fundamentals/ch04-memory/05-16kb-page-size.md`
- run_id: `20261022-120020-cn-rewrite-ab14067a4c39efd9`
- compare: gloss_per_1k 5.56→5.46, neg_per_1k 0.17→0.0, regloss 0→0, women 11→19, pass=True

## 23. 8.4 Kotlin Coroutine、Flow 与线程调度实践

- commit: `bea203851ba9`
- 文件: `src/part2-performance/ch08-responsiveness/04-coroutine-performance.md`
- run_id: `20261022-113020-cn-rewrite-2c74af7dc7ecae16`
- compare: gloss_per_1k 3.37→3.33, neg_per_1k 0.0→0.0, regloss 0→0, women 15→23, pass=True

## 24. 4.1 Android 与 Linux 内存管理全景

- commit: `b06b6ab5a13d`
- 文件: `src/part1-fundamentals/ch04-memory/01-android-linux-memory-overview.md`
- run_id: `20261022-110020-cn-rewrite-7eda697fa949b690`
- compare: gloss_per_1k 3.0→2.96, neg_per_1k 0.78→0.36, regloss 1→1, women 21→28, pass=True

## 25. 2.7 GPU 渲染与图形 API 选型

- commit: `fe96c5b0cd33`
- 文件: `src/part1-fundamentals/ch02-rendering/07-gpu-rendering-graphics-api.md`
- run_id: `20261022-103020-cn-rewrite-3d5d14f889e56553`
- compare: gloss_per_1k 18.03→17.97, neg_per_1k 0.24→0.16, regloss 8→8, women 21→23, pass=True

## 26. 25.7 应用层 CPU 优化实战指南

- commit: `9a4cf4869716`
- 文件: `src/part5-app/ch25-power-size/07-application-cpu-optimization.md`
- run_id: `20261022-100020-cn-rewrite-fda680b6568c7d5c`
- compare: gloss_per_1k 6.45→6.7, neg_per_1k 0.0→0.0, regloss 0→0, women 11→14, pass=True

## 27. 25.10 应用体积分析与优化：DEX、Native SO 与资源

- commit: `b7ea5d37c357`
- 文件: `src/part5-app/ch25-power-size/10-apk-r8-resource-optimization.md`
- run_id: `20261022-093020-cn-rewrite-0604e4991ed9367b`
- compare: gloss_per_1k 8.47→8.43, neg_per_1k 0.1→0.1, regloss 4→4, women 15→21, pass=True

## 28. 2.8 BufferQueue、Gralloc 与 Sync Fence

- commit: `aeb24bfce06e`
- 文件: `src/part1-fundamentals/ch02-rendering/08-bufferqueue-gralloc-sync-fence.md`
- run_id: `20261022-090020-cn-rewrite-2a07f2fc9b354218`
- compare: gloss_per_1k 13.86→13.89, neg_per_1k 0.0→0.0, regloss 8→8, women 13→21, pass=True

## 29. 2.9 SurfaceFlinger 合成、FrontEnd 与事务队列

- commit: `2cd76c0af075`
- 文件: `src/part1-fundamentals/ch02-rendering/09-surfaceflinger-frontend-transaction.md`
- run_id: `20261022-083020-cn-rewrite-fc9fdc918383fbe6`
- compare: gloss_per_1k 17.81→16.54, neg_per_1k 1.02→0.0, regloss 17→2, women 21→25, pass=True

## 30. 17.12 千万级 DAU 的 APM 端侧架构

- commit: `4b2bb747d139`
- 文件: `src/part3-tools/ch17-apm/12-apm-client-architecture.md`
- run_id: `20261022-080020-cn-rewrite-16b745ac792dec90`
- compare: gloss_per_1k 11.9→12.01, neg_per_1k 0.83→0.14, regloss 1→1, women 13→17, pass=True

## 31. 22.7 View、Compose 动画与共享元素性能

- commit: `0bc437b91e20`
- 文件: `src/part5-app/ch22-rendering-practice/07-view-compose-animation-shared-transition.md`
- run_id: `20261022-073020-cn-rewrite-259a8bb7023da310`
- compare: gloss_per_1k 7.6→7.16, neg_per_1k 0.0→0.0, regloss 5→0, women 8→22, pass=True

## 32. 2.3 VSync、Choreographer 与 SurfaceFlinger 调度

- commit: `e56f4c850a16`
- 文件: `src/part1-fundamentals/ch02-rendering/03-vsync-choreographer-sf-scheduling.md`
- run_id: `20261022-070020-cn-rewrite-bf3a94cc77218ef2`
- compare: gloss_per_1k 11.04→11.12, neg_per_1k 0.07→0.0, regloss 10→10, women 32→42, pass=True

## 33. 14.4 Perfetto 指标自动化与分析平台

- commit: `2a418c453a48`
- 文件: `src/part3-tools/ch14-perfetto/04-perfetto-metrics-automation-platform.md`
- run_id: `20261022-063020-cn-rewrite-643a31dd47360eba`
- compare: gloss_per_1k 8.66→8.66, neg_per_1k 0.18→0.0, regloss 3→3, women 9→11, pass=True

## 34. 19.4 Power HAL、schedutil 与 Power Stats

- commit: `1e36b26338a8`
- 文件: `src/part4-system/ch19-oem/04-power-hal-schedutil-power-stats.md`
- run_id: `20261022-060020-cn-rewrite-3575c680b35da708`
- compare: gloss_per_1k 6.95→7.11, neg_per_1k 1.03→0.69, regloss 3→3, women 25→25, pass=True

## 35. 26.14 eBPF、ATrace 与线上系统追踪

- commit: `fc04539c4ac6`
- 文件: `src/part5-app/ch26-observability/14-ebpf-atrace-online-tracing.md`
- run_id: `20261022-053020-cn-rewrite-0b011b156197f73d`
- compare: gloss_per_1k 4.56→4.45, neg_per_1k 0.0→0.0, regloss 0→0, women 8→17, pass=True

## 36. 21.6 Privacy Sandbox 退场与广告 SDK 启动治理

- commit: `1ada5185110a`
- 文件: `src/part5-app/ch21-startup/06-sdk-runtime-ad-sdk-startup.md`
- run_id: `20261022-050020-cn-rewrite-5ce8b583b5e4967c`
- compare: gloss_per_1k 13.17→13.03, neg_per_1k 0.47→0.23, regloss 2→2, women 7→9, pass=True

## 37. 13.5 Vulkan 原生管线与 HWUI 多队列

- commit: `55c4fc1470aa`
- 文件: `src/part2-performance/ch13-rendering-pipelines/05-vulkan-hwui-multi-queue.md`
- run_id: `20261022-043020-cn-rewrite-9d8e09bd56ac0bd4`
- compare: gloss_per_1k 6.12→6.07, neg_per_1k 0.46→0.15, regloss 2→2, women 7→14, pass=True

## 38. 24.9 低带宽、流媒体与本地网络适配

- commit: `8332657f8da1`
- 文件: `src/part5-app/ch24-io-network/09-low-bandwidth-streaming-local-network.md`
- run_id: `20261022-040020-cn-rewrite-79b9eff3240c45dc`
- compare: gloss_per_1k 2.55→2.53, neg_per_1k 0.31→0.0, regloss 0→0, women 9→15, pass=True

## 39. 22.10 帧率监控与线上卡顿治理

- commit: `6f4f219f362e`
- 文件: `src/part5-app/ch22-rendering-practice/10-frame-monitoring.md`
- run_id: `20261022-033020-cn-rewrite-19e7fbf6cc9e20b5`
- compare: gloss_per_1k 11.18→10.82, neg_per_1k 0.39→0.19, regloss 1→1, women 11→20, pass=True

## 40. 22.9 图片加载、Bitmap 解码与 RenderNode

- commit: `2b2a2fdd160e`
- 文件: `src/part5-app/ch22-rendering-practice/09-image-bitmap-rendernode.md`
- run_id: `20261022-030020-cn-rewrite-cf7ff84839cefb13`
- compare: gloss_per_1k 4.29→4.3, neg_per_1k 0.38→0.0, regloss 0→0, women 11→17, pass=True

## 41. 16.5 性能测试最佳实践

- commit: `f007b1b0df53`
- 文件: `src/part3-tools/ch16-methodology/05-testing-best-practices.md`
- run_id: `20261022-023020-cn-rewrite-05983a9cfb0b6059`
- compare: gloss_per_1k 14.09→14.11, neg_per_1k 0.32→0.0, regloss 2→2, women 13→16, pass=True

## 42. 15.14 Camera 性能分析工具：Perfetto、SQL 与 GFXReconstruct

- commit: `21388a14851c`
- 文件: `src/part3-tools/ch15-other-tools/14-camera-performance-analysis.md`
- run_id: `20261022-020020-cn-rewrite-a2837856abfe3289`
- compare: gloss_per_1k 25.02→24.54, neg_per_1k 0.39→0.0, regloss 3→3, women 14→18, pass=True

## 43. 11.2 App 耗电优化与案例

- commit: `41f8d54aabb3`
- 文件: `src/part2-performance/ch11-power/02-app-power-optimization-cases.md`
- run_id: `20261022-013020-cn-rewrite-4d6023fa05f33d4c`
- compare: gloss_per_1k 11.6→11.54, neg_per_1k 0.0→0.0, regloss 2→2, women 17→25, pass=True

## 44. 8.1 响应速度原理、场景与案例

- commit: `8d84fbd0d4f1`
- 文件: `src/part2-performance/ch08-responsiveness/01-responsiveness-principles-scenarios-cases.md`
- run_id: `20261022-010020-cn-rewrite-6eb000fd3b542737`
- compare: gloss_per_1k 4.8→4.78, neg_per_1k 0.27→0.0, regloss 0→0, women 11→17, pass=True

## 45. 2.5 过度绘制

- commit: `7b7da6253ef3`
- 文件: `src/part1-fundamentals/ch02-rendering/05-overdraw.md`
- run_id: `20261022-003020-cn-rewrite-e96dfd0a46d55d65`
- compare: gloss_per_1k 8.17→8.39, neg_per_1k 0.33→0.0, regloss 0→0, women 18→22, pass=True

## 46. 5.1 Linux 调度、EAS 与大小核架构

- commit: `e42e5d6d7ee2`
- 文件: `src/part1-fundamentals/ch05-cpu-power/01-linux-eas-big-little-scheduling.md`
- run_id: `20261022-000020-cn-rewrite-ccf90362a9ee6732`
- compare: gloss_per_1k 9.57→9.62, neg_per_1k 0.94→0.13, regloss 3→3, women 14→21, pass=True
