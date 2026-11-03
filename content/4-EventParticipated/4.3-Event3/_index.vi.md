---
title: "AWS First Cloud AI Journey Community Day 2026"
date: 2026-10-31
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

### Event Information

- **Event name:** AWS First Cloud AI Journey Community Day 2026
- **Date:** Saturday, 31 October 2026
- **Time:** 9:00 a.m. to 12:00 p.m. (UTC+7)
- **Location:** 26th floor, Bitexco Financial Tower, 02 Hai Trieu Street, Saigon Ward, Ho Chi Minh City
- **Role:** Attendee

### Overview

I attended AWS First Cloud AI Journey Community Day 2026 in Ho Chi Minh City. The event brought together technology professionals, students and community members for talks and networking.

The event announcement highlighted emerging technology trends, practical experience from industry speakers and opportunities to exchange ideas with the community.

### Speakers Announced

| Speaker | Organization |
| --- | --- |
| Thinh Nguyen | STYL Solutions |
| Henry Duc Bui | CloudThinker |
| Hung Tran | NAB |
| Luong Cam Dao | FCAJ |
| Khang Duong | FCAJ |
| Tran Minh Tuan | FCAJ |

### Event Poster

{{< event-photo src="images/events/community-day-2026/poster.png" alt="AWS First Cloud AI Journey Community Day 2026 event poster." caption="Event announcement poster supplied with the event information." >}}

### Check-in Photo

{{< event-photo src="images/events/community-day-2026/group-check-in.jpg" alt="Group check-in at AWS First Cloud AI Journey Community Day 2026." caption="Our group at AWS First Cloud AI Journey Community Day 2026." >}}

### Opening Session: New to AWS? Where Should You Start?

**Speaker:** Tran Minh Tuan

Tran Minh Tuan opened the event with an introduction to AWS learning resources and hands-on lab websites. His presentation focused on three resources:

- **AWS Study Group:** Community learning materials and lab guides.
- **AWS Skill Builder:** AWS lessons and training, including the free and paid learning options introduced during the session.
- **AWS Builder Center:** A resource for builders to explore technical content and ideas from the community.

The session also introduced a learning path for students and mentioned AWS credit opportunities. It provided an orientation to the available resources before the later technical presentations.

{{< event-photo src="images/events/community-day-2026/opening-learning-resources.jpg" alt="Opening presentation slide introducing AWS learning resources." caption="Opening session: New to AWS? Where Should You Start?" >}}

{{< event-photo src="images/events/community-day-2026/opening-speaker.jpg" alt="Tran Minh Tuan presenting the AWS learning roadmap." caption="Tran Minh Tuan introducing AWS Study Group, AWS Skill Builder and AWS Builder Center." >}}


### Session: Lessons Learned from Building Software Factories

**Speaker:** Henry (Duc) Bui, Head of Engineering at CloudThinker

Henry Duc Bui described how his team organized AI agents into a complete software development workflow. He reported an increase from 39 monthly merges into the develop branch in an earlier period to nearly 3,000, with AI supporting implementation and review. These figures describe the experience he presented from his company.

{{< event-photo src="images/events/community-day-2026/henry-software-factories.jpg" alt="Henry Duc Bui presenting Lessons Learned from Building Software Factories." caption="Henry Duc Bui introducing his team's software factory workflow and merge activity." >}}

#### A Shared Control Workspace

A central control folder provided the starting point for agent sessions. It stored notes, skills and machine guides, allowing agents to work across application, infrastructure and documentation repositories, team machines, and development or production clusters.

This approach gave agents a consistent place to find working context and instructions while coordinating tasks across multiple repositories.

{{< event-photo src="images/events/community-day-2026/henry-control-workspace.jpg" alt="Diagram connecting a central control folder to repositories, team machines and cloud clusters." caption="A central control workspace connects agents with the repositories and environments they need." >}}

#### Shared Testing and Checks

The presentation also showed a shared test cache and check runner serving multiple coding sessions. Test results could be reused when the relevant code was unchanged, while changed inputs triggered a new run. A small random sample was rerun to verify cached results.

