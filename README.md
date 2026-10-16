# Hardware Troubleshooting Logs

Documented hardware diagnostics and break-fix interventions performed on real systems. Designed to demonstrate systematic problem-solving, adherence to safety standards, and rigorous verification workflows for IT support and data center operations.

---

## 🧭 Repository Structure & Methodology

Every entry in this repository follows a standardized incident-response format: **Symptom ➔ Diagnosis ➔ Root Cause ➔ Remediation ➔ Verification.**

### Core Troubleshooting Framework
1. **Safety First:** Disconnect power sources, discharge residual capacitance, and adhere to ESD (Electrostatic Discharge) best practices.
2. **Physical Layer Inspection:** Verify component seating, cable integrity, physical damage, and thermal/dust buildup.
3. **Logical & Configuration Layer:** Review firmware (UEFI/BIOS), system logs (`dmesg`, event logs), and driver states.
4. **Isolation & Testing:** Apply a methodical process of elimination—changing one variable at a time to isolate faulty components.
5. **Documentation & Verification:** Validate repairs under sustained load metrics and document steps to ensure continuous knowledge retention.

---

## 🏷️ Log Classification Legend

To maintain transparency, entries are categorized by when they were documented:

| Label | Meaning |
| :--- | :--- |
| **`[Real-time]`** | Logged live as the diagnostic work and repair were completed. |
| **`[Retroactive]`** | Real-world hardware repairs from past years, documented systematically from engineering notes and memory. |

---

## 📂 Active Incident Logs

* **Log 01 `[Retroactive]`:** [Intermittent BSOD & Thermal Subsystem Overhaul](./logs/log-01-thermal-paste.md) — Diagnosed and remediated severe CPU thermal throttling (~92°C to ~72°C delta) via thermal paste reapplication and hardware lifecycle analysis.
* *(Upcoming)* **Log 02 `[Real-time]`:** Enterprise Storage Drive Replacement & SMART Telemetry Analysis.
* *(Upcoming)* **Log 03 `[Real-time]`:** PSU Rail Testing & Power Fault Isolation.
* *(Upcoming)* **Log 04 `[Real-time]`:** Motherboard POST Failure & Memory Channel Troubleshooting.
