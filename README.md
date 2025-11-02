# Bug Report Gold Pack - Sample

Write bugs that others can reproduce and fix on the first try.
This repo includes **free sample pages** from the pack so you can copy and use them in your tracker.

👉 Full pack on Gumroad (with category templates, evidence rules, handoff and retest checklists): <YOUR_GUMROAD_LINK>?coupon=GH20

## What is inside
- Core bug template that teams actually read
- One line Environment block that kills many follow-ups
- Severity vs Priority mini matrix to decide in seconds
- Evidence naming rules you can adopt today

## Quick start
Copy the template below into your issue tracker, then adjust the title and steps.

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

## Sample pages
- [samples/core-bug-template.md](samples/core-bug-template.md)
- [samples/severity-priority-mini-matrix.md](samples/severity-priority-mini-matrix.md)
- [samples/environment-line-pattern.md](samples/environment-line-pattern.md)
- [samples/evidence-naming-rules.md](samples/evidence-naming-rules.md)

## Why this helps
Most delays come from missing context, not hard fixes. A clear title, a consistent environment line, and one clean screenshot reduce back-and-forth and make fixes faster.

## License
The sample content in this repo is free for personal and internal company use with attribution. You may adapt it in your own trackers. Do not resell or repackage it as a competing product. See [LICENSE.md](LICENSE.md).

## Credits
Author: Emre Karakaya
