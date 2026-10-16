# 项目经验索引

> 本文件用于在新任务开始前快速检索历史经验。
> 带 `[种子]` 标记的条目是预置参考案例，不计入真实完成项目。
> 真实项目使用日期文件名（例如 `2026-05-16_*`），种子案例使用 `seed-*`。

## 统计

- 真实项目数：25
- 种子参考数：17
- 总条目数：42
- 最近更新：2026-10-16

## 按场景分类

### APK / Android 逆向

- [2026-08-20 Flutter AOT 服务端驱动广告去除（Blutter + 等长字符串替换）](./2026-08-20_apk-flutter-banner-ad-removal.md)
- [2026-05-15-cellular-pro-mumu-ksad-fragment-fix](./2026-05-15-cellular-pro-mumu-ksad-fragment-fix.md)
- [[种子] seed-008_apk-okhttp-ssl-pin-bypass](./seed-008_apk-okhttp-ssl-pin-bypass.md)

### 二进制 / 固件 / CTF

- [2026-08-06_cortex-m-msc-firmware-self-keyed-rotate-xor](./2026-08-06_cortex-m-msc-firmware-self-keyed-rotate-xor.md)
- [2026-07-22 Electron Bytenode 特权更新链分析](./2026-07-22_electron-bytenode-privileged-update-chain.md)
- [2026-07-14_android-arm64-self-extract-source-recovery](./2026-07-14_android-arm64-self-extract-source-recovery.md)
- [2026-05-15_lumine-go-reverse](./2026-05-15_lumine-go-reverse.md)
- [[种子] seed-001_elf-packed-loader](./seed-001_elf-packed-loader.md)
- [[种子] seed-002_go-malware-stripped](./seed-002_go-malware-stripped.md)
- [[种子] seed-010_ctf-pwn-rop-x64](./seed-010_ctf-pwn-rop-x64.md)
- [[种子] seed-011_pcap-protocol-reverse](./seed-011_pcap-protocol-reverse.md)
- [[种子] seed-014_unity-il2cpp-reverse](./seed-014_unity-il2cpp-reverse.md)
- [[种子] seed-015_iot-firmware-uart](./seed-015_iot-firmware-uart.md)

### Web / API / 渗透测试

- [2026-08-01 Next.js CDK 契约保真本地重建](./2026-08-01_nextjs-cdk-contract-faithful-local-reconstruction.md)
- [2026-08-01_pentest-encryption-oracle-public-template-sql-admin-takeover: .NET CMS 通用加密 oracle、公开密文模板消费者、完整 STL/模板解析、原始 SQL `UPDATE RETURNING`、官方管理员验证器新旧口令差分与隔离 PostgreSQL 清理闭环](./2026-08-01_pentest-encryption-oracle-public-template-sql-admin-takeover.md)

- [2026-07-18_gin-juice-client-friction](./2026-07-18_gin-juice-client-friction.md)
- [2026-07-05_dsl-vm-captcha-reverse](./2026-07-05_dsl-vm-captcha-reverse.md)
- [2026-06-29_burp-mcp-full-test-and-fix](./2026-06-29_burp-mcp-full-test-and-fix.md)
- [2026-05-26_pentest-newapi-rate-limit-bypass](./2026-05-26_pentest-newapi-rate-limit-bypass.md)
- [2026-05-25_pentest-cf-access-sibling-subdomain-cookie-poisoning](./2026-05-25_pentest-cf-access-sibling-subdomain-cookie-poisoning.md)
- [2026-05-17_pentest-vue-spa-actuator-leak](./2026-05-17_pentest-vue-spa-actuator-leak.md)
- [2026-05-16_pentest-personalblog-fun-mass-assignment](./2026-05-16_pentest-personalblog-fun-mass-assignment.md)
- [[种子] seed-003_web-api-auth-bypass](./seed-003_web-api-auth-bypass.md)
- [[种子] seed-004_js-sign-webpack](./seed-004_js-sign-webpack.md)
- [[种子] seed-006_ssrf-cloud-metadata](./seed-006_ssrf-cloud-metadata.md)
- [[种子] seed-017_xxe-oob-exfil](./seed-017_xxe-oob-exfil.md)

- [2026-10-16 CDP 补 Playwright 拿不到的运行时证据（initiator 调用栈 / 断点取参）](./2026-10-16_cdp-runtime-recovery-vs-playwright.md)
### 企业内网 / 云安全

- [[种子] seed-005_ad-certipy-esc1](./seed-005_ad-certipy-esc1.md)
- [[种子] seed-007_ntlm-relay-coercer](./seed-007_ntlm-relay-coercer.md)
- [[种子] seed-013_kerberoasting-spn](./seed-013_kerberoasting-spn.md)
- [[种子] seed-016_k8s-container-escape](./seed-016_k8s-container-escape.md)

### iOS 逆向

