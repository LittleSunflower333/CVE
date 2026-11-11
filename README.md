# CVE — Security Disclosures & Portfolio

独立安全研究 / 漏洞披露台账。记录我（[LittleSunflower333](https://github.com/LittleSunflower333)）发现、报告、并在官方公开后披露的安全漏洞。

> ⚠️ 未公开（`submitted` / `acknowledged` / `fixed`）的条目只记录「已上报 + 状态」，不含漏洞细节与 PoC；待官方 advisory 发布后再补完整信息。

## 披露清单

### Halo `2.27.1`

| ID | Vulnerability | CWE | Advisory | Status | CVE | Reported | Disclosed |
|----|---------------|-----|----------|--------|-----|----------|-----------|
| 001 | Memory-exhaustion DoS（解压炸弹） | CWE-409 | [GHSA-hcj6-mhw8-938h](https://github.com/halo-dev/halo/security/advisories/GHSA-hcj6-mhw8-938h) | submitted | — | 2026-11-12 | — |
| 002 | Blind SSRF | CWE-918 | [GHSA-94m5-342v-85pq](https://github.com/halo-dev/halo/security/advisories/GHSA-94m5-342v-85pq) | submitted | — | 2026-11-12 | — |
| 003 | 敏感信息泄露 | CWE-522 | [GHSA-9m7h-m333-p7vx](https://github.com/halo-dev/halo/security/advisories/GHSA-9m7h-m333-p7vx) | submitted | — | 2026-11-12 | — |
| 004 | 2FA（TOTP）绕过 | CWE-287 | [GHSA-g64v-27v6-xgwx](https://github.com/halo-dev/halo/security/advisories/GHSA-g64v-27v6-xgwx) | submitted | — | 2026-11-12 | — |
| 005 | 权限提升 | CWE-269 | [GHSA-7rpg-j9w3-hcx7](https://github.com/halo-dev/halo/security/advisories/GHSA-7rpg-j9w3-hcx7) | submitted | — | 2026-11-11 | — |

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
