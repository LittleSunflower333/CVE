# CVE — Security Disclosures & Portfolio

独立安全研究 / 漏洞披露台账。记录我（[LittleSunflower333](https://github.com/LittleSunflower333)）发现、报告、并在官方公开后披露的安全漏洞。

> ⚠️ 未公开（`submitted` / `acknowledged` / `fixed`）的条目只记录「已上报 + 状态」，不含漏洞细节与 PoC；待官方 advisory 发布后再补完整信息。

## 披露清单

### Halo

> 🔒 未公开：以下 GHSA 链接在官方 advisory 发布前打开会显示 404（还未公开），发布后即可访问。

| ID | Reference |
|----|-----------|
| 001 | [GHSA-hcj6-mhw8-938h](https://github.com/halo-dev/halo/security/advisories/GHSA-hcj6-mhw8-938h) |
| 002 | [GHSA-94m5-342v-85pq](https://github.com/halo-dev/halo/security/advisories/GHSA-94m5-342v-85pq) |
| 003 | [GHSA-9m7h-m333-p7vx](https://github.com/halo-dev/halo/security/advisories/GHSA-9m7h-m333-p7vx) |
| 004 | [GHSA-g64v-27v6-xgwx](https://github.com/halo-dev/halo/security/advisories/GHSA-g64v-27v6-xgwx) |
| 005 | [GHSA-7rpg-j9w3-hcx7](https://github.com/halo-dev/halo/security/advisories/GHSA-7rpg-j9w3-hcx7) |

### JPress

| ID | Vulnerability | CWE | Affected | Reference | Status | CVE | Reported | Disclosed |
|----|---------------|-----|----------|-----------|--------|-----|----------|-----------|
| 006 | Stored XSS（未认证 HTML 上传） | CWE-79 | 5.0.0–5.1.2 | [#197](https://github.com/JPressProjects/jpress/issues/197) | submitted | — | 2026-11-05 | — |
| 007 | Path Traversal（头像路径读取） | CWE-22 | 1.0-rc.7–5.1.2 | [#198](https://github.com/JPressProjects/jpress/issues/198) | submitted | — | 2026-11-06 | — |

## 状态说明

- `submitted` — 已上报，等维护者响应（私密 advisory 或公开 issue）
- `acknowledged` — 维护者已确认
- `fixed` — 已修复
- `published` — 已公开（advisory 已发布）
- `cve_assigned` — 已分配 CVE 编号
- `rejected` / `no_response` — 被拒 / 无响应（考虑走 MITRE 兜底）

## 披露原则

1. 漏洞细节与 PoC 只在官方修复/公开后公开（公开 issue 渠道除外，其内容本就公开）。
2. 未公开漏洞上报走私密渠道（GitHub Security Advisory / `security@`），不公开 issue 0day。
3. 每条漏洞独立编号，公开后回填 CVE 编号与 advisory 链接。
