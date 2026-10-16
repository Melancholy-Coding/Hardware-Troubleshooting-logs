# Incident: Intermittent BSOD & Thermal Subsystem Overhaul

**System Profile:** Custom Desktop (Legacy Hardware, ~6–7 years old)  
**Primary Role:** Hardware Diagnostics, Preventive Maintenance, & Thermal Remediation  
**Target Application:** AWS / Enterprise Data Center Hardware Support  

---

## 1. Incident Summary
* **Symptom:** The system experienced unexpected Blue Screens of Death (BSOD) and thermal shutdowns exclusively under sustained 3D workloads (gaming via Fortnite for ~10 minutes; lighter titles like Roblox ran stably).
* **Initial Hypothesis:** Software corruption, unstable GPU/CPU driver overhead, or component thermal throttling.

## 2. Diagnostic & Troubleshooting Methodology
1. **Workload Isolation & Replication:** Re-ran target applications to replicate failure conditions. Confirmed Fortnite triggered a hard crash within ~10 minutes, while lighter applications did not.
2. **Software & Driver Validation:** Checked OS logs, system files, and validated driver stability. Ruled out software-level anomalies.
3. **Hardware Telemetry Monitoring:** Monitored CPU and GPU thermal curves under load. Identified critical CPU thermal spikes reaching **~92°C** (near TjMax limits) despite a clean, dust-free chassis.
4. **Subsystem Inspection:** Factor-analyzed the system age (6–7 years). Hypothesized that the original thermal compound had undergone dry-out/pump-out degradation, severely inhibiting thermal conductivity between the integrated heat spreader (IHS) and the CPU cooler base.

## 3. Root Cause Analysis (RCA)
Thermal paste degradation over 6+ years caused severe thermal resistance. Under sustained load, the CPU rapidly reached thermal TjMax limits, triggering thermal protection shutdowns and kernel-level BSODs to prevent permanent silicon damage.

## 4. Corrective Action & Remediation Plan
1. **Safety Protocol:** Power disconnected, system isolated from AC mains, and standard ESD precautions observed.
2. **Disassembly:** Removed the CPU air cooler assembly and inspected contact surfaces.
3. **Surface Preparation:** Cleaned degraded thermal interface material (TIM) from both the CPU IHS and cooler base using 99% isopropyl alcohol and lint-free wipes.
4. **Reapplication:** Applied fresh high-performance thermal paste utilizing an X-pattern deposition to ensure uniform coverage and optimal pressure distribution.
5. **Reassembly:** Reinstalled the cooling assembly with proper cross-torque pressure on fasteners.

## 5. Verification & Testing
* **Stress Test:** Re-ran Fortnite under identical stress conditions.
* **Telemetry Results:** CPU core temperatures stabilized at **~72°C under sustained load**—a **20°C performance improvement** over pre-repair telemetry.
* **Stability:** Zero BSODs or thermal throttling observed over a 30-minute validation window, exceeding the pre-failure 10-minute crash threshold.

## 6. Lifecycle & Preventative Recommendations
* **Component Aging Note:** Identified that the secondary GPU (GTX 1050 Ti - Pascal architecture) reached end of regular Game Ready driver support (October 2025 transition to security-only updates through October 2028). 
* **Long-term Strategy:** Recommended a phased hardware modernization plan for aging client infrastructure.
