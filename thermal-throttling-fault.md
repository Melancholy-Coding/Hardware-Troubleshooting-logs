## 2. Diagnostic & Troubleshooting Methodology
1. **Workload Isolation & Replication:** Re-ran target applications to replicate failure conditions. Confirmed Fortnite triggered a hard crash within ~10 minutes, while lighter applications did not.
2. **Software & Driver Validation:** Checked OS logs, system files, and validated driver stability. Ruled out software-level anomalies.
3. **Hardware Telemetry Monitoring:** Monitored CPU and GPU thermal curves under load. Identified critical CPU thermal spikes reaching **~92°C** (near TjMax limits) despite a clean, dust-free chassis.
4. **Subsystem Inspection:** Factor-analyzed the system age (6–7 years). Hypothesized that the original thermal compound had undergone dry-out/pump-out degradation, severely inhibiting thermal conductivity between the integrated heat spreader (IHS) and the CPU cooler base.

---

## 5. Verification & Testing
* **Stress Test:** Re-ran Fortnite under identical stress conditions.
* **Telemetry Results:** CPU core temperatures stabilized at **~72°C under sustained load**—a **20°C performance improvement** over pre-repair telemetry.
* **Stability:** Zero BSODs or thermal throttling observed over a 30-minute validation window, exceeding the pre-failure 10-minute crash threshold.
