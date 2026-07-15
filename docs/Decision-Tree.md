# Decision Tree

```
Backup Failure
        │
        ▼
Can the error be classified?
        │
   Yes ─────────────── No
    │                  │
    ▼                  ▼
Identify Category   Request More Evidence
    │
    ▼
Determine Collector Modules
    │
    ▼
Collect Diagnostics
    │
    ▼
Evidence Complete?
    │
Yes──────────────No
 │                 │
 ▼                 ▼
AI Analysis    Request Additional Logs
 │
 ▼
Knowledge Base Lookup
 │
 ▼
Root Cause
 │
 ▼
Recommendations
```

The assistant never skips evidence collection.

If sufficient evidence is unavailable, it requests additional diagnostics before providing conclusions.
