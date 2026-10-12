===========================================================
 2026-10-12 Projects Must Document Core Reviewer Processes
===========================================================

Becoming a core reviewer is the primary way contributors gain a voice
in the technical direction of an OpenStack project. Today, how that
happens varies widely between project teams, and in many cases is not
written down at all. Where it is written down, it is frequently on the
OpenStack wiki, has not been revised in years, or is spread across
mailing list threads and meeting logs.

Without a documented, visible path, it is hard for a contributor, or
their manager, to know what "doing well" looks like, to plan the time
investment needed to grow into the role, or to understand why a
nomination has or has not happened. The same is true in reverse: without
a documented expectation for how core status is retained, core rosters
drift out of date, and the list of people with +2 rights stops reflecting
who is actually maintaining the project. Both undermine the "Open
Community" and "Open Development" principles described in
:doc:`/reference/opens`.

Requirement
===========

The OpenStack Technical Committee resolves that every official project
team must document, in its published contributor documentation:

#. **How a contributor becomes a core reviewer.** This includes how a
   candidate is nominated, who participates in the decision and how it
   is made, and the expectations or signals the team considers when
   evaluating a candidate.

#. **How continued core reviewer status is evaluated.** This includes
   the expectations placed on existing core reviewers and the process
   by which a core reviewer may be moved to an emeritus or inactive
   status or removed. A team that does not intend to review core status
   may instead explicitly state that core reviewer membership is held
   indefinitely until the reviewer chooses to step down.

This documentation must live in the project team's in-tree contributor
documentation published to docs.openstack.org, or in a single location
that it clearly links to and that is maintained under the same review
process. A wiki page may point to this documentation but is not a
substitute for it. Where a project team manages several core reviewer
groups (for example, per-deliverable or stable branch core teams, as
permitted by :doc:`20210923-stable-core-team`), one document may cover
all of them, provided any differences between groups are described.

The Project Team Lead, or the equivalent liaisons for teams using the
:doc:`/reference/distributed-project-leadership` model, is responsible
for keeping this documentation current and updating it whenever the
team changes its process.

Project Autonomy and Non-Goals
==============================

This resolution requires that the *process* be documented and visible.
It does not set the process or the criteria. In particular, this
resolution does not:

* Set criteria, thresholds, or metrics for becoming or remaining a core
  reviewer. These remain the decision of each project team.
* Require project teams to add core reviewers, or to lower their bar
  for doing so.
* Require that deliberation about individual candidates take place in
  public. Teams may continue to discuss candidates privately; only the
  process itself must be documented.
* Single out any individual project team.

Guidance, examples and optional practices, such as tiered contributor
models, subject matter expert tracking, and handling inactive core
reviewers, are provided in the `Project Team Guide`_.

Implementation
==============

This requirement applies to new project teams as part of the
:doc:`/reference/new-projects-requirements`. Existing project teams
will be brought into compliance through a community goal.

.. _Project Team Guide: https://docs.openstack.org/project-team-guide/ptl.html#core-member-maintenance
