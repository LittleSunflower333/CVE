# CVE — Security Disclosures & Portfolio

独立安全研究 / 漏洞披露台账。记录我（[LittleSunflower333](https://github.com/LittleSunflower333)）发现、报告、并在官方公开后披露的安全漏洞。

> ⚠️ 未公开（`submitted` / `acknowledged` / `fixed`）的条目只记录「已上报 + 状态」，不含漏洞细节与 PoC；待官方 advisory 发布后再补完整信息。

## 披露清单

| ID | Product | Version | Vulnerability | CWE | Status | CVE | Reported | Disclosed |
|----|---------|---------|---------------|-----|--------|-----|----------|-----------|
| 001 | Halo | 2.27.1 | *(advisory 公开后补标题)* | — | submitted | — | 2026-11-12 | — |

## 状态说明

- `submitted` — 已上报（私密 advisory，等维护者响应）
- `acknowledged` — 维护者已确认
- `fixed` — 已修复
- `published` — 已公开（advisory 已发布）
- `cve_assigned` — 已分配 CVE 编号
- `rejected` / `no_response` — 被拒 / 无响应（考虑走 MITRE 兜底）

## 披露原则

1. 漏洞细节与 PoC 只在官方修复/公开后公开。
2. 上报走私密渠道（GitHub Security Advisory / `security@`），不公开 issue 0day。
3. 每条漏洞独立编号，公开后回填 CVE 编号与 advisory 链接。
