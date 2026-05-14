# Data Schema v2

## Purpose

Defines standard field names and allowed values for all Bounded Power registrations.

Use this so humans and AI create compatible records.

---

## Core Record Fields

```yaml
record_id: string
status: draft | reviewed | published | archived
review_date: YYYY-MM-DD
reviewer_alias: string
confidence_level: high | medium | low
version: v2
```

---

## Authority Identity

```yaml
authority_name: string
authority_common_name: string
authority_type:
  - police_department
  - sheriff_department
  - court
  - prosecutor
  - prison
  - school_board
  - university
  - hospital
  - employer
  - hoa
  - regulator
  - platform
  - nonprofit
  - corporation
  - utility
  - other

sector:
  - public
  - private
  - nonprofit
  - hybrid

parent_organization: string
website: string | Unknown
```

---

## Jurisdiction

```yaml
jurisdiction_city: string
jurisdiction_state_province: string
jurisdiction_country: string
service_area: string
```

---

## Power Structure

```yaml
authority_classification:
  - direct
  - delegated
  - hybrid
  - opaque

primary_power_held: string
secondary_powers: list
legal_basis: string
funding_model: string
```

---

## Impact Metrics

```yaml
population_affected_estimate: integer | Unknown

dependency_level:
  - low
  - medium
  - high
  - critical

opt_out_possible:
  - yes
  - partial
  - no
  - unknown

appeals_process_exists:
  - yes
  - partial
  - no
  - unknown

independent_oversight_exists:
  - yes
  - partial
  - no
  - unknown
```

---

## Risk Outputs

```yaml
overall_structural_risk:
  - low
  - moderate
  - high
  - severe

capture_risk:
  - low
  - moderate
  - high
  - severe

dependency_risk:
  - low
  - moderate
  - high
  - severe

recommended_priority:
  - monitor
  - review
  - urgent_review
  - intervention
```

---

## SCBP-04 Scoring Fields

Use:

```yaml
pass
concern
fail
```

For each rule:

```yaml
R01_governance_humility
R04_burden_of_justification
R09_rollback_requirement
R13_unplug_ability
R17_scope_clarity
R21_independent_review
R27_reversibility
R33_no_penalty_for_good_faith_challenge
R41_nonparticipant_protection
R52_expiration_or_renewal_control
```

---

## Required Rules

1. Use Unknown instead of guessing.
2. Dates must be YYYY-MM-DD.
3. Use exact field names.
4. Use lowercase category values.
5. One value per field unless list-type.

```
```
