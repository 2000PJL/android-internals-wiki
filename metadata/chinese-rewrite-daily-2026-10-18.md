# 中文改写抽检 · 2026-10-18

- 提交数: 19
- 生成于: 2026-10-18T23:15:20.361166+08:00

## 1. 7.1 卡顿定义、分类与原因体系

- commit: `9781f32cb86a`
- 文件: `src/part2-performance/ch07-smoothness/01-jank-definition-causes.md`
- run_id: `20261018-223020-cn-rewrite-1eb45e55e33ef560`
- compare: gloss_per_1k 9.64→3.85, neg_per_1k 0.52→0.35, regloss 1→0, women 20→22, pass=True

## 2. 11.2 App 耗电优化与案例

- commit: `69669817c7ea`
- 文件: `src/part2-performance/ch11-power/02-app-power-optimization-cases.md`
- run_id: `20261018-220020-cn-rewrite-4d6023fa05f33d4c`
- compare: gloss_per_1k 11.02→4.04, neg_per_1k 0.69→0.0, regloss 0→0, women 16→17, pass=True

## 3. 1.20 音频链路（Audio Pipeline）延迟与性能

- commit: `1a0bf1cf9088`
- 文件: `src/part1-fundamentals/ch01-architecture/20-audio-pipeline-performance.md`
- run_id: `20261018-213020-cn-rewrite-7eb48a57e0b67f35`
- compare: gloss_per_1k 7.43→3.05, neg_per_1k 4.53→0.8, regloss 2→0, women 0→10, pass=True

## 4. 26.13 heapprofd、procfs CPU 与 Page Fault 分析

- commit: `973e40f3f64a`
- 文件: `src/part5-app/ch26-observability/13-heapprofd-procfs-page-fault.md`
- run_id: `20261018-210020-cn-rewrite-b3de61a6806c300a`
- compare: gloss_per_1k 2.97→1.39, neg_per_1k 3.8→0.14, regloss 0→0, women 18→20, pass=True

## 5. 22.19 App Widget 更新性能：RemoteViews IPC 与 Glance 渲染

- commit: `fede6bb7bb34`
- 文件: `src/part5-app/ch22-rendering-practice/19-app-widget-performance.md`
- run_id: `20261018-203020-cn-rewrite-aa4d2e601f56a0c4`
- compare: gloss_per_1k 3.54→2.11, neg_per_1k 4.66→0.97, regloss 0→0, women 0→10, pass=True

## 6. 22.18 CameraX：UseCase、Camera2 映射与性能

- commit: `ba07c7440a87`
- 文件: `src/part5-app/ch22-rendering-practice/18-camerax-rendering.md`
- run_id: `20261018-200020-cn-rewrite-01ad18871b7a880c`
- compare: gloss_per_1k 5.77→2.98, neg_per_1k 4.49→1.12, regloss 0→0, women 0→20, pass=True

## 7. 20.1 应用稳定性度量、聚合与归因

- commit: `3ce880f28924`
- 文件: `src/part5-app/ch20-stability/01-stability-metrics-aggregation-attribution.md`
- run_id: `20261018-193020-cn-rewrite-321f012c4e738e0e`
- compare: gloss_per_1k 6.02→3.42, neg_per_1k 0.07→0.07, regloss 0→0, women 9→12, pass=True

## 8. 16.1 Android 性能优化原则、实证与治理

- commit: `4797a4bdfb7a`
- 文件: `src/part3-tools/ch16-methodology/01-performance-principles-evidence-governance.md`
- run_id: `20261018-190020-cn-rewrite-4f1d4e134608e76e`
- compare: gloss_per_1k 6.53→4.31, neg_per_1k 0.52→0.45, regloss 0→0, women 18→21, pass=True

## 9. 2.2 帧率、刷新率与显示模式选择

- commit: `aea746c91c67`
- 文件: `src/part1-fundamentals/ch02-rendering/02-framerate-refresh-display-mode.md`
- run_id: `20261018-183020-cn-rewrite-fb8fe93053d6fcf4`
- compare: gloss_per_1k 6.72→3.45, neg_per_1k 0.3→0.25, regloss 0→0, women 21→21, pass=True

## 10. 8.5 Keystore、Biometric 与 Credential 登录性能

