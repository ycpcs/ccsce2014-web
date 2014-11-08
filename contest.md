---
layout: default
title: "CCSC-E 2014 Programming Contest"
---

Last updated: November 8th, 2014

This page has information about the CCSC-E 2014 programming contest.

Email comments to [dhovemey@ycp.edu](mailto:dhovemey@ycp.edu)

# Logistics

Registration and a continental breakfast will take place 7:30&ndash;8:30 AM in the Canteen Area of the Kinsley Engineering Center (just inside the west entrance).

An orientation session will start at 8:30 *sharp* in KEC 125.  The orientation will cover using the contest software and development environment.

The contest will start no later than 9:15 AM and end no later than 12:45 PM.  When the contest is finished, programming contest participants should proceed to Yorkview Hall (on the top floor of the Willman Business Administration Building) for the conference luncheon and awards ceremony.

See the [local information](local_info.html) page for directions, maps, information about parking, etc.

# Contest Rules

Each team will have 2 or 3 members.

Teams may write their solutions in Java or C++.  Eclipse Luna is provided as the the programming environment.  The Java environment is JDK 1.8.  The C++ environment is g++ 4.4.  The contest PCs will run Linux using a USB drive provided by the contest organizers.  Submissions will be compiled and tested on a computer running Linux.

The contest software is <a href="http://www.ecs.csus.edu/pc2/">PC<sup>2</sup></a> version 2.9.4.

The use of cell phones or other electronic devices during the contest is strictly prohibited.  Any violation of this rule will result in the offending team's immediate disqualification.  Team members must have all such devices turned off during the contest.

The use of *printed* textbooks and language references during the contest is permitted.  Teams must bring their own printed reference texts; no reference texts will be provided.

General web access is not allowed during the contest (and will be disabled at the operating system level.)  Access to the Java API documentation will be provided (through Eclipse and through a local web browser.)  No electronic information about C++ will be provided, so teams planning to use C++ should bring their own language reference texts.

## Scoring

The scoring algorithm is one used in the ACM ICPC World Finals (see Section 9.2 of the PC<sup>2</sup> manual):

1. Teams are ranked according to the number of problems solved; a team solving more
problems is always ranked higher than a team solving fewer problems.

2. Within a group of teams solving the same number of problems, teams are ranked by
increasing "Penalty Points" (that is, the team with the lowest number of Penalty Points
is ranked highest within the group). Teams only accrue Penalty Points for problems
which the team has solved; unsolved problems do not affect the scoring in any way.
Teams accrue Penalty Points for solved problems in two ways:

    *  One point for each minute elapsed from the start of the contest until the problem was solved (the time of SUBMISSION is counted as the "time solved"; it does not matter how long it took the Judges to judge it).
    * A specific number of penalty points for each INCORRECT submission submitted to the Judges prior to a correct solution for the problem (runs submitted after a correct solution are not counted in the scoring).

3. If two or more teams have the same number of solved problems and exactly the same
number of Penalty Points, ties are broken in favor of the team with the earliest time of
the last correct submission (that being the time when the team "finished" the contest).

The number of penalty points for an incorrect submission is 20.
