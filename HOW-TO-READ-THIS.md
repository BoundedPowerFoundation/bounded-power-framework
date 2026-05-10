# How to Read This

## What this is

This repository is a thought experiment about institutional authority, presented in the form the experiment requires.

The experiment asks: *what would it look like if any system exercising authority over people had to publicly declare what it can do, what would stop it, and when its authorization expires? Not in principle, but in operating detail — the actual rules, the actual form, the actual examples worked out for institutions a reader would recognize.*

To answer that, the experiment had to be built. An essay can wave at the idea; a worked construction either holds together or it doesn't, and the difference is visible. So what's in this repository is a complete proposed architecture: a constitution of structural rules, an operations manual, a registration form, a stop-trigger process, an enforcement system, and roughly twenty example registrations applying the form to authorities ranging from a 940-person homeowners association to a national credit bureau.

None of it is operating. There is no real registry. No institution has filed. There is no foundation with staff, no enforcement, no pending reviews. The registry exists as a worked specification — the equivalent of a fully detailed architectural drawing for a building that has not been constructed.

## Why it had to be built this way

A common failure mode of writing about institutional design is that the writing stays at altitudes where the hard questions don't surface. "Authorities should be accountable" is a sentiment. "Authorities should declare expiration dates and harm thresholds in a public registry" is a position. "Here is the form an authority would fill out, here is what a credit bureau's declaration would actually contain when filled out honestly, and here is what happens when the form is filled out in bad faith" is an experiment whose results can be examined.

The construction is the argument. Reading the constitution alone is not the point; reading the constitution alongside the example registrations and asking whether the rules actually do useful work when applied is the point.

This is also why the documents read like an operating regime — like a constitution, like an enforcement system, like real registration forms. They have to. A thought experiment about regulatory architecture that didn't sound like regulatory architecture would be evading the work it's meant to do. The genre of the document is part of the experiment.

## What the reader is being asked to do

Read it as a proposal in working form. Notice where the construction holds together and where it leaks. The example registrations are particularly important: they are applications of the form by its author to authority types they do not operate. They are not self-disclosures by those institutions; the institutions in question have not filed anything and would not. The examples ask: *if this form were filled out honestly about a municipal police department or a family court, what would it surface? And does the surfacing produce something useful?*

A bad-faith example sits alongside the honest ones. It asks the harder question: *what does the form fail to catch when an authority fills it out strategically?* The bad-faith case is the most epistemically valuable document in the repository and is worth reading carefully.

## What this is not

This is not a working registry. The rules are not claimed to be correct. The form is not claimed to be sufficient. This document does not claim standing to bind anyone. It is one worked construction, presented to see whether building it surfaces anything worth seeing.

The "Bounded Power Foundation" appears in the repository as the registry's hypothetical operator. It is a construct of the experiment, not an organization. The cryptographic hash on the constitution file is real and verifiable, but it secures only the file's integrity within this repository — it is not an enforcement primitive. The "stop trigger" mechanism describes how filings would work if the registry operated, not a process that currently runs.

## Questions the experiment is built to make answerable

These are the questions the construction was built to sharpen. Reasonable readers will identify others:

- Does a single registration form scale across authority types from a 940-person HOA to a 245-million-person credit bureau, or does it break somewhere in the middle?
- The constitution defines "authority" extremely broadly — including any system that materially shapes decisions at scale. Does that breadth produce useful constraints, or does it sweep in so much that the rules become unworkable?
- A stop-trigger process with no enforcement, only public visibility — does that do real work, or is it theater?
- What does an honest registration of a coercive institution surface that the institution's own materials don't?
- What does a bad-faith registration look like, and what would catch it?
- Can the framework's operator credibly be subject to the framework? (The construction tries; the result is mixed and worth examining.)

If the construction makes any of these questions sharper than they were before, the experiment did its job. If it doesn't, it didn't.

## What this is for

For this to exist as a reference document that people can engage with. Discussion, critique, forking, replying with a different construction, picking up the underlying ideas and writing them up in a different form, ignoring the parts that don't work and using the parts that do — all of these are good outcomes. There is no operational ambition behind the document. A curated registry of this kind eventually existing would be welcome; the author does not intend to operate one.

The repository will not be actively maintained as if it were live infrastructure. If something here is useful, take it. If something here is wrong, the wrongness is part of what's available for examination.

## How to navigate the documents

**If you have ten minutes:**
- Read this document and the README
- Skim one example registration — `REG-EXAMPLE-HOA.md` is the smallest and gives the form's shape quickly

**If you have an hour:**
- The above, plus
- The Foundational Theory document (`SCBP-02`) for the reasoning
- The Structural Constitution (`SCBP-04`) skimmed for the rules' general shape
- One large example — `REG-EXAMPLE-CONSUMER-CREDIT-REPORTING.md` or `REG-EXAMPLE-MUNICIPAL-POLICE-DEPARTMENT.md`
- The bad-faith counter-example with its annotations

**If you have a weekend and you are a researcher:**
- The full constitution, with attention to R58 (indirect authority), R34 (aggregation), R28 (expiration), R69 (burden reversal), and R70 (time-bound compliance)
- The full bad-faith example
- Three examples that span the scale — a small one, a mid-size one, a large one
- The Registry Charter and SCBP-REG-0001, which together attempt to make the registry's operator subject to its own framework

---

All documents are markdown files. The green "Code" button at the top of the repository offers a "Download ZIP" option to retrieve everything at once.
