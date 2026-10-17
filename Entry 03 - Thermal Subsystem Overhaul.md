# Entry 03 — Intermittent BSOD and Thermal Overhaul

**Log Type:** `[Real-time]`  
**Date:** September 2026  
**System Profile:** Custom Desktop (Intel Core i5-11600K, Cooler Master Hyper 212 Black Edition)  
**Category:** Hardware Diagnostics / Thermal Remediation / Preventive Maintenance  
**Time to Diagnose & Fix:** ~40 Minutes  

---

## 1. Symptom & Initial Observation
The desktop experienced unexpected Blue Screens of Death (BSOD) and thermal shutdowns exclusively under sustained 3D workloads. Fortnite triggered a hard system crash within ~10 minutes, whereas lighter titles like Roblox ran stably.

**Initial Hypotheses:** Software corruption, unstable system/GPU drivers, or hardware thermal throttling.

## 2. Diagnostic Process
1. **Workload Replication:** Re-ran target applications to test failure conditions. Confirmed Fortnite consistently reproduced a hard crash at the ~10-minute mark.
2. **Software Validation:** Inspected OS event logs, system files, and driver stability. Ruled out software-level anomalies.
3. **Thermal Telemetry Monitoring:** Monitored thermal curves under load. Discovered that the Intel Core i5-11600K spiked critically to **~92°C** under load—approaching its 100°C maximum thermal threshold (TjMax)—despite a clean, dust-free chassis.
4. **Subsystem Age Assessment:** Factored in system age (~6–7 years). Hypothesized that the original thermal compound had undergone dry-out/pump-out degradation, severely inhibiting heat transfer between the i5-11600K integrated heat spreader (IHS) and the Cooler Master Hyper 212 base.

## 3. Root Cause Analysis (RCA)
Thermal paste degradation created extreme thermal resistance. Under sustained load, the i5-11600K rapidly reached its thermal threshold, triggering kernel-level BSODs and hardware safety shutdowns to prevent permanent silicon damage. 

> *Confirmed by the direct temperature drop observed post-remediation.*

## 4. Safety & ESD Protocols
* Powered down the system and disconnected it completely from AC mains power.
* Observed standard Electrostatic Discharge (ESD) handling precautions prior to internal component manipulation.

## 5. Corrective Action & Remediation
1. Removed the Cooler Master Hyper 212 air cooler assembly and inspected contact surfaces.
2. Cleaned degraded thermal interface material (TIM) off both the i5-11600K IHS and cooler base using 99% isopropyl alcohol and lint-free wipes.
3. Applied fresh high-performance thermal paste utilizing an **X-pattern deposition** to guarantee uniform surface coverage and optimal pressure distribution.
4. Reinstalled the cooling assembly, tightening fasteners in a cross pattern to ensure even mounting pressure.

## 6. Verification & Stability Testing
* **Stress Test:** Re-ran Fortnite under identical operational conditions.
* **Telemetry Results:** CPU core temperatures stabilized at **~74°C under sustained load**—a massive **18°C performance improvement** compared to pre-repair metrics.
* **Stability Window:** Zero BSODs, thermal shutdowns, or throttling observed over a 30-minute test window, vastly outperforming the pre-fix 10-minute crash threshold. *(Note: System has remained completely stable in ongoing operation since September 20th, 2026).*

## 7. Prevention & Best Practices
* **Routine Maintenance:** Incorporate thermal paste inspection and replacement into maintenance cycles for aging systems.
* **Hardware Lifecycle Planning:** For legacy client hardware, proactively plan phased component modernization (e.g., noting end-of-life driver updates for secondary components like the GTX 1050 Ti).

---

## Skills Demonstrated
`Hardware Diagnostics` `Thermal Management` `Root Cause Analysis` `Preventive Maintenance` `Verification Testing`