Checks included type checking, linting, migrations, secret scanning, dependency audits and tests. The slide reported up to 72% of tests reused in a day and a 76% reduction in waiting time for checks.

{{< event-photo src="images/events/community-day-2026/henry-shared-test-cache.jpg" alt="Slide showing a shared test cache and check runner used across coding sessions." caption="Shared test results and ready-to-run environments help reduce repeated work and waiting." >}}

#### Principles Highlighted

- Start with one repeatable task.
- Agree on the approach before building.
- Keep each change small.
- Turn failures into rules that improve the workflow.

{{< event-photo src="images/events/community-day-2026/henry-principles.jpg" alt="Closing slide outlining principles for starting small and improving the workflow." caption="Principles for introducing automation through small, repeatable improvements." >}}

#### Personal Reflection

This was the session I found most memorable and learned the most from. The combination of a shared control workspace, coordinated agents, reusable checks and small changes gave me a concrete picture of how an agent workflow can be organized. The practical principles were especially valuable to me.

### Session: An Online Card Game and the FCAJ Journey

**Speaker:** Duong Khang (Khang Duong on the event poster)

Duong Khang gave an inspiring and humorous presentation about an online card game website built using AWS services. She also shared her FCAJ journey, including the interesting experiences and challenges she encountered along the way.

Her presentation included a discussion of serverless building blocks. The slide highlighted reduced server management, automatic scaling and usage-based pricing, while also pointing out the shared responsibility for the application code and IAM configuration.

I enjoyed how she connected the technical project with her personal journey. Her humor and openness about the challenges made the session engaging and encouraging.

{{< event-photo src="images/events/community-day-2026/duong-khang-serverless.jpg" alt="Duong Khang presenting the serverless building blocks of her online card game project." caption="Duong Khang discussing serverless and sharing her FCAJ journey." >}}
### Session: AWS Lambda Web Functions

**Speaker:** Thinh Nguyen, STYL Solutions

Thinh Nguyen presented "AWS Lambda Web Functions: Rethinking Serverless Web Architecture." His session focused on AWS Lambda in the context of web applications and offered a perspective on serverless web architecture.

{{< event-photo src="images/events/community-day-2026/thinh-nguyen-lambda.jpg" alt="Thinh Nguyen presenting AWS Lambda Web Functions." caption="Thinh Nguyen introducing AWS Lambda Web Functions: Rethinking Serverless Web Architecture." >}}

### Session: Luong Cam Dao

**Speaker:** Luong Cam Dao

The photographed slide illustrated a synchronous content-generation flow involving a user, an API service, an AI service and Amazon Bedrock. It showed a request to generate content and the service waiting for a response during processing.

{{< event-photo src="images/events/community-day-2026/luong-cam-dao-session.jpg" alt="Luong Cam Dao presenting a slide showing a synchronous content-generation flow with Amazon Bedrock." caption="Luong Cam Dao presenting a synchronous request flow involving API and AI services." >}}

### Session: Kubernetes Engineering and Open Source Contributions

**Speaker:** Hung Tran, NAB

Hung Tran shared his career journey as a Kubernetes Engineer at NAB and his experience contributing to open source projects. During the session, he shared that he was among the top 25 contributors to AWS CDK on GitHub.

His slides highlighted practical ways to find contribution opportunities: choosing clear, well-defined issues with labels such as "good first issue," "triaged" and "ready to implement," and taking on batch changes or refactoring tasks that already have a clear template. Examples shown on the slides came from Kubernetes and Cilium.

{{< event-photo src="images/events/community-day-2026/hung-tran-batch-refactoring.jpg" alt="Hung Tran presenting batch change and refactoring examples from Kubernetes and Cilium." caption="Hung Tran discussing contribution opportunities with a clear refactoring template." >}}

{{< event-photo src="images/events/community-day-2026/hung-tran-first-issues.jpg" alt="Hung Tran showing issue labels such as good first issue, triaged and ready to implement." caption="Finding clear, approachable issues as a starting point for open source contributions." >}}