- commit: `97457bacacfe`
- 文件: `src/part2-performance/ch08-responsiveness/05-keystore-biometric-credential-login.md`
- run_id: `20261018-180020-cn-rewrite-0021b853f3a4ba1a`
- compare: gloss_per_1k 7.42→2.22, neg_per_1k 2.73→0.26, regloss 1→0, women 9→16, pass=True

## 11. 20.3 Native Crash、堆栈回溯与符号化

- commit: `05bd03bacf95`
- 文件: `src/part5-app/ch20-stability/03-native-crash-unwinding-symbolication.md`
- run_id: `20261018-173020-cn-rewrite-b64e5fb68385808c`
- compare: gloss_per_1k 8.99→3.18, neg_per_1k 1.19→0.69, regloss 1→0, women 9→11, pass=True

## 12. 18.7 Android 17 平台 Rust 性能边界：Binder、CXX 与 Soong

- commit: `85a7beaaf7c7`
- 文件: `src/part4-system/ch18-aosp/07-rust-system-services-performance.md`
- run_id: `20261018-170020-cn-rewrite-19eeca01c18d341f`
- compare: gloss_per_1k 7.95→3.14, neg_per_1k 0.42→0.0, regloss 0→0, women 10→14, pass=True

## 13. 21.7 ART GC 启动期开销与分配治理

- commit: `ca72e7253583`
- 文件: `src/part5-app/ch21-startup/07-art-gc-startup-allocation-governance.md`
- run_id: `20261018-163020-cn-rewrite-afd026b214030c2c`
- compare: gloss_per_1k 14.17→5.48, neg_per_1k 3.54→1.37, regloss 1→0, women 0→14, pass=True

## 14. 17.8 网络 APM 底层捕获原理

- commit: `566fe63a8f06`
- 文件: `src/part3-tools/ch17-apm/08-network-apm-internals.md`
- run_id: `20261018-160020-cn-rewrite-288906d745d4b091`
- compare: gloss_per_1k 4.15→2.07, neg_per_1k 1.92→0.32, regloss 0→0, women 15→16, pass=True

## 15. 1.3 系统启动、Zygote 与图形栈预加载

- commit: `24658648144b`
- 文件: `src/part1-fundamentals/ch01-architecture/03-boot-zygote-graphics-preload.md`
- run_id: `20261018-153020-cn-rewrite-ce43abaaa3ef70ac`
- compare: gloss_per_1k 9.62→1.65, neg_per_1k 0.91→0.27, regloss 6→0, women 18→18, pass=True

## 16. 1.19 Android 显示架构与 WindowManager

- commit: `8b1206f1d688`
- 文件: `src/part1-fundamentals/ch01-architecture/19-display-windowmanager-architecture.md`
- run_id: `20261018-150020-cn-rewrite-f805dc056a83060c`
- compare: gloss_per_1k 9.07→2.23, neg_per_1k 2.32→0.1, regloss 0→0, women 31→28, pass=True

## 17. 25.9 热节流适配与性能退化治理

- commit: `7f203735417f`
- 文件: `src/part5-app/ch25-power-size/09-thermal-throttling-performance.md`
- run_id: `20261018-143020-cn-rewrite-0e16ba0f67fea7ef`
- compare: gloss_per_1k 4.81→1.83, neg_per_1k 1.0→0.0, regloss 0→0, women 8→12, pass=True

## 18. 1.9 Android IPC 全景与 Binder 性能

- commit: `ebf591d6a365`
- 文件: `src/part1-fundamentals/ch01-architecture/09-ipc-binder-performance.md`
- run_id: `20261018-140020-cn-rewrite-f1627a0e30d44ed7`
- compare: gloss_per_1k 7.65→3.2, neg_per_1k 3.98→0.1, regloss 3→0, women 0→10, pass=True

## 19. 5.9 Bluetooth LE Audio 延迟与功耗性能

- commit: `25688c5daf97`
- 文件: `src/part1-fundamentals/ch05-cpu-power/09-bluetooth-le-audio-performance.md`
- run_id: `20261018-000020-cn-rewrite-b956c43c3eab77ee`
- compare: gloss_per_1k 10.48→6.57, neg_per_1k 1.5→0.0, regloss 0→0, women 6→16, pass=True
