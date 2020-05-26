# OSCA Governance

This policy came into effect in June 2016 and will be reviewed periodically \(see revision sections\). The last modification has been made in June 2016.

## Goals

The goals of Open Source Community Africa Governance are to:

* Create a set of minimum requirements for a sub-project hosted on oscafrica.org,
* Create a lightweight project life cycle that:
  * leads the project to articulate its goals and how to achieve them,
  * encourages desired behaviors \(e.g., open development\),
  * provides motivation for the project to succeed,
  * leads to non-viable projects failing quickly, and
  * provides opportunities for other community members.
* Avoid bureaucracy, i.e., the life cycle should be as informal as possible,
* Encourage Open Source Community Africa-related projects to be hosted on oscafrica.org rather than going elsewhere, and
* Set clear expectations to vendors, upstream and downstream projects, and community members.

## Principles

### Openness

Open Source Community Africa is open to all individuals in their individual capacities, and provides the same opportunity to all. Everyone participates with the same rules. There are no rules to exclude prima facie any potential individual contributors, which include individuals associated with direct competitors in the marketplace.

### Transparency

All project discussions, minutes, deliberations, project plans, designs, plans for new features, and other artifacts shall be open, public, searchable, and easily accessible to everyone.

### Meritocracy

The Open Source Community Africa community is a meritocracy. The more you contribute, the more responsibility you will earn. Leadership roles in Open Source Community Africa are also merit-based and earned by peer acclaim.

### Consensus Decision Making

