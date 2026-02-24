# Problem Discovery Toolkit

Full reference for conducting user interviews and product validation.

## Table of Contents
1. [Mom Test Interview Template](#1-mom-test-interview-template)
2. [JTBD Canvas](#2-jtbd-canvas)
3. [Problem Discovery Checklist](#3-problem-discovery-checklist)

---

## 1. Mom Test Interview Template

### Pre-Interview Prep

| Item | Fill in |
|------|---------|
| Interviewee role | ________ |
| Your assumed pain point | ________ |
| Your assumed solution | ________ |
| What assumption are you testing? | ________ |

### Core Questions (ask in order)

**Stage 1 — Confirm the problem exists**

1. 「你上一次遇到 ________ 是什麼時候？」
   → No specific answer = problem isn't painful enough

2. 「那次具體發生了什麼？」
   → Let them describe details; don't fill in gaps for them

3. 「這件事多常發生？」
   → Low frequency = may not be worth solving

**Stage 2 — Confirm willingness to pay**

4. 「你現在怎麼解決這個問題的？」
   → No workaround = problem isn't painful enough
   → Has workaround = there's a market; follow with Q5

5. 「你為那個解決方案花了多少錢/時間？」
   → Paid money = willingness to pay exists
   → Lots of manual time = automation opportunity

6. 「現在的做法，你最不滿意的是什麼？」
   → This is your wedge / entry point

**Stage 3 — Explore need boundaries**

7. 「如果有一個工具能 ________，你會用嗎？」
   → Beware false positives; always follow with Q8

8. 「你願意為這個工具付多少錢？」
   → Hesitation or "depends" = problem isn't painful enough

9. 「你能幫我介紹 2-3 個也有這個問題的人嗎？」
   → Willing to refer = problem is real and they're serious

### Post-Interview Record

| Item | Notes |
|------|-------|
| Date | ________ |
| Interviewee | ________ |
| Problem confirmed? | Yes / No / Unclear |
| Current workaround | ________ |
| Willingness to pay signal | Strong / Medium / Weak |
| Biggest frustration (= wedge) | ________ |
| Which assumption was overturned? | ________ |
| Next action | ________ |

---

## 2. JTBD Canvas

> Don't ask users what features they want. Ask: "What job do you hire this product to do?"

### JTBD Statement Formula

```
當我 [情境/觸發條件]，
我想要 [完成的任務/目標]，
這樣我就能 [期望的結果/進步]。
```

### Examples

```
當我 [通勤路上只有一隻手空著]，
我想要 [快速解決早餐又不弄髒車子]，
這樣我就能 [準時到公司且不餓肚子]。
→ Competitor isn't other milkshakes — it's bananas and bagels.
```

```
當我 [收到客戶的 RAG 系統準確率投訴]，
我想要 [快速找出是檢索還是生成環節出問題]，
這樣我就能 [在 SLA 時間內修復並回報]。
→ User doesn't hire a "monitoring tool" — they hire "fast root-cause identification".
```

### JTBD Canvas (fill in)

| Dimension | Fill in |
|-----------|---------|
| **Trigger context** — When does the user "hire" your product? | ________ |
| **Functional job** — What concrete task do they want done? | ________ |
| **Emotional job** — How do they want to feel? (calm / confident / not anxious) | ________ |
| **Social job** — How do they want to be seen? (professional / efficient / ahead) | ________ |
| **Current alternative** — What do they currently "hire" for this job? | ________ |
| **Switching barrier** — What stops them from switching to your solution? | ________ |
| **Success metric** — How does the user know the job is done? | ________ |

---

## 3. Problem Discovery Checklist

Before writing any line of code, confirm all items:

- [ ] Conducted at least 5 Mom Test interviews
- [ ] Problem independently confirmed by 3+ different users
- [ ] At least 1 existing workaround confirmed (= market exists)
- [ ] Willingness-to-pay signal confirmed (money spent or significant manual time)
- [ ] At least 1 JTBD Statement written
- [ ] Identified the "biggest frustration" (= your entry point)
- [ ] At least 1 assumption has been overturned (if none overturned = you're confirming bias)
