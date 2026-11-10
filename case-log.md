# Case Log: CFReDS Data Leakage

| Timestamp (EST) | Action | Tool | Result |
|---|---|---|---|
| 2026-11-09 22:39 | Verified archive part .001 | Get-FileHash (MD5) | c327db25292296ab10c2670b94ef28b5, matches NIST |
| 2026-11-09 22:39 | Verified archive part .002 | Get-FileHash (MD5) | 8a5185144c7d38c111d5505e3018ba73, matches NIST |
| 2026-11-09 22:39 | Verified archive part .003 | Get-FileHash (MD5) | e155d374d77643a9ff44a664d628bf87, matches NIST |
| 2026-11-09 22:56 | Extracted evidence image from archive | 7-Zip | Archive integrity OK, 21474836480 bytes |
| 2026-11-09 22:56 | Baseline hash of image BEFORE analysis | Get-FileHash (SHA-256) | 026C143638295DB1FBFA598C5B35BCAC4860BA73EC5DA1CC87B67AFD598BE4E2 |
