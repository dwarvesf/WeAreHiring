---
title: Life at Dwarves
date: 2023-12-05
description: We build this company like we build a product. There are roadmaps for growth; there are phases; there are iterations. There might also be bugs, places where the company crashes because of bad organizational design, or cultural oversights.
authors:
  - duy
  - nikki
tags:
  - career
---

> We're like-minded teammates who pursue ambitious goals with tech culture and codes of conduct.

### Growth stories

Life at Dwarves is a series of stories about people, perspectives and lives at Dwarves.

```dsql-list
SELECT markdown_link(COALESCE(short_title, title), file_path)
FROM vault
WHERE file_path ILIKE '%life%'
  OR ['life-at-dwarves'] && tags
ORDER BY date DESC
LIMIT 10;
```

## Build a place we love to work at

We build this company like we build a product. There are roadmaps for growth; there are phases; there are iterations. There might also be bugs, places where the company crashes because of bad organizational design, or cultural oversights.

That means we advocate for changes. Changes always start with making our people better.

### [Education allowance](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md#continuing-education-allowance-cea)

Annual budget for learning and development goals.

### [Referral bonus](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md#employee-referral-bonus)

Sponsorship to recommend peeps that fit the team.

### [Work gear supplies](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md#work-supplies-expense)

Team fund to back you up for work-related expenses, such as work gears or subscriptions.

### [Travel support](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md#flight-tickets-to-dwarves-hubs)

Annual travel package to Dwarves Hubs across the country.

### Learning sponsorship

Monthly pool for internal & external input in the team's knowledge hub.

### [Healthcare package](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md#annual-healthcare)

Annual Bao Minh Insurance for overall & specialized healthcare check ups.

> And other exclusive company support, as in [Dwarves Benefits & Perks](https://github.com/dwarvesf/handbook/blob/master/benefits-and-perks.md).

## Foster a learning culture

We take learning as the north-star metric. At Dwarves, we value you not only for the projects that you do for the company but also for how you strive to grow yourself. Learning at Dwarves takes place in all formats.

### [Radio talks](https://www.youtube.com/channel/UC_SyzGLf6wiqctQFsRI_frw)

Weekly sharing on practices, new findings & demos.

### [Dwarves Memo](https://memo.d.foundation)

Practice sharing, real-case demos & key takeaways.

### [Tech event](https://open.spotify.com/show/7iHr4TuMBhc2LZhLn0YFoI?si=be4abf7312fe44e1&nd=1)

Monthly sit with Vietnam tech talents for global real-world experiences.

### Lecturer training

Occasional training from university lecturers to reinforce working style & engineering mindset.

### #TIL channels

Jotted down channels for daily news & tips sharing.

## Get things done in style

We proudly ship out challenging products with the support from top-notch technology, latest toolings and frameworks. We apply Agile methodology at scale. The development phase is run in sprints, and V-model testing is applied simultaneously. Our [Dwarves Playbook](https://github.com/dwarvesf/playbook) contains teamwork ethics, engineering principles and other protocols we play by.

### [Product design](https://github.com/dwarvesf/playbook#product-design)

- [[design-sprint|Design Sprint]]
- [[aarrr|AARRR Framework]]
- [[[UX|UX Research]]]
- [[playbook/design/design-system|The Design System]]

### [Production](https://github.com/dwarvesf/playbook#production)

- [[log|Logging]]
- [[monitoring|Monitoring]]
- [[production|Production Checklist]]
- [[handover|Handover Checklist]]

### [Business](https://github.com/dwarvesf/playbook#business)

- [Overall Process](https://github.com/dwarvesf/playbook/blob/master/business/README.md)
- [[fbsc|Fixed Budget, Scope Controlled]]
- [[collaboration-guideline|Collaboration Guideline]]

### [Developing](https://github.com/dwarvesf/playbook#developing)

- [Setup](https://github.com/dwarvesf/playbook#setup)
- [Practices](https://github.com/dwarvesf/playbook#practices)
- [Platforms](https://github.com/dwarvesf/playbook#platforms)

![Dwarves team collaboration workspace](assets/team-workspace.webp)

## Community support

Driven to turn what we know into impactful products & insights for community support. Over the past few years, the Dwarves has participated in countless campaigns and become the sponsor of different tech communities.

### [Golang Vietnam](https://golang.org.vn/)

![Golang Vietnam community event sponsored by Dwarves](assets/golang-vietnam.webp)

### [WeBuild Community](https://webuild.community/)

![WeBuild Community meetup supported by Dwarves](assets/webuild.webp)

### [Techie Story](http://techiestory.net/)

![Techie Story partnership with Dwarves Foundation](assets/techie-story.webp)

### [Startup.vn](https://startup.vn/)

![Startup.vn collaboration with Dwarves](assets/startup-vn.webp)
