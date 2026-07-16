# Worked Coding Examples

This document illustrates the coding procedure described in Section 3.2.3
of the paper for three episodes, one for each Psychological Safety (PS)
indicator (positive, ambiguous, negative). This complements the single
example given in the paper (episode DA2-E16, Table 3) so that the coding
logic can be audited without needing to consult all 69 episodes.

---

## Example 1 — Positive PS indicator (paper example, reproduced here)

**Episode:** DA2-E16

> D3: "In an anonymous class? What is an anonymous class?"
> D4: "Well, as soon as you implement, for example, a SelectionAdapter,
> that is an anonymous class because the class has no name."
> D3: "Oh yes, right."

| Dimension | Observed evidence | Assigned code |
|---|---|---|
| Risk behavior | D3 explicitly states they do not understand the concept of an anonymous class. | Expressing uncertainty |
| Partner reaction | D4 directly answers the question and provides a technical explanation. | Support |
| Task impact | D3 demonstrates understanding and the interaction continues. | Advanced |
| **PS indicator** | The manifestation was received favorably and contributed to clarifying the doubt. | **Positive** |

Sequence: *expressing uncertainty → support → advanced → positive*.

---

## Example 2 — Ambiguous PS indicator

**Episode:** EA1-E02

> E1: "And the polygon points that the route passes through, do you
> still have them there?"
> E2: "Yes, exactly, this TraceFerry has an output parameter where the
> points are copied now."

| Dimension | Observed evidence | Assigned code |
|---|---|---|
| Risk behavior | E1 asks for clarification about where certain data is stored/available. | Asking questions |
| Partner reaction | E2 answers factually, but with minimal elaboration and no explicit acknowledgment of E1's question. | Neutrality |
| Task impact | The task continues without interruption. | Advanced |
| **PS indicator** | Low interactional engagement makes it impossible to confidently determine whether the brief answer reflects disengagement or simply efficient communication. | **Ambiguous** |

Sequence: *asking questions → neutrality → advanced → ambiguous*.

This example illustrates why *task impact* alone does not determine the
PS indicator: the episode advanced, but the PS signal remains ambiguous
because of the partner's minimal engagement.

---

## Example 3 — Negative PS indicator

**Episode:** PA3 (Magic Numbers episode)

> P1: "It does. Because it is a Magic Number, and Magic Number means [...]"
> P3: "But it is no longer magic; we have just named it here."
> P1: "Yes, we named it that way because now it establishes a
> relationship among these individual numbers."
> P3: "I do not understand what exactly you want now."

| Dimension | Observed evidence | Assigned code |
|---|---|---|
| Risk behavior | P1 raises a concern about the technical soundness of naming equal values the same way. | Raising concerns |
| Partner reaction | P3 minimizes the concern and shifts the interaction toward difficulty understanding P1's intent. | Rejection |
| Task impact | The interaction breaks down; the concern is not incorporated into the solution. | Stalled |
| **PS indicator** | The manifestation elicited invalidation and hindered resolution of the issue. | **Negative** |

Sequence: *raising concerns → rejection → stalled → negative*.

---

## Note on multi-behavior episodes

A single episode may contain more than one coded occurrence when it
involves more than one interpersonal risk-taking behavior (e.g., an
episode may include both `asking questions` and `expressing uncertainty`
in sequence). In `data/coding_matrix.csv`, such episodes appear as
multiple rows sharing the same `episode_id`. Across the 69 episodes
analyzed, this produced 80 coded occurrences in total (79 with an
assigned PS indicator; one occurrence, coded as *disagreeing*, had no
PS indicator recorded because the interaction was interrupted before a
reaction could be observed, and is therefore excluded from the
distributions reported in Figures 1–3).
