# Evidence naming rules

Use short, readable names so people can guess the content without opening the file.

**Patterns**
```
ss_[module]_[short].png
vid_[flow]_[short]_[ts].mp4
har_[flow]_[ts].har
log_frontend_[ts].txt
log_[service]_[ts].txt
curl_[endpoint-short]_[ts].txt
payload_[endpoint-short]_[case].json
export_[entity]_[ts].csv
```
Timestamp example: `20251102-1218-UTC`

**Quality bar**
- Legible without zoom
- Tight crop on the broken state
- One clean take
- Exact timestamps
- Device info if relevant

**Redaction**
- Mask tokens, emails, phone numbers, and internal URLs
- Prefer masking over blur so shape stays readable
