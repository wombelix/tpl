<!--
SPDX-FileCopyrightText: 2025 Dominik Wombacher <dominik@wombacher.cc>

SPDX-License-Identifier: CC0-1.0
-->

# Architecture Decision Records

This directory holds the Architecture Decision Records (ADRs) for the
project.

## What are ADRs

An ADR is a short document that records one decision, why it was made,
and what follows from it. For the reasoning behind using them, see
[ADR-0001: Use of Architecture Decision Records](0001-use-of-architecture-decision-records.md).

## Index of ADRs

- [ADR-0001: Use of Architecture Decision Records](0001-use-of-architecture-decision-records.md)

## Writing an ADR

- One decision per ADR.
- Write it for the project as a whole, not for one instance, host or
  environment. Real names and examples belong in the README.
- Record the decision, its reasons, the chosen tools and approaches, and
  policies such as "latest stable release".
- Leave out implementation details: versions, IP ranges, times, exact
  config lines and commands. They change with the code. Name the file
  that holds them instead.
- Accepted ADRs are not edited. A new ADR supersedes or amends an old
  one.

## Creating a New ADR

1. Copy the [template](template.md) to a new file named `NNNN-title-with-hyphens.md`
1. Fill in the template sections
1. Add a line for the ADR to the index above
1. Submit for review and acceptance
