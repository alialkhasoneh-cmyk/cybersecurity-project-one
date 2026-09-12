## DFIR Triage Script

**What it does:** 
An automated Digital Forensics and Incident Response (DFIR) triage tool. It collects data from a target system, including running processes, recently modified files (within a specific time window), and SHA-256 cryptographic hashes for file integrity monitoring.

**Requirements:**
- Python 3.x
- `psutil` (optional, falls back to `subprocess` with `ps aux` if not installed)

**How to run:**
```bash
python triage.py sample_evidence