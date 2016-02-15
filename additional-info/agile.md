# We do agile

## Kanban

We use Trello with Kanban theory to organize tasks. Tasks will be flew from left list to right list. We also organize lists into Scrum steps. So this will be liked:

- Sprint Planning
- Current Sprint
- In Progress
- Blocked
- Testing
- Bugs Report
- Approved

[![Trello](https://raw.githubusercontent.com/dwarvesf/WeAreHiring/master/images/trello.png)](/images/trello.png)

For each project, we will have Sprint planning meeting for Project Manager to explain project details to project members. User stories will be converted into cards or tickets and added to Trello list > **Sprint Planning**.

Usually, one sprint is about 1 or 2 weeks, we have weekly meeting to break user stories into tasks and add them to list Current Sprint. It’s also our target for this week, we have to get in done. This time, cards need to have requirement and non requirement specification. And sometimes, if this task has some special requirements that developers need to care about, we need to sit down and write out the **Acceptance Criteria**.

[![Criteria](https://raw.githubusercontent.com/dwarvesf/WeAreHiring/master/images/criteria.png)](/images/criteria.png)

As a customer, they are granted permission to access Trello Board to give feedback or be a tester. And most of my customers are happy with it.

The template for this workflow can be found at https://trello.com/b/WYgcFBgl/sprint-template

## Source code management

We use git and GitLab. It’s more like GitHub but for enterprise. You can have one by downloading and deploying it yourself.

We apply [Gitflow](http://danielkummer.github.io/git-flow-cheatsheet/) and Merge Request (some people may call it Pull Request) between developers to gain some benefits from it:

- Can deliver anytime because branch master is always stable.
- Quality source code: always review it after it’s merged into branch develep
- High efficiency collaboration between team members.

[![Gitflow](https://raw.githubusercontent.com/dwarvesf/WeAreHiring/master/images/gitflow.png)](/images/gitflow.png)

There’s another article about it on Atlassian site: https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

## Communication channels

We use Slack as the main hub for all informations, from team meeting, hangout, manage tasks and source code ...

[![Slack](https://raw.githubusercontent.com/dwarvesf/WeAreHiring/master/images/slack.png)](/images/slack.png)

Slack support lots of methods to add integration. So the powerful it can be depends on what you integrate into it.

Finally, at the end of the day, we do daily meeting via hangout or face to face at the office to summary what we have done today and what we plan to do tomorrow. The project manager will be the one to write it down and make weekly report to customer.

All the processes out there are just to make the team stick together and development plan works. All team members need to understand their roles, team vision and know how to make things go on the right tracks.

Read more about [Teamwork](http://tieubao.me/writing/2014/12/05/it-is-hard-to-become-a-team-member/).