Open Source Community Africa projects or teams are self-governing and driven by the people who volunteer for the job. When more formal decision making and coordination is required, decisions are taken with a ["lazy consensus"](http://openoffice.apache.org/docs/governance/lazyConsensus.html) approach: a few positive votes with no negative vote is enough to get going.

Sometimes a member of the community will believe a specific action is the correct one for the community but are not sure enough to proceed with the work under the lazy consensus model. In these circumstances they can state Lazy Consensus is in operation.

What this means is that they make a proposal and state that they will start implementing it in **72 hours** unless someone objects. 72 hours is chosen because it accounts for different timezones and non-Open Source Community Africa commitments. If the 72 hours are touching a weekend/holidays it would be wise to extend the timeframe a bit. This will ensure that people can participate in the proposal even when they were offline over the weekend.

Voting is done with numbers:

* +1 : a positive vote
* 0 : abstain, have no opinion
* -1 : a negative vote

A negative vote should include an alternative proposal or a detailed explanation of the reasons for the negative vote. The project community then tries to gather consensus on an alternative proposal that resolves the issue. In the great majority of cases, the concerns leading to the negative vote can be addressed.

## Conflict Resolution

### Refereeing

Open Source Community Africa projects and teams are not democracies, but meritocracies. In situations where there is disagreement on issues related to the day-to-day running of the project, Committers and Project Leads are expected to act as referees and make a decision on behalf of the Open Source Community Africa community. Referees should consider whether making a decision may be divisive and damaging for the Open Source Community Africa community. In such cases, the committers of the project can privately vote on an issue, giving the decision more weight.

### Last Resort

In some rare cases, the lazy consensus approach may lead to the community being paralyzed. Thus, as a last resort when consensus cannot be achieved on a question internal to a project, the final decision will be made by a secret ballot majority vote amongst the committers and project lead. If the vote is tied, the project lead gets an extra vote to break the tie.

For questions that affect several projects, committers and project leads of mature projects will hold a secret ballot majority vote. If the vote is tied, the Open Source Community Africa Steering Committee will break the tie through a casting vote.

## Roles

### Maintainers

Maintainers own one or several components in Open Source Community Africa. A maintainer reviews and approves changes that affect their components. It is a maintainer's prime responsibility to review, comment on, co-ordinate and accept patches from community members, and to maintain the design cohesion of their components. A project's maintainers shall be listed in a MAINTAINERS file in the root of that project's code repository or documentation page.

### Committers

Committers are Maintainers who are allowed to commit changes into a repository. The committer acts on the wishes of the maintainers and applies changes that have been approved by the respective maintainer\(s\) to the repository. Due to their status in the community, committers can also act as referees, should disagreements amongst maintainers arise. Committers are listed on the project's team web page.

### Projects and Teams

Open Source Community Africa organizes itself into a number of projects, which follow the Project Governance \(or Project Lifecycle\) as outlined in this document. Projects are run by individuals and are often referred to as teams to highlight the collaborative nature of development. For example, each project has a team page on oscafrica.org.

### Project Lead

Open Source Community Africa projects and teams are managed by a Project Lead, who is also a committer of the project/team they lead. Project Lead is the public figurehead of the project and is responsible for the health of the project. Due to their status in the community, project leads can also act as referees should disagreements amongst committers of the project arise. The project lead typically also has write access to resources, such as the web page of a specific project.

### Open Source Community Africa Steering Committee

The Open Source Community Africa Steering Committee consists of members who are committed to steering Open Source Community Africa to advance its market and technical success, and who serve as positive ambassadors for the project. The Open Source Community Africa Steering Committee manages non-technical aspects of Open Source Community Africa including funding for shared project infrastructure, marketing and events, and managing Open Source Community Africa trademarks. The Steering Committee leaves all technical decisions to the open source meritocracy.

### Mentor

Younger projects may have a need for a mentor to help ensure that the project will be successful. Mentors can be maintainers, project leads, Steering Committee members or other distinguished community members. Mentors are expected to have a monthly review and report back to the community about movement from incubation to maturity.

### Sponsor

To form a new Open Source Community Africa project or team, we require a sponsor to support the creation of the new project. A sponsor can be a project lead or committer of a mature project, a member of the Steering Committee or the community manager. This ensures that a distinguished community member supports the idea behind the project and is responsible to find an appropriate mentor for the project.

## Making Contributions

Making contributions in Open Source Community Africa follows the conventions as they are known in the Linux Kernel community. In summary, contributions are made through pull requests that are reviewed by the community. Open Source Community Africa does not require community members to sign contribution or committer agreements.

More information on making contributions can be found in the following documents:

* [Contribution Guidelines for Open Source Community Africa Toolkit](https://gitlab.com/Open%20Source%20Community%20Africa/lh-toolkit/blob/master/CONTRIBUTING.md)
* Contribution Guidelines \(others upcoming\)

## Elections and Formal Votes

### Maintainer Elections

Developers who have earned the trust of maintainers \(including the project lead\) can be promoted to Maintainer. A two-stage mechanism is used:

* **Nomination:** A maintainer should nominate himself by proposing a patch to

  the MAINTAINERS file or mailing a nomination to the project's mailing list.

  Alternatively another maintainer may nominate a community member. A nomination

  should explain the contributions of proposed maintainer to the project

  as well as a scope \(set of owned components\). Where the case is not obvious,

  evidence such as specific patches and other evidence supporting the nomination

  should be cited.

* **Confirmation:** Normally, there is no need for a direct election to confirm

  a new maintainer. Discussion should happen on the mailing list using

  the principles of consensus decision making. If there is disagreement or doubt,

  the project lead or a committer should ask the community manager to arrange

  a more formal vote.

### Committer Elections

Developers who have earned the trust of committers in their project can through election be promoted to Committer. A two-stage mechanism is used:

* **Nomination:** Community members should nominate candidates by posting

  a proposal by sending a direct message to the "Appointments" group on

  Open Source Community Africa Forums, explaining the candidate's contributions to the project

  and thus why they should be elected to become a Committer of the project.

  The nomination should cite evidence such as patches and other contributions

  where the case is not obvious. Existing Committers will review all proposals,

  check whether the nominee would be willing to accept the nomination

  and publish suitable nominations in the Open Source Community Africa Forums publicly

  for wider community input.

* **Election:** A committer will be elected using the decision making process

  outlined earlier. Voting will be done by committers for that project privately

  using a voting form that is created by the community manager. Should there

  be a negative vote the project lead and community manager will try

  and resolve the situation and reach consensus. Results will be published

  in the public forums.

### Project Lead Elections

Projects which lose their project lead are at risk of failing. Should this occur, the project's maintainer community should agree on a suitable new project lead and follow the election process as outlined above.

### Formal Votes

Sometimes it is necessary to conduct formal voting within the Open Source Community Africa community \(outside of elections\). Formal votes are necessary when processes and procedures are introduced or changed, or as part of the Project Governance. Who is eligible to vote, depends on whether the scope of a process or procedure is **local** to a project or team, or whether it affects all projects \(**global**\). An examples of local scope is a code review policy which applies to the EMR project only. Examples of global scope are changes to this document or votes outlined in the Open Source Community Africa Community Governance document.

* **Scope:** Local
  * **Who reviews:** Members of developer mailing lists of the affected projects.
  * **Who votes:** Maintainers of the project \(or projects\), which are affected

    by the process, procedure, etc. are allowed to vote. This includes maintainers

    from incubation projects \(if the scope affects the project\).
* **Scope:** Global
  * **Who reviews:** Readers of all Open Source Community Africa Forums project categories.
  * **Who votes:** Maintainers of all **mature projects** and the Open Source Community Africa

    community manager are allowed to vote.

The community manager first arranges a public review, followed by a timed private vote. Public review and voting should be open for a minimum of a week each. For voting a traceable poll mechanism, e.g., a voting system that keeps auditable and tamper proof records, must be used. Voting follows the conventions as laid out in "Principle: Consensus Decision Making".

## Project Governance

### Basic Project Life Cycle

The proposal is to follow a simple basic flow:

![alt tag](http://i.imgur.com/f1mgSxN.png)

A Open Source Community Africa project starts with an idea which through the process of project formation will grow into a project proposal. The project proposal will need to satisfy some basic conditions, will be put out for community review and is then put to a vote to all maintainers and project leads of mature Open Source Community Africa projects following the usual decision making process.

For agreed project proposals, Open Source Community Africa will provide basic infrastructure and the project can get started. Projects in incubation are working towards a set of goals, will get additional support and marketing opportunities from the Open Source Community Africa. However, there will also be regular checkpoints to see whether the project is progressing. Should it turn out that a project is not viable any more, it will be archived after an archival review and vote. For a project to graduate, some basic conditions must be satisfied. If a project in incubation has achieved the point where it believes it is mature enough to graduate, it can request a Graduation community review followed by a vote.

Mature projects are expected to run themselves. However, at some point a mature project will lose momentum and developers. If this is the case the Open Source Community Africa community can request an archival review, which follows the usual pattern.

Archival reviews have two purposes:

* To give somebody in the community an opportunity to step up and continue

  a project, and

* To archive the project outcomes such that they are still available to people

  who want to use them, but promotion of such projects will cease.

It is also possible to revive archived projects. However these are treated almost like new projects as projects would only be archived if they have become inactive.

### Requesting Reviews, Reviews and Voting

**Requesting Reviews:** Project Proposal and Graduation Reviews are requested by the \(prospective\) project lead of the project by contacting the community manager providing the necessary documentation. An archival review can be requested by any maintainer of a mature project or by the Open Source Community Africa community manager. The community manager will then publish relevant material on the respective forums.

**Reviews:** These are off-line reviews which are open to all community members by which a proposal is published for review. The purpose of the review is two-fold:

* To gather final feedback and input from the community \(it is good practice to informally do this before the review\), and
* To advertise the project with the aim to attract interest, users and contributors.

After a review, the requester of the review may decide to withdraw, request a re-review or progress to a vote by arranging with the community manager.

**Voting:** The community manager arranges a timed private vote as outlined in Formal Votes.

### Forming a Project

Requirements for forming a Open Source Community Africa project \(or team\):

* A project needs a lead, who is willing to become the project lead of the sub-project.
* A project needs a sponsor, which can be a project lead of a mature project, a member of the Open Source Community Africa Steering Committee, or the community manager.
* There should be no dissent from other community members who would qualify as sponsor \(see "Principle: Consensus Decision Making"\).
* A project needs a mentor, which can be the project sponsor or a maintainer of a mature project.
* A project needs to have a relationship to other projects or teams, i.e., it aims to develop software that has a dependency on other Open Source Community Africa projects or teams. If the project needs components in other projects to work, then this should also be stated.
* A project needs to be large and long-term enough to grant a separate project. For example adding support for a new clinical domain, adding additional functionality on top of existing projects, etc. Adding a new feature to an existing project should be performed within an existing project.
* A project will deliver code using a license that is compatible with other Open Source Community Africa projects, ideally MPL 2.0 HD.

The purpose of the project formation phase is to work out what the project is about, get community buy-in and help the future project gain publicity and momentum. The formation phase is driven by that project's project lead. The project mentor's role is to advise and support the project lead in getting the project started.

The project proposal is a document that is published on forums.oscafrica.org and describes:

* What the project is aiming to achieve, i.e., the project charter and project goals,
* What components/code and in which code lines \(new or components in other projects\) the project aims to deliver,
* Key dependencies on other Open Source Community Africa projects or teams, if applicable,
* A list of initial maintainers, if applicable,
* A lists of any interested parties in the project, if applicable,
* A lists of any planned initial code contributions, if applicable, and
* A rough plan on how to get through the Incubation phase.

### Project Proposal Review

The review is initiated by the project lead and follows the rules outlined in "Requesting Reviews, Reviews and Voting".

After a successful review, the following resources will be created for the project:

* A category in the Open Source Community Africa forums,
* A code repository, and
* A project or team page on oscafrica.org, in an area separate from mature projects, to be maintained by the project lead.

### Incubating a Project

The purpose of the incubation phase is for a project to show that it is gathering momentum and adheres to the "Principles & Roles" of Open Source Community Africa projects. The project mentor will work closely with the project lead and there are at least quarterly informal review meetings with the mentor on how the project is doing. Should a mentor not be able to fulfill his/her role any more, it is the responsibility of the project lead to find another mentor. We advise that the project lead gives at least quarterly updates on the Open Source Community Africa blog on how the project is doing.

Open Source Community Africa will provide support to incubating projects. The project lead will work closely with the Open Source Community Africa community manager as well as with the project mentor.

### Archiving an Incubating project

The mentor can request for a project to be archived, if the project is not making sufficient progress. See "Archival Review".

### Graduation Review

The review is initiated by the project lead and follows the rules outlined in "Requesting Reviews, Reviews and Voting". In essence, the project lead makes a pitch to the community about why the project should graduate.

A project must fulfill the following requirements before it can graduate:

1. It follows the principles of openness, transparency and meritocracy.
2. It has delivered at least one functioning release of what it is aiming to deliver.
3. It has a public code repository which shows active development, has mechanisms to accept patches, and a history of accepting patches.
4. It has a public forum that is active.
5. It has a mechanism for users to raise bugs and for developers to work on bugs.
6. It has an active developer community, including multiple maintainers, a diverse profile of individuals, etc.

Other items to look at during the review \(depending on project are\):

1. It has up-to-date documentation and a core and group of people maintaining it.
2. It publishes regular builds and tests.
3. It promotes itself at Open Source Community Africa events and on the Open Source Community Africa blog.

### Mature Projects

Mature projects are expected to be run and promote themselves. The project lead has significant responsibility in ensuring that this happens. The Open Source Community Africa Steering Committee and the community manager will help organize events, provide opportunities for the project to get new contributors and build a community, promote new releases on the blog and to the press, work with project members, etc. However the Open Source Community Africa Steering Committee and the community manager will not get involved in the day-to-day running of the project.

At some point during its lifecycle, a project may lose momentum. In other words, developers and users are not interested in the project any more. If this is the case, it may be time to archive the project. If the project has achieved its goals and is thus completed, it may also be time to archive the project.

### Archival Review

These can happen in a number of situations:

* An incubation project shows clear signs of failing and not progressing.
* A mature project has lost its developer and user base, and there is little or no activity.
* The project has achieved its goals and/or fulfilled its charter. In other words, it has completed.

In the first case, the review is triggered by the incubation project's mentor. Failing this, the review can be requested by any maintainer of any mature project \(including the project's lead\) or by the Open Source Community Africa community manager. See "Requesting Reviews, Reviews and Voting".

The review is essentially a pitch why the project should be archived. The purpose of the review is not necessarily to archive a project, but also to provide a last opportunity for interested parties in the Open Source Community Africa community to save the project and step up. The Open Source Community Africa community manager will support efforts to save the project, should community members want to step up. In the case where a project has been completed, the normal situation would be for the project lead to make the case for archival.

### Archived Projects

When a project is archived, the following happens:

1. The code repository and forums will be made read-only and made accessible from an "archived projects" section of oscafrica.org.
2. The project's documentation pages will be tagged as "archived". A project may be completed, i.e.,  it has achieved its goals and/or fulfilled its charter, in which case it is tagged as "completed" and "archived".
3. The project or team page on oscafrica.org will be moved into an "Archive" or "Completed" section.

In cases where the project has delivered code into other Open Source Community Africa projects, the code will be:

* Deprecated at the point where the project is archived, and
* The project which now contains the archived code can \(but does not have to\) remove the code in a subsequent release \(it should however give users sufficient time to adapt\)

## Exceptional Circumstances

### Projects without Project Lead

Projects which lose their project lead during the incubation or maturity phase are at risk of failing. Should this occur, the project's maintainer community should agree who would want to be/be able to be the new project lead and follow the election process as outlined in "Electing Maintainers".

If a project lead leaves during the formation phase without finding a successor, we assume that the project does not have enough momentum and will not go ahead.

### Incubation projects without Mentor

Should an incubation project lose its mentor, the Open Source Community Africa community manager will support the project lead in finding a new mentor.

## Acknowledgements

_This work, "Open Source Community Africa Community Governance", is a derivative of "Xen Project Governance" by Xen Project, used under the Creative Commons Attribution 3.0 License \(CC BY 3.0\). "Open Source Community Africa Community Governance" is licensed under the Creative Commons 4.0 International Attribution License \(CC BY 4.0\) by Humanitech Inc._

## Change History

* **ver. 0.1** Initial Draft, 15 June 2016

