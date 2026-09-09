<!--
SPDX-FileCopyrightText: 2026 Dominik Wombacher <dominik@wombacher.cc>
SPDX-License-Identifier: CC0-1.0
-->

# ADR-0001: Use of Architecture Decision Records

## Status

Accepted

Date: 2026-09-09

## Context

As the project grows, we make architectural decisions that are hard to
trace back later. We want a record of what we decided, why we decided it,
and what came after. Anyone new to the project needs this history to see
how it got here. We also want to stop re-opening decisions that are
already made.

Today we have no set way to write these decisions down.

## Decision

We will keep a record of decisions that affect how the project is built.
Each record is an Architecture Decision Record (ADR). A small decision
can be worth an ADR too, not just a large one.

Each ADR follows the template at `/docs/adr/template.md` and lives in the
`/docs/adr/` directory. We number them in order (ADR-0001, ADR-0002, and
so on) and name the files `NNNN-title-with-hyphens.md`.

## Consequences

Anyone new to the project gets the context behind past decisions. The
reasoning stays with the decision. Changes to the architecture are
planned and out in the open. When someone wants to re-open a decision,
there is one place to look.

This only works if we keep it up. It adds a step to some decisions and
slows them down. An ADR that no one updates can fall out of date.

## Alternatives Considered

Notes in commit messages and pull requests: tied to a code change, not
to the decision, and hard to find months later.

A wiki: runs as its own service, separate from the code, with its own
access and its own history. An ADR is a plain text file that sits next
to the code and moves with it.

No written record: relies on memory and is lost when someone leaves.

## Related

None. This is the first ADR.