- [[种子] seed-009_ios-jailbr&#101;ak-detect-bypass](./seed-009_ios-jailbr%65ak-detect-bypass.md)

### 工具链与环境

- [2026-09-03 多 Issue/PR 安全边界集成](./2026-09-03_issue-pr-security-boundary-integration.md)
- [2026-08-17 tool-index r2 fallback 与 powershell/pwsh 子进程入口统一](./2026-08-17_tool-index-r2-fallback-powershell-pwsh-host-fix.md)
- [2026-08-14 Windows PowerShell 原生命令退出码 PR 审查](./2026-08-14_windows-powershell-native-exit-code-pr-review.md)
- [2026-08-08 平台无关结构化路由 PR 集成](./2026-08-08_client-neutral-structured-routing-pr-integration.md)
- [2026-07-20_reverse-toolchain-windows-bootstrap](./2026-07-20_reverse-toolchain-windows-bootstrap.md)

- [2026-10-16 中文紧贴 ASCII 关键词导致 \b 词边界失效（.NET 与 Python 双引擎同样受影响）](./2026-10-16_cjk-adjacent-ascii-word-boundary-routing-failure.md)
- [2026-10-16 境内访问境外 API 的传输层三重坑（Node fetch 不读代理 / CF 指纹 / execFile 经 GBK 破坏 UTF-8）](./2026-10-16_cn-network-transport-triple-trap.md)
- [2026-10-16 工具索引 .md/.json 双份漂移、PowerShell 5.1 属性赋值回滚、换行符三连坑](./2026-10-16_tool-index-dual-desync-and-scripting-traps.md)
### 其他

- [2026-08-08 开放 PR 价值分级与安全集成](./2026-08-08_pr-value-triage-and-safe-integration.md)
- [[种子] seed-012_log4shell-jndi-rce](./seed-012_log4shell-jndi-rce.md)

## 高频成功模式（按技术）

### 平台无关路由与供应链门禁

- [隔离 worktree、多 PR 祖先闭环、Git-blob AV 审查与 reference/executable CI 边界](./2026-09-03_issue-pr-security-boundary-integration.md)
- [Resolve-ReverseHostExe 统一子进程入口、r2 .bat fallback、StrictMode hashtable 安全访问](./2026-08-17_tool-index-r2-fallback-powershell-pwsh-host-fix.md)
- [原生命令后立即保存退出码、Windows PowerShell 5.1 实宿主复现、PR head 固定](./2026-08-14_windows-powershell-native-exit-code-pr-review.md)
- [单一 routing.json、多入口 parity、实际安装命令 pin](./2026-08-08_client-neutral-structured-routing-pr-integration.md)

### 固件自定义封装

- [1 KiB 自带掩码 ROR/XOR、Cortex-M 向量 crib、跨固件验证](./2026-08-06_cortex-m-msc-firmware-self-keyed-rotate-xor.md)

### 跨引擎文本匹配与词边界

- [CJK 紧贴 ASCII 时 \b 失效，.NET 与 Python 同时中招；基准用例的「无空格」覆盖盲区](./2026-10-16_cjk-adjacent-ascii-word-boundary-routing-failure.md)

### 境内访问境外 API 的传输层

- [curl 作传输层：读系统代理、过 CF 指纹、body 走临时文件避开 GBK 破坏中文、windowsHide 防弹窗](./2026-10-16_cn-network-transport-triple-trap.md)

### 浏览器运行时取证（CDP 直连）

- [initiator.stack 恢复调用来源、压缩脚本断点必须给 columnNumber、enable 与监听器顺序](./2026-10-16_cdp-runtime-recovery-vs-playwright.md)

### 索引与清单一致性

- [多格式索引必须逐项核对；PowerShell PSCustomObject 属性存在性保护；二进制读写保换行符](./2026-10-16_tool-index-dual-desync-and-scripting-traps.md)

## 实体倒排（按目标特征）

### 多宿主安全技能路由包

- [核心/适配器边界与大 PR 选择性集成](./2026-08-08_client-neutral-structured-routing-pr-integration.md)

### Windows PowerShell 供应链引导脚本

- [powershell/pwsh 子进程入口统一、tool-index .bat fallback、pin gate StrictMode](./2026-08-17_tool-index-r2-fallback-powershell-pwsh-host-fix.md)
- [原生命令输出经过对象管道后退出码失真](./2026-08-14_windows-powershell-native-exit-code-pr-review.md)

### Cortex-M USB MSC 升级器

- [应用/驻留 bootloader 边界与虚拟磁盘写入链路](./2026-08-06_cortex-m-msc-firmware-self-keyed-rotate-xor.md)

### 本地逆向技能路由包（含本地化修复与执行层桥接）

- [路由规则的中文边界缺陷、R3 关键词缺口与基准配对用例](./2026-10-16_cjk-adjacent-ascii-word-boundary-routing-failure.md)
- [工具索引双份漂移与登记脚本的 PowerShell 陷阱](./2026-10-16_tool-index-dual-desync-and-scripting-traps.md)

### 打包 SPA（无 source map）

- [CDP 恢复运行时调用栈与断点入参](./2026-10-16_cdp-runtime-recovery-vs-playwright.md)

## 使用说明

1. 新任务开始前，先按场景分类查找是否有相似记录。
2. 命中真实项目时，优先复用已验证的流程和踩坑记录。
3. 命中种子案例时，只作为方法参考，不视为真实成功记录。
4. 新增经验后，请按 PR 流程更新本索引，避免直接改动共享主线。
