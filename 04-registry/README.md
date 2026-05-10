*Part of a thought experiment. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md). Nothing described here is operating.*

---

# Registry

This directory holds the registry's own structural elements: the registry-as-operator's self-registration and the template that would be used when a stop trigger names an authority that is not registered.

The registry itself does not exist as operating infrastructure. The construction proposes a public, append-only record-keeping infrastructure where authorities would file Mechanism Records declaring their scope, harm thresholds, and stop paths; this directory shows what the registry's own internal documents would look like if it operated.

For the broader logic of how registration would work — what the form requires, what the registry validates, how stop triggers would be filed — see the framework documents in [01-framework/](../01-framework/) and the forms in [02-forms/](../02-forms/).

---

## What is here

### [SCBP-REG-0001.md](SCBP-REG-0001.md) — Bounded Power Foundation self-registration

The construction names the Bounded Power Foundation as the registry's hypothetical operator. SCBP-REG-0001 is the Foundation's own Mechanism Record — its declaration of what it would do, what stops it, and how it would be subject to the same framework it applies to others.

This file is interesting for two reasons. First, it is an attempt to make the framework's operator subject to the framework, including provisions that would allow the operator's authority to expire if no affected party convened a renewal review. Second, it serves as a worked example of how a small, indirect-authority entity would fill out the registration form — a useful counterpoint to the larger authorities described in [03-examples/](../03-examples/).

### [UNREG-TEMPLATE.md](UNREG-TEMPLATE.md) — Unregistered authority stub template

Part of the construction is a way to record the fact that someone has filed a stop trigger against an authority that is *not* registered. The framework's claim is that this absence — operating without disclosure — is itself a finding. The UNREG template shows how the registry would record that finding: in the framework's own structural vocabulary, marking every undeclared section as `[Not declared — operating without registration]`.

A stub record is not a registration. It records the visible fact that an authority exists, exercises power, and has not declared what it is, what it is bound by, or how it can be stopped.

---

## Naming and ID conventions described in the construction

Mechanism IDs follow a flat sequence:

```
SCBP-REG-####-v#
```

Where:

- `SCBP-REG` is a fixed prefix indicating registration under this framework
- `####` is a zero-padded sequence number assigned in order of registration
- `v#` is the version of the record (incremented when the record itself is materially updated)

The ID encodes only "the Nth thing registered, in version N." The authority's domain, function, and scope live inside the record — not in the ID. This keeps IDs stable across reclassification and avoids baking a functional claim into an identifier that may later prove inaccurate.

Filenames match the ID with the version stripped: a file would be named `SCBP-REG-####.md` and reflect the current version. The version is recorded inside the file.

---

## Registered authorities

Only the registry's self-registration sits in this directory. No other authorities have filed, and the construction does not anticipate that any will — the experiment is what it would look like if any did, not whether they actually would.

| ID | Mechanism | Status | Notional expiration |
|---|---|---|---|
| [SCBP-REG-0001](SCBP-REG-0001.md) | Bounded Power Foundation — Public Registry and Framework | ACTIVE (within the construction) | 2028-05-05 |

---

*Registry — part of the construction*
*All records are subject to the Structural Constitution.*

---

> *This document is part of a thought experiment. The "Bounded Power Foundation" is a construct of the experiment, not an organization. Nothing described here is operating. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md) for the full framing.*
