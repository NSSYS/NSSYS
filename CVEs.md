# CVE & Security Advisory Portfolio

[← Back to profile](README.md)

This index tracks **16 public CVE identifiers** associated with my vulnerability research and coordinated disclosure work, with links to the underlying public CVE records and vendor advisories. Each entry should be evaluated against the official advisory for scope, affected versions, fixes and attribution.

Researcher: **Ali Saifeldin / [@NSSYS](https://github.com/NSSYS)**.

> Disclosure and credit note: Some advisories cover multiple reported endpoints or researchers. Inclusion here reflects related research and disclosure correspondence, not a claim of exclusive discovery. A small number of reporter-credit details are being reconciled with maintainers. I do not count unassigned or private reports as CVEs.

## Frappe Framework and ERPNext

### Frappe Framework

| CVE | Description | Advisory |
|---|---|---|
| [CVE-2026-44207](https://www.cve.org/CVERecord?id=CVE-2026-44207) | IDOR exposing other users’ email account configuration | [GHSA-cw6v-39qx-7r74](https://github.com/frappe/frappe/security/advisories/GHSA-cw6v-39qx-7r74) |
| [CVE-2026-50026](https://www.cve.org/CVERecord?id=CVE-2026-50026) | Missing permission checks in relink and set_email_password | [GHSA-q6m6-759h-46jp](https://github.com/frappe/frappe/security/advisories/GHSA-q6m6-759h-46jp) |
| [CVE-2026-44208](https://www.cve.org/CVERecord?id=CVE-2026-44208) | Authorization bypass in submit_discussion | [GHSA-xh7m-j2j2-82f2](https://github.com/frappe/frappe/security/advisories/GHSA-xh7m-j2j2-82f2) |
| [CVE-2026-44975](https://www.cve.org/CVERecord?id=CVE-2026-44975) | Missing authorization in form-tour reset | [GHSA-9cxj-48g3-jx22](https://github.com/frappe/frappe/security/advisories/GHSA-9cxj-48g3-jx22) |
| [CVE-2026-44976](https://www.cve.org/CVERecord?id=CVE-2026-44976) | IDOR in onboarding-step updates | [GHSA-78rj-jch8-42m8](https://github.com/frappe/frappe/security/advisories/GHSA-78rj-jch8-42m8) |
| [CVE-2026-47422](https://www.cve.org/CVERecord?id=CVE-2026-47422) | Unrestricted access to save_report / reportview API | [GHSA-w8g7-j846-j248](https://github.com/frappe/frappe/security/advisories/GHSA-w8g7-j846-j248) |
| [CVE-2026-47765](https://www.cve.org/CVERecord?id=CVE-2026-47765) | Improper authorization for document restore operations | [GHSA-cjjx-3v2x-37mf](https://github.com/frappe/frappe/security/advisories/GHSA-cjjx-3v2x-37mf) |

### ERPNext

| CVE | Description | Advisory |
|---|---|---|
| [CVE-2026-72907](https://www.cve.org/CVERecord?id=CVE-2026-72907) | Access control bypass in accounting master record creation | [GHSA-94v6-784v-24q5](https://github.com/frappe/erpnext/security/advisories/GHSA-94v6-784v-24q5) |
| [CVE-2026-109667](https://www.cve.org/CVERecord?id=CVE-2026-109667) | Privilege escalation through unauthorized record creation | [GHSA-x635-wr4c-7345](https://github.com/frappe/erpnext/security/advisories/GHSA-x635-wr4c-7345) |
| [CVE-2026-109668](https://www.cve.org/CVERecord?id=CVE-2026-109668) | Unauthorized modification of customer/party records | [GHSA-5mcx-cjjh-gc64](https://github.com/frappe/erpnext/security/advisories/GHSA-5mcx-cjjh-gc64) |
| [CVE-2026-109669](https://www.cve.org/CVERecord?id=CVE-2026-109669) | Broken authorization in record status updates | [GHSA-6m66-w2qq-v5f8](https://github.com/frappe/erpnext/security/advisories/GHSA-6m66-w2qq-v5f8) |
| [CVE-2026-109665](https://www.cve.org/CVERecord?id=CVE-2026-109665) | Missing authorization for deactivating master records | [GHSA-j57j-p235-x5mx](https://github.com/frappe/erpnext/security/advisories/GHSA-j57j-p235-x5mx) |
| [CVE-2026-109666](https://www.cve.org/CVERecord?id=CVE-2026-109666) | Unauthorized changes to inventory/supplier records | [GHSA-6rgf-xx2m-fjr2](https://github.com/frappe/erpnext/security/advisories/GHSA-6rgf-xx2m-fjr2) |

## Other published CVEs

| Product | CVE | Description | Reference |
|---|---|---|---|
| Node.js | [CVE-2026-48615](https://www.cve.org/CVERecord?id=CVE-2026-48615) | Proxy credentials exposed through tunnel error handling | [Security release](https://nodejs.org/en/blog/vulnerability/june-2026-security-releases) |
| Pyrus Sync for Windows | [CVE-2026-116596](https://www.cve.org/CVERecord?id=CVE-2026-116596) | Local privilege escalation through LocalSystem WCF service | [Research article](https://medium.com/@alisaifeldin/cve-2026-116596-local-privilege-escalation-in-pyrus-sync-for-windows-0fe2417dc8cf) |
| pyLoad | [CVE-2026-45306](https://www.cve.org/CVERecord?id=CVE-2026-45306) | Incomplete path restriction allowing Flask session file disclosure | [GHSA-w727-595x-pc3r](https://github.com/pyload/pyload/security/advisories/GHSA-w727-595x-pc3r) |

## Additional published GitHub advisories

These are **additional public security advisories**, **not included in the 16-CVE count**.

| Project | Advisory | Finding |
|---|---|---|
| CRUDAdmin | [GHSA-4cwg-f726-9hfv](https://github.com/benavlabs/crudadmin/security/advisories/GHSA-4cwg-f726-9hfv) | Missing rate limiting on the login endpoint |
| CRUDAdmin | [GHSA-fv5q-2mg9-c62x](https://github.com/benavlabs/crudadmin/security/advisories/GHSA-fv5q-2mg9-c62x) | IP address spoofing through untrusted X-Forwarded-For |

## Published CVE linked to a reported issue — attribution pending

The following published advisory is **not included in the 16-CVE credited research count** while researcher attribution is being verified with the vendor.

| Original report | CVE / Advisory | Reported impact | Attribution status |
|---|---|---|---|
| ERPNext **#66692** — `pause_job_for_doc` (reported 26 April 2026) | [CVE-2026-72910](https://www.cve.org/CVERecord?id=CVE-2026-72910) · [GHSA-qpvh-75wh-j645](https://github.com/frappe/erpnext/security/advisories/GHSA-qpvh-75wh-j645) | Authenticated low-privileged users could change the status of payment reconciliation records without appropriate write authorization. The published advisory covers this function together with other ERPNext endpoints. | Frappe confirmed that the reported issue had been patched on 21 June 2026 and promised a security advisory with due credit. The public GHSA currently credits a different reporter; confirmation or addition of **@NSSYS** is pending with the vendor. |

**Scope:** ERPNext versions before **15.112.0** and **16.22.0** are affected; the advisory assigns **CVSS 3.1: 7.1 (High)**. This entry documents an overlap between a submitted report and a public advisory; it does not claim exclusive discovery or confirmed reporter credit.

## Research article

[CVE-2026-116596 — Local Privilege Escalation in Pyrus Sync for Windows](https://medium.com/@alisaifeldin/cve-2026-116596-local-privilege-escalation-in-pyrus-sync-for-windows-0fe2417dc8cf)

---
