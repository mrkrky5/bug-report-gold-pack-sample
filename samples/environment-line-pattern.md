# Environment line pattern

Paste this before steps. It kills many follow-ups because it pins the context.

```text
Environment: [Test or Staging or Prod] · Build [id or commit] · Feature flags [name on/off] · Browser [name ver] · OS [name ver] · Device [if mobile] · Locale [code]
```

Examples
```text
Environment: Staging · Build 2025.11.02-rc3 · Flags export_v2 on · Chrome 129 · Windows 11 · Locale en-GB
Environment: Test · Build 8b17e42 · Flags pricing_v3 off · Safari iOS 17 on iPhone 13 · Locale tr-TR
Environment: Prod · Build app-2.14.1 · Flags all default · API only
```
