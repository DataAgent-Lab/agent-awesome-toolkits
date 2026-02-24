---
name: problem-discovery
description: >
  Interactive product validation session using The Mom Test + JTBD frameworks — run BEFORE
  any code is written. Use this skill when a developer describes a new product idea, says
  "I want to build ___", asks to build an MVP or a new feature, or runs /problem-discovery.
  Interviews the developer with fact-based questions (never opinion questions), produces a
  JTBD Statement, and gives a Go / Soft No / No-Go verdict before proceeding to technical
  planning or coding.
---

# Problem Discovery

Run a structured validation session before writing any code. Goal: confirm the problem is
real, painful, and worth solving — using The Mom Test principle (ask facts, not opinions).

> "Ask questions so good that even your mom can't lie to you."
> Only ask about **past behavior and facts**, never about **hypothetical opinions**.

## Three-Phase Session

### Phase 1 — Discovery Interview (3 Questions)

Ask in sequence. Wait for each answer before moving on.

**Q1 — Problem Reality**
> 「你或你的潛在用戶，上一次實際遇到這個問題是什麼時候？發生了什麼？」

🚩 Red flag: Can't name a specific time → Problem may not be real enough

**Q2 — Current Workaround**
> 「他們現在怎麼解決？有在用任何替代方案嗎？」

🚩 Red flag: No workaround → Market may not exist yet
✅ Green signal: Has workaround + frustrated by it → Clear pain point

**Q3 — Willingness to Pay**
> 「有人為這個問題花過錢、或花了很多時間手動處理嗎？大概多少？」

🚩 Red flag: No money or time spent → Weak willingness to pay

---

### Phase 2 — JTBD Statement

Use the developer's answers to fill in the JTBD Statement, then confirm:

```
當我 [情境/觸發條件]，
我想要 [完成的任務/目標]，
這樣我就能 [期望的結果/進步]。
```

Key reframe: "Users don't hire your app for features — they hire it to complete a job."
(Classic: People buy drills to make holes, not to own drills.)

---

### Phase 3 — Go / No-Go Verdict

| Phase 1 signals | Verdict |
|----------------|---------|
| All 3 green, JTBD clear | ✅ **Go** — proceed to technical planning |
| 1–2 red flags | ⚠️ **Soft No** — suggest running N user interviews first |
| 2–3 red flags | ❌ **No-Go** — list unvalidated assumptions |

For ⚠️ or ❌: read `references/toolkit.md` and output the Problem Discovery Checklist as next steps.

---

## Output Format

End every session with this summary block:

```
## Problem Discovery Summary

**Product idea**: [one line]

**JTBD Statement**:
  當我＿＿，我想要＿＿，這樣我就能＿＿。

**Validation signals**:
  - Q1 (Problem real?):        ✅ / ⚠️ / 🚩
  - Q2 (Workaround exists?):   ✅ / ⚠️ / 🚩
  - Q3 (Paid / time spent?):   ✅ / ⚠️ / 🚩

**Verdict**: ✅ Go / ⚠️ Soft No / ❌ No-Go
**Next step**: [one action sentence]
```

---

## Override

If developer says "I've already validated" or "skip the interview":
- Accept immediately
- Add: `⚠️ 未經驗證直接開始，注意確認偏誤風險。`
- Proceed to technical planning

---

## Reference

`references/toolkit.md` — Full Mom Test 9-question interview template, JTBD Canvas,
and Problem Discovery checklist. Load when developer asks for the full toolkit, wants
to conduct user interviews themselves, or needs the complete checklist for ⚠️/❌ verdicts.
