## Failed Login Counter

**What it does:** 
This script parses an SSH authentication log file (`sample_auth.log`) to detect brute-force attack attempts. It counts the total number of failed SSH login attempts and extracts the source IP addresses using regular expressions to report the top 3 offending IPs.

**Requirements:**
- Python 3.x
- Standard libraries only (`re`, `collections`)

**How to run:**
```bash
python failed_login_counter.py








