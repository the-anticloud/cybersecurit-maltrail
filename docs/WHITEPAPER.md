# Technical Whitepaper — MALTRAIL

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/stamparm/maltrail
**Category:** CYBERSECURITY

## Abstract

This whitepaper describes the Anticloud integration of `MALTRAIL` (Malicious traffic detection system)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local threat intelligence and malware analysis
2. AIOSS tamper-evident SOC event chain (SIEM-ready)
3. AES-256 encryption for all incident data and forensic evidence
4. Single-binary security tool deployable in air-gapped SOC environments
5. Zero-cloud: all detection, analysis, and response runs locally
6. GPU/CPU equalizer: ML detection on GPU, rule-based on CPU
7. Open STIX/TAXII integration replacing proprietary threat intel feeds
8. Offline MITRE ATT&CK mapping without API dependency

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.