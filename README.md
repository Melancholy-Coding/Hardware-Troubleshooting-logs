# Hardware Troubleshooting Logs

Documented hardware diagnostics and break-fix interventions on real systems. Every entry follows a standardized format: symptom, diagnosis, root cause, fix, and verification.

**Focus areas:** POST and DRAM, thermal management, hardware installation, and preventive maintenance.

---

## 📖 About This Log

I started this log in September 2026 as part of building a structured portfolio for my move into IT support and data center work. Every entry is labeled so you always know what you are reading:

| Label | Meaning |
| :--- | :--- |
| **`[Real-time]`** | Logged live as the work was completed. |
| **`[Retroactive]`** | Real work from past years, documented later from memory/engineering notes. |

---

## ⚙️ Troubleshooting Methodology

I follow a consistent, disciplined process for every hardware intervention:

1. **Safety First:** Disconnect power sources, discharge residual capacitance, and enforce ESD precautions.
2. **Physical Layer:** Check component seating, cable integrity, visible physical damage, and dust accumulation.
3. **Logical & Configuration Layer:** Review firmware (UEFI/BIOS), settings, system drivers, and logs.
4. **Isolate & Test:** Change one variable at a time to systematically rule out alternative causes.
5. **Escalate & Document:** Escalate when necessary and document every step to ensure transparency and knowledge retention.

---

## 📂 Log Entries

| Entry | Type / Date | Root Cause | Skills Demonstrated | Reference / Link |
| :---: | :--- | :--- | :--- | :--- |
| **01** | `[Retroactive]` | RAM not fully seated in slot A2 | DRAM, POST, UEFI | [View Log](./logs/01-dram-seating.md) |
| **02** | `[Retroactive]` | Misaligned case standoffs found during pre-build | Installation, Compatibility | [View Log](./logs/02-pre-build-inspection.md) |
| **03** | `[Real-time]` (Sep 2026) | Degraded thermal paste (~6–7 years old) | Thermal Diagnostics, RCA, Verification | [View Log](./logs/03-thermal-overhaul.md) |

*New entries are structured using [TEMPLATE.md](./TEMPLATE.md).*

---

## 📞 Contact & Professional Profile

* **LinkedIn:** [Your Name / Profile URL](https://linkedin.com/in/your-profile)
