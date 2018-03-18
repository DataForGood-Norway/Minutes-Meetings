# Meeting DataForGood #02 (2018/03/16 17:30)

* Meeting purpose: Present structure for online collaboration & get started with current project ideas.
* Meeting Location: Socentral, Oslo

## ATTENDING

Alex, Bjørn, Dirk, Eva, Geir, Harjeet, Kleng, Magdalena, Olav, Patrick, Peter

## AGENDA

The agenda presented at the meeting on these [slides](./slides/slides_D4G_meeting_02.pdf):

- Review our structure for remote collaboration
- Present the current project ideas (2min each)
- Method to help pick a project
- Discuss next steps (recruit, report on projects, website, ...)
- (optional) Start projects tonight!?


## DISCUSSIONS


### Review our structure for remote collaboration

We started with a round table to briefly present ourselves.

We use Slack for discussing as Github isn't providing an easy way to chat about things. In Slack, each project should have its own "channel". There is other channels like "organization" or "general" to discuss topics not specific to a project.

We use [Github](https://github.com/DataForGood-Norway) to:

* check existing project ideas.
* add a "Project Idea" (by [writing an 'issue'](https://github.com/DataForGood-Norway/project-ideas/issues) in the "project-ideas" repository). Each issue can be labeled to facilitate its classification or needs (e.g. 'wanted Project Lead', 'size XXL' or 'Impact Local').

  Missing a label? Just [add yours](https://github.com/DataForGood-Norway/project-ideas/labels)
* share our work (each running project has its own repository)
* share knowledge and best practices (with the soon-to-come "Tutorials" repository)


A question/comment was raised about the names of those online tools which were not the same. And there was no reason for this clumsiness :sweat_smile: To solve it:

> Our Slack account has been renamed from ~~https://data4good-no.slack.com~~ to https://DataForGood-Norway.slack.com, thus matching our Github account (https://github.com/DataForGood-Norway). We are losing our first discussions, but we can probably deal with that ;)
>
> [Facebook](https://www.facebook.com/DataForGoodNO/) doesn't allow for special characters like "-" or "_", so they still have a different name ('@DataForGoodNO') than Github/Slack ('DataForGood-Norway'), but now identical to [Twitter](https://twitter.com/DataForGoodNO).

Another remark was made about the way to post "project ideas". Maybe "Github issues" were not the best and writing a proper [Markdown](https://guides.github.com/features/mastering-markdown/) file (`.md` extension). However the current issues allow for an easy/quick visualization of the list of new ideas, thanks to the labels mainly. Therefore the solution could be to keep those ideas as "issues" under the [project idea repository](https://github.com/DataForGood-Norway/project-ideas/issues) but more description could be added in another markdown file (added under [`projects_details/`](https://github.com/DataForGood-Norway/project-ideas/projects_details)) and link to it from the issue (example: [UN challenges - issue #7](https://github.com/DataForGood-Norway/project-ideas/issues/7)).

Another good idea mentioned to build a Slack bot to receive a message in Slack every time a new "issue" has been posted on Github. (Slack already facilitates such [integration](https://get.slack.help/hc/en-us/articles/232289568-GitHub-for-Slack). To be implemented...)

We also described the different 'roles' we might need to run the organization, and especially the importance of having one "project leader" per project to help newcomers find a task they would like to do and coordinate the tasks.

A suggestion was made to add the role of [mentors](https://github.com/DataForGood-Norway/roles/pull/1), e.g. "UX developer", "Google Cloud expert" or "professional fundraiser", who could advice any team on specific tasks when stuck or just unsure. This means we need to find a way to collect those skills we (members) are ready to share.

The [team](https://github.com/DataForGood-Norway/roles#homepagesocial-media-people) which will be responsible for the online public image of DfG (website and social media) will have a lot to do with the website. The website is currently a simple javascript presentation missing a lot of the functionality we would like to have. A list of tasks is available for the ones interested in building it: https://github.com/DataForGood-Norway/DataForGood-Norway.github.io/issues


### Present the current project ideas (2min each)

We moved on to the list of project ideas. We didn't go through the whole list.

The [challenges](https://www.uniteideas.spigit.com/Page/Home) provided by the United Nations were often ambitious projects requiring a team working hard for a couple of months to reach the deadline.

Good remarks emphasized the risk of such projects in the beginning: smaller projects would bring us more confidence, allow us to show finished projects on the website.

Bjørn presented the projejct [OrcaTag](https://github.com/bjornhjelle/orcatag/blob/master/README.md) for researchers at the polar institute in Tromsø: building a tool which help researchers label the pictures of orcas more easily and ultimately automate as much as possible the final goal which is to re-identify single individuals.

The project:

* address the need of some researchers at the polar institute. They are not many users to support, so easier in the first phase of development.
* is scalable, since about 30 other groups worldwide would be interested in the same tool.
* has no funding to pay for developers.

we also discussed technical challenges, but contact Bjørn on the [OrcaTag Slack's channel](https://dataforgood-norway.slack.com/messages/C9SPLJ46B/?) if you want to know more and contribute.


Kleng presented the project [UN Treaties](https://github.com/DataForGood-Norway/project-ideas/issues/6), on which Dirk is now already working, named [ResoCrawl](https://github.com/DataForGood-Norway/ResoCrawl) for crawling the resolutions on the website of the UN treaties.
Kleng contacted UN representatives both in Norway and in NYC to get information. Definitely some skills we need in general for [this role](https://github.com/DataForGood-Norway/roles#representatives) ;)

We discussed the case of BySpire, a for-profit startup building vertical farming and concluded that it might not be the best fit of projecct for DfG.

### Method to help pick a project

Each one can ask herself/himself what they would prefer to work on. A few questions might help find out among the list of project ideas or running projects.

* Type of skills required: Development (UX, Data Science, mobile app, ...), project leader, business/expertise domain, ...
* Prefer working on a local or global project?
* Classify the projects to help compare them:
  * Urgent/non-urgent
  * Important/non-important
  * Easy/realistic vs difficult/unfeasible
  * Potential for becoming a sustainable lucrative social/environmental business?
  * Is the project scalable (i.e. re-usable)?
  * How many man-week would you estimate to spend on this project?
  * Does it require specific domain expertise?



### Discuss next steps (recruit, report on projects, website, ...)

One way to recruit more volunteers of all sort would be to present our projects at different meetups:

* "Data Science", "machine learning", "Deep Learning" meetups to get more Data scientists.
* "UX" and "Progressive webapps" to get more UX designers/developers.
* "OuiShare" meetup to get more challenges and skills in social entrepreneurship.

That should be an objective of our 3rd meeting, after easter holidays.

We also agreed to try to meet once a week, in a place where we can have a drink and eat something. A few places were mentioned (e.g. Mesh) but we will probably use a Doodle to find out.

People already volunteered to:

* work on OrcaTag, NAV, UN Treaties.
* take care of the social media and preparation of the meetings.
* start engaging possible sponsors like Microsoft or Google.
* hold a technical session to show how to get and use satellite data.


### (optional) Start projects tonight!?

Not this time!

## NEXT TASKS

* Rename our online tools to be a minimum consistent ;)
  Share the new links to the team!
* Contact a Meetup and prepare a presentation of D4G and the status running projects.
* Share access to social media account to the respective team.
* build the website with all features mentioned on Github.
* Engage with sponsors (less urgent but useful hopefully soon)
