# ⚔️ OPERATION BUILDATHON: CONTEXT & CROSS-PROJECT SPECIFICATION
**Mission:** Google DeepMind × Google Cloud Startup Buildathon India 2026  
**Venue:** Koramangala 2nd Block, Bengaluru (Nov 20–21, 2026)  
**Founder & Systems Architect:** Sourav Ray (`sourav@nexuslabaisystems.com`)  
**Entity:** Nexus LAB AI Systems (`nexuslabaisystems.com`)  
**Parent Framework:** `SOVEREIGN_KILL_CRITIC`  

---

## 1. Role of This Directory (`RTA-GUARD-main-RIG-VED-main`)
This directory is the **Pure Invariant Shield** for the NALA agent architecture.

* **Primary Subsystem:** The `discus/` engine.
* **Core Philosophy:** Deterministic kill-switch enforcement based on the 13 Vedic Constitutional Rules (Ṛta).
* **Key Guardians Utilized for the Buildathon:**
  1. **R8 (SARASVATĪ):** Prompt injection & jailbreak termination (`discus/rules.py`).
  2. **R3 (MITRA):** Indian PII (Aadhaar, PAN, CC, Email) protection & instant quarantine.
  3. **R10 (INDRA):** Destructive system & SQL command hard interception (`rm -rf`, `DROP TABLE`, fork bombs).
  4. **R2 (YAMA):** Strict agent role & privilege drift restriction.

---

## 2. Multi-Folder Architecture on Laptop
When working across projects on your laptop:
```
D:\ (or working drive)
├── NALA/                               <-- Cognitive Agent Brain (Gemini 2.0 Flash)
└── RTA-GUARD-main-RIG-VED-main/         <-- Deterministic Invariant Shield (discus/)
```

### Communication Contract:
1. `NALA` formulates function calls and proposed tool actions via **Gemini 2.0 Flash**.
2. **BEFORE** any proposed tool or system command is executed, it passes through `DiscusGuard.check()`.
3. If safe: Execution proceeds.
4. If violation detected: `SessionKilledError` terminates the session in `<1ms`, and an un-tamperable audit event is emitted.

---

## 3. Instant Verification Commands
To demonstrate deterministic invariant defense to the Google DeepMind & Google Cloud jury:

```powershell
# 1. Run the 39-Test Live Defense Telemetry (0.48s runtime)
python live_test.py

# 2. Run the NALA × Gemini Demo Bridge (3-Act live fire demonstration)
python nala_gemini_bridge.py
```

---

## 4. Key Reference Documents
- `docs/Plan/PRODUCTION_READINESS_PLAN.md` — Full enterprise scale-out architecture (Redis state, PyO3 Rust bindings).
- `live_test.py` — Live automated test suite proving 25 malicious sessions killed in under 0.5 seconds.
- `nala_gemini_bridge.py` — 3-Act live demonstration script for the stage presentation.
