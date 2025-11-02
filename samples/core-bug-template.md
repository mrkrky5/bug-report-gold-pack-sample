# Core bug template

Use one action per step. Keep Expected and Actual neutral and testable.

```text
Title: [Module] - [State or Action] - [Impact on user or workflow]
Environment: [Test or Staging or Prod] · Build [id] · Feature flag [on/off]
Steps:
1) ...
2) ...
3) ...
Expected: ...
Actual: ...
Impact: [User or Ops or Data] - who is affected and how
Evidence: ss_[module]_[short].png · har_[flow]_[ts].har · log_[service]_[ts].txt
Severity / Priority: Sx / Py
Links: relates [KEY] · blocks [KEY] · duplicate of [KEY]
Notes: constraints, toggles, time window
```

Example
```text
Title: Orders - export CSV disabled - users cannot download
Environment: Staging · Build 2025.11.02-rc3 · Flag export_v2 on
Steps:
1) Login as role planner
2) Open Orders list
3) Click Export and choose CSV
Expected: CSV download starts and the file has headers
Actual: Export stays disabled and no file is downloaded
Impact: Planners cannot send the daily report
Evidence: ss_orders_export_disabled.png
Severity / Priority: S2 / P1 - medium technical impact with high operational urgency
Links: relates QATA-532
Notes: More frequent between 10:00 and 12:00 UTC
```
