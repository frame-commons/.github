# frame-commons charter

**Purpose.** Make open-source software for the Steam Frame easier to find, combine and keep
working: a catalog of what exists, short specs for how parts connect, a record of what
each update breaks, and parts built to those specs.

**What we keep here.**
1. *The catalog.* Any public Frame project can be listed, whatever its licence, and
   whether or not it ever joins. Being listed asks nothing of a project. Anyone can ask to be
   left out.
2. *Specs.* Short, versioned documents for the interfaces between parts (camera frames,
   hand data, gestures, the project manifest). Specs are CC0. They are written from working
   code, and projects adopt them by choice.
3. *Parts.* Repositories that do one job, implement a spec where one exists, run on their own,
   and can be tested from recorded data without wearing a headset.

**Licences.** frame-commons' own code is MIT or Apache-2.0, and its specs are CC0. Projects
elsewhere can use any licence and still be listed or implement our specs. Model weights or
datasets under other terms are never committed here. They can be offered as a separate,
optional download that shows their own licence.

**No telemetry.** Nothing here phones home, reports crashes, or collects usage.

**Decisions.** Changes go through pull requests. A spec changes after it has been open for
comment for at least a week, and the projects that implement it have had a chance to object.
Maintainers settle disagreements, preferring whatever keeps existing implementations working.

**Maintainers.** frame-commons starts with one admin (@arealjim). A co-maintainer seat is
open to anyone who maintains a Frame project. The goal is at least two admins from
different projects, so the org never depends on one person.

**Names.** "Steam" and "Valve" are Valve's trademarks. frame-commons is not affiliated with
Valve. Our org and repository names don't use these marks; we name the Steam Frame only to say
what the software is for.

**Conduct.** Be kind and specific, and credit others' work. Maintainers may remove
contributions or contributors that make the space worse.
