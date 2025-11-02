# Severity vs Priority mini matrix

Severity describes technical impact. Priority describes when to act.

**Levels**
- Severity: S1 critical, S2 medium, S3 low
- Priority: P1 now, P2 soon, P3 later

|            | P1 - Now | P2 - Soon | P3 - Later |
|------------|----------|-----------|------------|
| **S1** | Login blocked for all roles. Users cannot enter the app. | Export CSV fails only on Staging. Release depends on it next week. | Admin audit log empty on a rarely used legacy page. No near deadlines. |
| **S2** | Invoice total misrounds for some currencies. Finance needs a fix today. | Search suggestions lag 3 to 4 seconds. Usable but hurts UX. | Push notification badge count off by one. No operational impact. |
| **S3** | Legal footer link wrong during a public launch. Must fix today. | Tooltip clipped on Safari mobile. Content still readable. | Icon misaligned by 2 px on settings page. Cosmetic only. |

**Quick rules**
- People blocked or data at risk -> S1
- Flow works with friction -> S2
- Looks wrong but works -> S3
- Live incident or release blocker -> P1
- Planned next cycle -> P2
- No deadline -> P3

**One line rationales**
- S1 P1: Core flow blocked for all users. No workaround.
- S2 P1: Financial impact today. Manual correction is not safe.
- S1 P2: Critical on Staging only. Needed before next release cut.
- S3 P3: Cosmetic only. No user task is affected.
