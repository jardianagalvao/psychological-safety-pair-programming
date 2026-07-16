# Codebook — Psychological Safety and Interactional Behaviors in Pair Programming

This codebook consolidates the coding scheme described in Section 3.2.2
of the paper. It is provided as a standalone reference so the coding
logic applied to `data/coding_matrix.csv` can be audited independently
of the manuscript text.

## Unit of analysis

**Interaction episode**: a continuous segment of conversation in which
participants engage with the same technical problem, decision, or topic,
and in which at least one manifestation of interpersonal risk-taking
behavior occurs during task execution.

- **Start criterion:** introduction of a new issue, emergence of a doubt,
  or a clear topic shift.
- **End criterion:** resolution of the issue, abandonment of the topic,
  or a definitive shift in the focus of the interaction.

A single episode may contain more than one coded occurrence when it
involves more than one interpersonal risk-taking behavior.

## Dimension 1 — Interpersonal risk-taking behavior

| Category | Operational definition | Example |
|---|---|---|
| Asking questions | Requests clarification or guidance about the task. | "Do we need to add something here?" |
| Expressing uncertainty | Demonstrates doubt about the correctness of the code or understanding. | "I'm not sure if this is correct." |
| Raising concerns | Points out potential issues or risks in the solution. | "This might break the flow." |
| Challenging/Pointing out errors | Challenges or corrects a mistake in the code or reasoning. | "This is wrong." |
| Proposing changes | Suggests an alternative, modification, or improvement to the current solution. | "Do it on localhost instead of dev-intern." |

## Dimension 2 — Partner's reaction

| Category | Operational definition |
|---|---|
| Support | The partner helped, explained, confirmed, validated, or acknowledged the manifestation. |
| Neutrality | The response was minimal, engagement was absent, or focus shifted without explicitly addressing the issue. |
| Rejection | The response involved irritation, interruption, invalidation, or defensive closure of the conversation. |

## Dimension 3 — Task impact

| Category | Operational definition |
|---|---|
| Advanced | The interaction contributed to clarifying a doubt, solving a problem, refining the solution, or continuing the task. |
| Stalled | The interaction resulted in an impasse, loss of flow, interruption, or abandonment of the topic without clear resolution. |

## Interpretive indicator — Psychological Safety (PS)

Assigned based on the **joint, contextual analysis** of the three
dimensions above, without assuming an automatic correspondence between
individual codes (e.g., "support" does not automatically imply
"positive").

| Category | Operational definition |
|---|---|
| Positive | The manifestation was received favorably, particularly through a supportive reaction, and contributed to clarifying doubts, correcting problems, or advancing the task. |
| Negative | The manifestation elicited rejection, defensiveness, or invalidation, hindering interaction continuity or problem resolution — including evidence of hesitation or avoidance that prevented raising or correcting a relevant issue. |
| Ambiguous | The available evidence did not allow confident determination of whether the partner's reaction supported or undermined PS — including episodes with neutral responses, conflicting signals, or insufficient contextual information. |

**Important:** these indicators refer to evidence observed in *specific
episodes* and should not be interpreted as a direct assessment of the
pair's or team's overall psychological safety.

## Episode identification scheme

Episodes are identified by a code composed of company, session, and
episode identifiers: `[Company][Session]-[Episode]`.

- Companies are represented by a letter (A, B, C, D, E, J, O, or P).
- Sessions are represented by the letter "D" (or similar) followed by a
  sequential number (used as originally assigned in the source
  transcripts).
- Episodes are represented by the letter "E" followed by a sequential
  number.

Example: `DA2-E16` = Company D, Session A2, Episode E16.

## Researcher agreement procedure

Coding was performed independently by two researchers using the
definitions above. Disagreements on episode delimitation or category
assignment were first discussed between the two coders; when consensus
could not be reached, a third researcher made the final determination.

## Theoretical grounding

The coding scheme is grounded in Edmondson's conception of psychological
safety and interpersonal risk-taking (Edmondson, 1999; Edmondson & Lei,
2014), and its application to the Software Engineering context (Santana
et al., 2024). See the paper's reference list for full citations.
