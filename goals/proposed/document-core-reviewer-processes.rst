=============================================
 Document core reviewer membership processes
=============================================

Description
===========

:doc:`/resolutions/20261012-document-core-reviewer-processes` requires
every official project team to document, in its published contributor
documentation, how a contributor becomes a core reviewer and how
continued core reviewer status is evaluated (or an explicit statement
that core reviewer membership is held indefinitely).

New project teams must meet this requirement before being accepted.
This goal brings existing project teams into compliance.

Many teams already have some form of this process, but it is frequently
undocumented, lives only on the OpenStack wiki, or has not been revised
in several cycles. A documented, visible path makes it clear to
contributors, and to the organizations funding their time, what is
expected to grow into the role, and keeps core rosters reflective of
who is actually maintaining each project.

Design & Implementation details
===============================

Each project team adds, or updates, a page in its in-tree contributor
documentation (typically under ``doc/source/contributor/``) covering:

#. **Becoming a core reviewer.** How candidates are nominated, who takes
   part in the decision and how it is made, and the expectations or
   signals the team considers.

#. **Retaining core reviewer status.** The expectations placed on
   existing core reviewers and how a core reviewer may be moved to an
   emeritus or inactive status or removed, *or* an explicit statement
   that core reviewer membership is held indefinitely until the reviewer
   chooses to step down.

If the team manages more than one core reviewer group (per-deliverable
or stable branch core teams, for example), the page should cover each
group or describe how they differ.

The criteria themselves remain the team's decision. This goal does not
ask teams to change who their core reviewers are, to add core reviewers,
or to lower their bar for doing so.

Teams whose process currently lives on the wiki should move the content
into their contributor documentation and replace the wiki page with a
link to it.

The `Core member maintenance`_ section of the Project Team Guide has
guidance and examples, including optional practices such as tiered
contributor models, subject matter expert tracking, and handling
inactive core reviewers.

Goal Checklist
==============

Is design finalized?
--------------------

Status: YES

Is implementation finalized?
----------------------------

Status: YES

Is there any dependency or blocker?
-----------------------------------

Status: NO

Current state
-------------

Several teams already document part or all of this process and can
serve as examples. For instance, the Nova team documents its process
on the `Nova core team wiki page`_, which covers nomination and
membership and review expectations; moving this content into Nova's
contributor documentation would satisfy the goal.

Regular Meeting & Discussion
----------------------------

Questions can be raised on the ``openstack-discuss`` mailing list, or in
the ``#openstack-tc`` IRC channel.

Completion Date & Criteria
==========================

Completion Date: 2027-07-01

Items to complete:

#. The project team's published contributor documentation describes how
   a contributor becomes a core reviewer.

#. The project team's published contributor documentation describes how
   continued core reviewer status is evaluated, or explicitly states that
   core reviewer membership is held indefinitely.

#. Any wiki pages previously describing this process are updated to link
   to the contributor documentation.

Champion
========

Doug Goldstein (cardoe)

Status & Tracking
=================

:Etherpad: https://etherpad.opendev.org/p/openstack-core-reviewer-process-goal

Gerrit Tracking
---------------

To facilitate tracking, commits related to this goal should use the
gerrit hashtag or topic::

  core-reviewer-process

Hashtags are preferred over topics because they are additive and
support multiple tags per change.

References
==========

* `Original proposal on openstack-discuss`_
* :doc:`/resolutions/20261012-document-core-reviewer-processes`
* `Core member maintenance`_ in the Project Team Guide
* `Kubernetes community membership`_, an example of a tiered contributor
  model

.. _Core member maintenance: https://docs.openstack.org/project-team-guide/ptl.html#core-member-maintenance
.. _Nova core team wiki page: https://wiki.openstack.org/wiki/Nova/CoreTeam
.. _Original proposal on openstack-discuss: https://lists.openstack.org/archives/list/openstack-discuss@lists.openstack.org/thread/KPLX44YX6VEAJT4SZ3T7CJ3K2U6HJUTZ/
.. _Kubernetes community membership: https://github.com/kubernetes/community/blob/master/community-membership.md
