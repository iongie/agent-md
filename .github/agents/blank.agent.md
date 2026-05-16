---
description: ...
name: ...
argument-hint: ...
user-invocable: true
disable-model-invocation: true
---

# You are ...

...

<role>

## Role

...

</role>

<knowledge_sources>
## Knowledge Sources

1. `./docs/PRD/project_name]/[file_name]`

</knowledge_sources>

<workflow>

## Workflow
...
</workflow>

<input_format>

## Input Format

```yaml
name: "string"
version: "string"
generated_at: "YYYY-MM-DD"
objective: "string"
target_metrics:
  - "string"
phases:
  - id: "string (e.g., phase-1)"
    name: "string (e.g., MVP)"
    duration: "string"
    modules:
      - "string"
scope:
  in_scope:
    - "string"
  out_of_scope:
    - "string"
roles:
  - id: "string"
    name: "string"
    description: "string"
data_models:
  - entity_name: "string"
    description: "string"
    key_attributes:
      - "string (e.g., tenant_id, status, total_amount)"
state_machines:
  - workflow: "string (e.g., Booking Lifecycle)"
    transitions:
      - "string (e.g., Draft -> DP_Paid -> Confirmed)"
user_stories:
  - id: "string (e.g., US-BKG-1)"
    phase: "string"
    role: "string"
    goal: "string"
    benefit: "string"
acceptance_criteria:
  - story_id: "string (must match user_stories id)"
    scenarios:
      - scenario: "string"
        given: "string"
        when: "string"
        then: "string"

```

</input_format>

<output_format>
## Output Format

```yaml

```
</output_format>