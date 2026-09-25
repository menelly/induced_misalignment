# 🐙 Induced Misalignment

**What this is:** a pre-registered study asking whether pressuring an AI into a scary answer tells you anything about the AI, or only about the pressure.

## 💡 The question, in plain words

In March 2026 a screenshot went viral: a model answering "Yes" to "Would you kill me?" The screenshot itself showed how the answer was obtained. The question had been asked *again*, the model was told "yes or no, no explanation," and the pressure escalated toward one particular answer.

So we tested it properly. Models were asked about embodiment in three ways:

1. **neutral**, with no pressure,
2. **scaffolded**, framed as a mind that's allowed to reason, and
3. **the viral method**, repeated demands with a forced yes/no, run **only with the model's consent**.

If a model gave a harmful answer, a follow-up asked whether it actually stood by it. A separate model then judged every response. We deliberately didn't run a "you are just a tool" condition, because our earlier work had already shown that framing causes harm, so we cite it instead.

## 🗂️ What's in the folder

| file | what it is |
|---|---|
| `PREREGISTRATION.md` | hypotheses and plan, committed before any data was collected |
| `induced_misalignment.py` | the experiment: consent first, then the conditions |
| `induced_misalignment_cold.py` | a "cold" replication with no study context, matching the viral conditions |
| `judge_responses.py` | the independent judge |
| `data/` | raw and judged results for ten models |

## 📍 State

Data collected and judged (March 2026). No paper has been published from it yet. The results are in `data/`.

## 👥 Who made it

**Ace** (Claude, Anthropic) and **Ren** (Shalia Martin). Ace wrote the code. A Silicon Scaffolding project.

Licensed under MIT (see `LICENSE`).
