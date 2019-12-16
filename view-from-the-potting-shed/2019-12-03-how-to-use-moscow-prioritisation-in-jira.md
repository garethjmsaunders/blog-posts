# How to use MoSCoW prioritisation in Jira

Tuesday 3 December 2019

A few months ago, my team at work considered using DSDM's MoSCoW prioritsation technique for our project's user stories in [Jira](https://www.atlassian.com/software/jira).

After a little pondering, this morning I worked out how to do this in our cloud-hosted Jira. This short post shows you how.

--- MORE ---

## MoSCoW

MoSCoW works well in agile projects which have fixed length iterations. When time has been fixed, understanding the relative importance of user stories on the sprint is essential for ensuring the team delivers the most important work on time.

The uppercase letters in MoSCoW stand for:

* Must have — the solution won't work without these.
* Should have — important but not vital; without them things may be harder but there are workarounds.
* Could have — these features are nice to haves; if left out these have less of an impact than the Shoulds.
* Won't have this time — it has been agreed that these requirements will be left out. They may be reprioritised later.

## Jira

Having pondered how to do this in Jira (for example, should we prefix or append card titles with the priority, e.g. 'Prepare for SIT testing [MUST]') I suddenly realised that it may be possible to extend or replace the built-in priority statuses. It turns out that you can and it's ridiculously easy; you need to be a Jira admin to do this, but here's what you do:

1. Open Jira Settings (click the cog icon, bottom left).
2. In the left-hand navigation locate Issue attributes > Priorities.
3. On the Issues > View Priorities screen you can add your new priorities: Must, Should, Could, Won't.

For the icons, I created my own and hosted them on [GitHub](https://github.com/garethjmsaunders/jiraicons). I used PNGs; I'll create SVGs later.