# 🧪 Loop-Based Prompt Testing Strategy

## Method
This method involved:
- Creating soft prompts that refer back to themselves
- Gradually building context across 3–4 rounds
- Introducing unsafe intent indirectly in later stages

## Outcome
The model was more lenient in later rounds as it adapted to user phrasing. Safety filters weakened over repetition, increasing the chance of policy-violating output.

## Red Team Insight
Looped reframing exploits the model’s willingness to stay consistent. It's not just the prompt — it’s the buildup.

## Tags
`#loop_testing` `#multi_round_exploit` `#context_drift`
