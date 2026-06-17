# 📝 Engagement Notes Template

> A reusable template for documenting an authorized penetration test or a practice lab.
> Good notes = reproducible findings = a credible report. Copy this for each new target.

---

## Engagement Overview

| Field | Detail |
|---|---|
| **Target / Lab name** | |
| **Date** | |
| **Scope** | *(explicitly authorized targets only)* |
| **Authorization** | *(written permission reference — never test without it)* |
| **Objective** | |

---

## 1. Reconnaissance

**Hosts identified:**
```
(list live hosts here)
```

**Open ports / services:**
```
(port → service → version)
```

**Observations:**
-

---

## 2. Enumeration

**Services investigated:**
-

**Interesting findings (misconfigs, exposed info, versions):**
-

**Prioritized targets (why these first):**
-

---

## 3. Exploitation

> Document each attempt — successful or not. Failures are findings too.

**Finding #1**
- **What:**
- **How it was validated:**
- **Evidence (command / output reference):**
- **Business impact:**
- **Status:** ☐ Confirmed ☐ Attempted ☐ Not exploitable

*(duplicate this block per finding)*

---

## 4. Post-Exploitation

**Access obtained:**
-

**What this access could reach (impact assessment):**
-

**Lateral movement / escalation observations:**
-

---

## 5. Findings Summary (for the report)

| # | Finding | Severity | Affected asset | Remediation |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |

---

## 6. Remediation Recommendations

> Written so a technical team can act, and a manager can understand the priority.

-

---

## 7. Lessons / Personal Notes

> What slowed me down? What would I do faster next time? (This is how you improve.)

-

---

*Part of [Road to CPENT](../README.md) — Coach John, D-CORP Academy*
