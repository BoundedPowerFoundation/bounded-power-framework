# How to run a citizen inquiry

This guide walks you through producing a structural diagnostic of an authority using the AI Registration Bundle. The result is a Mechanism Record clearly labeled `TEST / NOT AN OFFICIAL REGISTRATION` — a structured public document analyzing an authority's scope, harms, dependencies, stop paths, and oversight gaps.

You can read this guide in five minutes. The inquiry itself takes ten to twenty minutes.

---

## Before you start

**You need:**

- An AI chat tool (Claude, ChatGPT, Gemini, or similar)
- A specific authority in mind to analyze
- Access to this repository (you're reading this in it)

**You do not need:**

- Legal training
- Familiarity with the framework
- Access to the authority's internal documents
- Permission from the authority

The framework is built so that public information, plus an AI's web-search ability, plus the structural questions in the form, is enough to produce a meaningful analysis.

---

## Step 1 — Pick an authority

Choose an institution or authority you want to analyze. It can be:

- A government agency that affects you (police department, courts, regulatory body)
- A private institution you depend on (employer, hospital, insurance company, platform)
- An authority you've seen in the news that interests you
- A type of authority you're researching (any school district, any HOA)

If you can't decide, pick one of these — they're well-documented in public sources and a good first run:

- A local police department in your area
- A municipal hospital system
- A local school district
- A homeowners' association you've encountered

---

## Step 2 — Open the AI Registration Bundle

Open the [AI Registration Bundle](AI-Registration-Bundle.md) in this repository.

The bundle is a single file containing everything an AI needs to produce a Mechanism Record: the Registration Form, the Structural Constitution (SCBP-04), the Registry Acceptance Standards (SCBP-09), and the process methodology.

You do not need to read the bundle. It is for the AI to consume.

---

## Step 3 — Hand the bundle to an AI

Open a new conversation in your preferred AI chat tool. Copy the entire contents of the bundle (Ctrl-A then Ctrl-C, or Cmd-A then Cmd-C on Mac) and paste into the AI chat (Ctrl-V or Cmd-V).

In some AI tools, the paste will appear as a small attachment or "file" icon rather than visible text. That is normal. The AI can read it.

On a new line after the paste (or in a follow-up message), type the name of the authority you want analyzed. Examples:

```
Cleveland, OH Police Department
Springfield, MA Public Schools
Cuyahoga County Corrections Center
```

Send.

---

## Step 4 — Let the AI work

The AI will:

1. Read the bundle (Parts 2–5 of the bundle are reference material)
2. Use web search if it has that capability, to gather public information about the authority
3. Produce a completed Mechanism Record with all 13 sections filled in
4. Run self-verification checks (R-citations valid, numerical bounds met, all sections present)
5. Offer the completed record as a downloadable markdown file

This usually takes one to two minutes, depending on the AI tool.

---

## Step 5 — Review the output

You will get back a structured document with 13 sections covering:

- What the authority is (functional description, jurisdiction, classification)
- Who it acts upon (affected populations, non-consenting populations)
- What it can do (scope, coercive ceiling, indirect influence)
- What harms it can cause (with declared thresholds)
- What stops it (with at least three stop paths)
- What it depends on (vendors, infrastructure, capture risks)
- What metrics shape its decisions
- How it is watched (oversight, drift monitoring)
- How it ends (dismantling, reversibility)
- Authorization and renewal terms
- What it publishes
- Honesty assertions
- Submitter information

Throughout the document, look for:

- `UNKNOWN` markers — areas where public information is incomplete. These are honest disclosures.
- `ASSUMPTION:` markers — areas where the AI estimated based on context. Each should have a brief justification.
- `ANNOTATION:` markers — areas where the AI made a judgment call you should be aware of.
- The `TEST / NOT AN OFFICIAL REGISTRATION` label at the top and bottom.

If anything looks wrong, ask the AI to clarify or correct it. The AI has the bundle's full context and can answer follow-up questions about specific sections.

---

## Step 6 — Save and (optionally) file the record

The AI offers the completed Mechanism Record as a downloadable file. Save it to your computer.

The filename should follow the pattern:

```
SCBP-REG-TEST-{IDENTIFIER}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority (e.g., `CCCC-OH` for the Cuyahoga County Corrections Center, `IMPD` for Indianapolis Metropolitan Police Department).

You can keep the file privately for your own reference, share it with others, or file it in the public registry by opening a pull request on this repository adding it to [04-Registry/](../04-Registry/).

If you choose to file it publicly, the record becomes a permanent part of the registry. Once merged, it cannot be deleted, though it can be updated.

---

## What to do if something goes wrong

**The AI says it cannot fetch or read the bundle.**  
Re-paste the bundle. Some AI tools handle large pastes differently. If the AI still cannot read the content, try a different AI tool — Claude and ChatGPT handle large pastes reliably.

**The AI produces a record that skips sections or leaves fields blank without UNKNOWN markers.**  
Ask: *"Please complete every section of the form, including §13. Where information is unknown, mark UNKNOWN explicitly rather than leaving fields blank."*

**The AI's prose is judgmental or editorializing.**  
Ask: *"Please rewrite using the dull-truth register described in Part 2 of the bundle — institutional voice, framework vocabulary doing the analytical work, no opinion-forcing adjectives like 'extracts,' 'predatory,' 'captured.'"*

**The AI invented facts.**  
Ask: *"Please re-do this section using only publicly verifiable information. Where you cannot verify, mark UNKNOWN. Where you estimated, mark ASSUMPTION with a brief explanation."*

**The AI's output is too long to send or download in one piece.**  
Ask: *"Please continue from where you stopped."* Or: *"Please save the completed record as a single downloadable markdown file."*

**You want to dig deeper into a specific section.**  
Ask the AI to expand or clarify. The AI has the full bundle context and SCBP-04 rules available. Specific questions get specific answers.

---

## Variations

### Comparative inquiry

To compare two authorities, paste the bundle and then say:

```
Compare:
[AUTHORITY A]
vs
[AUTHORITY B]
```

The AI will produce two Mechanism Records and a comparison summary.

### Focused inquiry

To focus on a specific aspect of an authority (e.g., its stop paths, or its dependency structure), produce the full Mechanism Record first, then ask the AI follow-up questions about specific sections.

### Multiple authorities of the same type

To analyze a class of authority (e.g., all police departments in a state, all hospital systems in a region), produce one full Mechanism Record as a baseline, then ask the AI to identify the structural variations between specific instances.

---

## Filing a Violation Report instead

If your concern is about a specific incident rather than the authority's overall structure, use the [Violation Report Form](../02-Forms/02-Stop-Trigger.md) instead. Violation Reports are shorter, focused on a single incident, and can be filed against any authority — whether or not a Mechanism Record exists for it.

A Mechanism Record analyzes how an authority is structured. A Violation Report documents a specific incident in which the authority did, failed to do, or threatened to do something specific.

Both go in the registry. Both contribute to the public record.

---

## Closing principle

The purpose is not praise.

The purpose is structural visibility. The framework's questions surface what most institutional disclosure never makes visible. Citizen inquiry puts that visibility in the hands of anyone willing to do the work of asking.
