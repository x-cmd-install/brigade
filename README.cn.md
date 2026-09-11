# brigade

[English version](./README.md)

Event-driven scripting for Kubernetes

![brigade](https://repo.x-cmd.io/brigade.svg?lang=zh)

## 安装

```sh
x install brigade
```

## 代码洞察

合计: **56,179** 行代码（覆盖前 5 种语言、共 **373** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 50,033 | 4,231 | 3,598 | 289 |
| Yaml | 2,563 | 1,719 | 153 | 45 |
| Json | 1,147 | 0 | 70 | 18 |
| TypeScript | 991 | 419 | 108 | 20 |
| Makefile | 394 | 38 | 65 | 1 |

## OpenSSF Scorecard 评分

总评分: **3.9 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Maintained** (0/10) — 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/brigadecore/brigade>
- **官网**: <https://brigade.sh/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v2.6.0` (2022-06-09)
- **最近提交**: 2022-09-28
- **Release 含资产**: 12 个

## 流行度

- **Star**: 2,418 · **Fork**: 244 · **开放 issue**: 796 · **贡献者**: 90

## 累计统计

- **发布数**: 55 · **已合并 PR**: 1111 · **开放 PR**: 5 · **已关闭 issue**: 770 · **开放 issue**: 26 · **提交数**: 2046

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 0 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 0 | 0 | 0 | 0 | 1 | 0 |
| last720d | 2024-09-21 | 0 | 0 | 0 | 0 | 2 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [brig-darwin-amd64](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brig-darwin-amd64) | 9.1 MiB | `native/darwin/x64` |
| [brig-darwin-arm64](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brig-darwin-arm64) | 9.0 MiB | `native/darwin/arm64` |
| [brig-linux-amd64](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brig-linux-amd64) | 9.2 MiB | `native/linux/x64` |
| [brig-linux-arm64](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brig-linux-arm64) | 8.8 MiB | `native/linux/arm64` |
| [brig-windows-amd64.exe](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brig-windows-amd64.exe) | 9.2 MiB | `native/win/x64` |
| [brigade2-apiserver-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-apiserver-v2.6.0-SBOM.json) | 44.9 KiB | `other` |
| [brigade2-artemis-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-artemis-v2.6.0-SBOM.json) | 988.3 KiB | `other` |
| [brigade2-git-initializer-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-git-initializer-v2.6.0-SBOM.json) | 208.8 KiB | `other` |
| [brigade2-logger-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-logger-v2.6.0-SBOM.json) | 751.8 KiB | `other` |
| [brigade2-observer-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-observer-v2.6.0-SBOM.json) | 29.8 KiB | `other` |
| [brigade2-scheduler-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-scheduler-v2.6.0-SBOM.json) | 9.0 KiB | `other` |
| [brigade2-worker-v2.6.0-SBOM.json](https://github.com/brigadecore/brigade/releases/download/v2.6.0/brigade2-worker-v2.6.0-SBOM.json) | 913.2 KiB | `other` |

## 改进这些数据

brigade 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `brigade` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/brigade.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T05:19:11Z._
