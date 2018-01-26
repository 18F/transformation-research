# Best practices in government digital transformation

## Executive summary

An 18F research team investigated what makes modern digital practices “stick” within a government entity, beyond a single innovation project.

### What we discovered

After spending time with 15 government staff involved in widely varied transformation projects, including two clusters of people involved in the same project from different perspectives and levels of authority, we identified important positive and negative factors for transformation success.

#### Top barriers to successful transformation

* **Extreme technical debt**, heavy enough to prevent small engineering teams from choosing their tools and doing rapid, iterative releases.

* **Difficulty concretizing the benefits of transformation**. We don’t say _quantifying_, because that’s the problem: many benefits are clear, but qualitative in nature. This makes it hard to get buy-in for ongoing work.

* **Teams that can’t make project decisions without leadership approval**. This costs time and effort for both management and staff, and makes it hard for transformative practices to become the norm.

* **Failure to connect directly to users** (whether they’re employees or the public). It’s harder to muster the will to seek out the most impactful practices when you don’t have a picture of the impacted people in your mind.

We identified a few other barriers, such as shallow adoption of modern practices without committing enough resources, and failing to formalize experimental policy or practice changes before leadership shifts, but these four were the most critical. We saw some promising strategies to overcome some the top barriers, but we also believe 18F should develop further help for several of them.

#### Top practices that contribute to successful transformation

* **Establishing constant feedback loops with users,** often created by early, somewhat risky releases. These are powerful drivers of engagement at every possible level of the organization.

* **Building cross-functional teams of substantial duration.** Subject matter experts working side by side with technical specialists for months or years rather than weeks, and all being treated as full project team members.

* **Using community organizing techniques to bring staff on board** (like monthly meetings, office hours, councils). When it comes down to it, transformation is a long process of getting people on board and supporting them in hard work. This takes non-judgmental spaces to learn, celebrate small and large wins, and get support from teammates and management.

* **Referring to authoritative guidance,** like the [TechFAR Handbook](https://playbook.cio.gov/techfar/), [FITARA](https://management.cio.gov/implementation/), the [Open Data Policy](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf) (OMB Memorandum M-13-13), and the [U.S. Digital Services Playbook](https://playbook.cio.gov/), helps tech-savvy managers make non-technical leadership comfortable allowing experiments in new practices.

There are other important components to success, like choosing the right leaders for transformation, managing contractor staff closely, and showing commitment to both team autonomy and modern practices through signals like strong delegation and budget targets. Read further for more on how these factors operate and interact.

You’ll note that the lists don’t match. Not every barrier has an antidote identified, and not every positive factor has a known barrier or pitfall. In our next stages of research, we’ll spend time digging deeper on strategies to implement the positive practices and overcome the barriers.


## Preliminary report

### Our project goal

**We are leading a comprehensive research project to investigate what makes modern digital practices “stick” within a government entity, beyond a single innovation project.** That is, how does an agency become “transformed”, so that effective modern practices are a default way of working, rather than an experiment?

### Why this question?

People at every level of government are working to improve how they use modern tools and methods to empower workers, connect with constituents, save money, and provide demonstrably better services. Despite these efforts, very few agencies are sustaining strong digital work more broadly.

Correspondingly, there are many resources on how to do innovative digital projects well, but few outline how to sustain modern practices beyond an initial project or prototype. In the course of working with partner agencies, 18F has identified the need for such resources.

### The goal of digital transformation

In May 2016, 18F’s Transformation Services Team held a workshop with 18F staff to define what a “transformed” agency looks like. They identified the following characteristics:

1. People at all levels feel connected to the agency’s mission, have a sense of purpose, and are empowered with the autonomy to act on that purpose.

2. The agency chooses and manages technology effectively in the service of its larger mission.

3. The agency is capable of and committed to practicing [continuous improvement](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/60678/Cabinet-Office-continuous-improvement-strategy.pdf).

We adopted this framework as our hypothesis of what the end goal of this work looks like, and our research thus far has validated these characteristics.

We had originally set out to arrive at a more concrete definition of what “digital transformation” actually entails; however, our research has shown that the work of digital transformation does not necessarily have clear-cut boundaries or look the same everywhere or in every time period. We don’t list particular technologies or technical methods here, because while there’s a clear benchmark of what “modern” looks like in 2016, it’s very different from how it looked in 2006 and how it will look in 2026 and beyond. Right now getting to the cloud and being mobile-ready are on many technologists’ minds, but we found articles about computerization in the 60s and the initial move to the web in the 90s that outlined the same deeper challenges organizations face now. Therefore, for the purposes of this report, **when we say “digital transformation,” we mean any activity that moves an agency toward the three characteristics of a transformed agency, as outlined above**.

### The digital transformation process

Aside from the barriers and best practices we’ve identified thus far, we’re also ready to offer a sketch of what the process of transformation looks like. We have more to fill in, but we believe these are the basic steps:

1. Show what’s possible with a small project that has both internal and external visibility, and make sure there is a user feedback loop. (Note that this is not the transformation itself—just a spark that shows what’s possible).

2. Find explicit executive authority and justification for trying a new approach (such as laws, OMB memos, or White House directives).

3. Actively work to get everyone onboard through community organizing as you do what’s necessary to move more and more parts of the organization to the new practices demonstrated in the initial project. We want to document more details about how to “do what’s necessary” in the next phase of research, but we’ve started identifying [best practices](https://github.com/18F/transformation-research/blob/master/preliminary-report.md#how-the-best-practices-contribute-to-success) as outlined below.

4. Transition-proof the changes you’ve made. Early progress often depends on creative interpretation of policies and standards, but long-term progress depends on writing what works into the rules and creating new norms.

5. Long term, keep checking how well you’re fulfilling your mission and serving your users, and use technology judiciously as a tool to further those goals.

We have an additional hypothesis that a website redesign can be the vehicle for this entire process, in certain circumstances. If an agency or office’s mission is very clear, and its activities are narrow enough in scope to be effectively represented by a single coherent website, then a primary-website rebuild project can be a driver for the entire transformation effort. This can also be true for other types of systems that have broad internal and external visibility, but these days the most common type is a website.

In any case, if you combine the process with the three characteristics of a transformed organization, you begin to see how the barriers and best practices have their effects.

### Why the barriers are so problematic

#### Extreme technical debt

While it’s possible to perform the rituals of agile software development without basic technical infrastructure in place (such as the engineering team having control of their servers and test environments), doing so doesn’t result in the same benefits. Nor does a modern content strategy have the same effect when teams try to implement it using a content management system from the pre-mobile era. Teams that try out a modern method and aren’t able to realize the benefits end up going through the motions and getting tired.

This also allows a situation where a prototype can be created without a path forward to a robust system. Prototypes are almost always technical exceptions, and they should always be able to be thrown away, but successful or exciting ones make promises to constituents. We heard a story from an interviewee about a very successful prototype for distributed government staff. The team tested the prototype and staff were so enthusiastic they adopted it in prototype version. But the team wasn’t able to muster either the development or acquisitions capacity to deliver a full version, and the prototype, not designed for production loads, degraded quickly. The constituents and the team were all painfully disappointed and demoralized, and a year plus after reversion, the problem the prototype addressed is still unsolved.

To boot, practices replicate and justify themselves. One story we heard involved a team that can only release new software once every three months, because they don’t have automated testing or the capacity to correct bugs quickly. They have to follow a long and rigorous acceptance testing process that means it takes weeks from proposed release to actual release. They’re trying to practice agile and iterative development, but it isn’t really possible at these timescales.

#### Difficulty concretizing the benefits of transformation

All of the project leads and managers we spoke with reported some version of this problem. Moving to modern digital practices promises time and cost savings eventually, but inevitably requires large commitments of resources up front. Our interviewees all believe the benefits are worth it, but none of them found a way to explain it in numbers. With numbers being very important in government in terms of efficient use of taxpayer funds, measurement of services delivered, etc., this meant it was hard to get buy-in for larger, longer, and therefore more expensive transformation projects.

We don’t have an answer for this yet, but we think the answer lies in finding a rigorous way to use qualitative evidence to demonstrate benefits like higher service quality and greater staff engagement, that are clear indicators of transformation’s impact but are not well captured by traditional metrics.

#### Teams that can’t make project decisions without leadership approval

One of our leadership interviewees shared with us that the maximum number of projects he could handle, while making all major decisions himself in a hierarchical model, was two or three. Whereas, with lightly-guided, autonomous teams having responsibility for their own decisions, he could run eight to 10 simultaneously. Given his agency’s backlog of projects, this would make a huge difference in productivity.

His was not the only similar story we heard, with both staff and managers lamenting the typically hierarchical relationship they were working in. Where managers found a way to empower teams to work independently, people were more productive and more engaged on both sides.

#### Failure to connect directly with users (whether internal or external)

When people can see how their work impacts the people they’ve committed to serving, they seek out ways to improve. When they can’t see it directly, or don’t have permission to act on that feedback, they just can’t sustain the same intensity.

This is one of the negative factors that actually has a direct positive counterpart. We know how to fix this—through the power of direct observation of users—but it needs to be implemented consistently and universally. The reason user-centered design is so important is that doing well for the people you serve is one of the most powerful motivations there is for a professional. It is one of the few things strong enough to underpin the hard work of continuous improvement over years and decades. Absent that motivation, changing the way you work with technology is just one more mandate.

### Further barriers that can stall transformation work

#### Shallow adoption of modern practices

We heard many accounts of teams adopting the _language_ of agile or user-centered design, without having committed to or mastered the _practices_ themselves. This can happen for a number of reasons, but it comes down to needing effective training and support or mentorship along the way. It can result in the ultimate assessment that the new practices don’t work any better than the old ones—when the reality is that the new practices haven’t been really been tried. This can stop transformation in its tracks, and we heard several stories where it did.

As an example, one of our interviewees told us how his team was trying to do agile on their own. They wrote user stories without doing user research and designed menus without knowing what people actually need. Looking back on the project, he realized that they tried to do agile after briefly reading about it, but it wasn’t until working alongside a group of experts that they understood the process enough to apply it to their work.

#### Policy or practice changes not being formalized before a change in leadership

Having permission from senior management to informally test out innovations before writing new rules is essential, but it can also have painful effects. We heard a particularly difficult story from the leader of an innovation team that had been allowed some leeway in hours-and-location rules by one director in order to enable recruitment and retention of top technologists from industry. The strategy worked, but after a shift in leadership, the team found the new director taking disciplinary actions against them for exceptions that his predecessor had allowed. Because the first director didn’t change the actual rules, the team was blindsided by the second director’s interpretation.

At the same time, we saw a strong positive example of a senior manager doing the hard work to institute a new position description in his agency so that a newer discipline could be officially supported even if he later moved on. Transition-proofing positive changes is especially challenging because transformation efforts take a long time. We haven’t figured out the right stage for experimental approaches to turn into new rules yet, but we know it’s important to ensure they do.

### How the best practices contribute to success

#### Establishing constant feedback loops with users

Every participant who had released something spoke of the power of hearing from actual constituents. Even in cases where a product was released before it achieved a high level of quality, teams from frontline to management were deeply engaged in what real people said, and in how to act on it. Since one of the core components of transformation is continuous improvement, creating feedback loops is a critical component of any transformation effort.

#### Building cross-functional teams of substantial duration

This was one of the surprising findings that maybe shouldn’t have been surprising. But the importance reported by our interviewees caught us off guard. When digital teams consist of IT staff only, or IT staff with occasional input from subject matter experts, both sides learn less about each other’s practices and needs. Cross-functional teams connect IT staff to broader organizational missions, and mission staff to better understandings of digital practices, and the shared strengths of both result in qualitatively better projects.

This is one of the things that’s hard to concretize, but we should pursue it further in our research and our partnership efforts at 18F.

#### Using community organizing techniques to bring staff on board

While transformation is often framed around new technology, much of what actually changes for individuals is the way they do their work. Larger process changes are rarely easy, and they’re even harder for diverse groups to implement than individuals. We shouldn’t have been surprised when we heard about leaders of supposedly technical projects organizing open, cross-functional meetings; taking time to understand stakeholders’ needs; citing listening skills as critical to their jobs; checking in on progress on a monthly basis; and going out of their way to make sure people have safe spaces to learn and grow—but we were, a little.

One of our participants described his work recruiting more and more participants to cross-agency web councils over time; he supplemented that with setting up weekly office hours, Q&A sessions, and in-person tutorials with technical experts. These ongoing conversations create feedback loops and give teams insight into what their peers are working on. The same interviewee emphasized how important it is to cross-promote work across the agency. It’s easy to feel overwhelmed by barriers and bureaucracy when you’re working in government. Having a dedicated place to air frustration and celebrate small wins improves morale, and we heard similar stories in other interviews. This ongoing work may be the top thing that successful transformation requires, and it costs very little in some ways, but requires tons of time and effort. Still, the most successful efforts that we heard about had one or more people dedicated to doing this work, even though they were unlikely to name it as organizing.

#### Referring to authoritative guidance

Every tech-savvy leader has to make a case for transformation work to someone whose portfolio is much broader than technology. Because transformation is a long process, this may happen over and over. We assumed that references would be useful, but we were surprised by how much value managers and project leads found in authoritative guidance from government leadership, including the [TechFAR Handbook](https://playbook.cio.gov/techfar/), [U.S. Digital Services Playbook](https://playbook.cio.gov/), [Open Data Policy](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf) (OMB Memorandum M-13-13), and other similar documents that set a precedent or otherwise make an official case for more modern approaches.

The technical evidence for claims like “agile results in higher quality software” or “user-centered design reduces risk” isn’t evidence that non-technical senior leadership can evaluate easily. Short of leveling up significantly in their own technology-practice knowledge, their best way to assess the value and risk level of a practice is to use the authority of the source pushing for it as a proxy. A trusted subordinate is good; a trusted subordinate backed by a recognized governmental authority is always going to be better.  Given that, these documents are a critical bridge between technical evidence that something works, and administrative confidence in using it.

We hope that our further research will develop into a similarly authoritative resource that can be used to build buy-in for investment in the more structural work that’s required to make space in an agency for more modern practices to take hold in an enduring way.

### Further practices that can push transformation work forward

#### Selecting mid-senior, long-tenured agency staff as leaders

Three of our interviewees fit into this category, and in two cases we were able to talk with other participants on the same projects. The value that socially-adept, trusted, knowledgeable project leads provided, simply by being familiar to and answering questions from everyone, was immense. When they were able to use their well-developed professional networks within agencies to jumpstart communities of practice and support networks, their contributions were even more valuable to their teams.

#### Connecting with communities of practice

We heard several stories of people learning about new techniques from GSA-run communities of practice. We also heard, for example, about someone learning about responsive web design as a participant in an industry community of practice. That person was able to push for immediate adoption of responsive design to solve a pressing problem in his work, and cited outside expert guidance on how to do it. People need communities for support and learning, and they need their managers to acknowledge this need and actively support it.

#### Actively and closely managing contractor staff

Because of the many stories about bad government contracts, we expected to hear stories of difficulty managing contractors. We mostly didn’t, and in fact two of our interviewees were long-tenured contractors. What they (and their permanent staff partners) cited as critical for joint success was very active involvement between contractors and partners. We heard stories of daily meetings, seamless integration into teams, and both sides learning from each other.

One story in particular involved a government CIO working with a systems integration vendor on a highly challenged project. The CIO chose to colocate her internal team with her SI partners for several months and felt the decision was one of the most positively impactful she made on the project. While it might seem like a good idea to let technical professionals go off and do technical work on their own, the work is often much better when both sides work closely together throughout the project (which relates to the importance of having IT and subject matter experts in close proximity). So we end up with the hypothesis that contractors are fine supplements to government staff when treated as a part of the team. We’ve heard the concept of a “badgeless culture” working well as a way to implement this. Ultimately, the government loses huge opportunities for staff learning and productivity, as well as for success with practices like agile and user-centered design, by not working with contractors closely.

This kind of close integration sometimes requires changes to contracts. We heard success stories of rewriting contracts to explicitly specify colocation and team fluidity; we plan to explore further details in our next research stage.

#### Setting budget targets for modern practices

One useful measure of whether something is important is whether an individual or an agency is willing to commit dollars to it. One of our senior interviewees shared that when he joined his agency, he assessed the seriousness of talk about user-centered design by checking the percentage of project budgets spent on usability testing. Finding it much too small, he used a simple metric to demonstrate how important that discipline was to him: he mandated higher spending percentages from the top.

As a research team, we note that higher spending without quality controls is of no use, so we expect that using this factor will sometimes require clear guidance on how to hire high-quality vendors and employees in newer disciplines.

#### Using hierarchical authority to make teams autonomous

One of the trickiest things about transformation is that it’s very clear that doing it successfully requires employees who are both engaged and independent. How do you do that if your employees are used to deferring to authority and sending decisions up the chain?

One way that we heard about is to use your hierarchical authority to mandate independence. Managers can—and successful ones do—refuse to telegraph which side of a question they favor, insist that teams bring a recommendation and not just a question, and require teams to make significant choices for themselves and live with them. We need more examples here, but this is a very interesting way to cross the bridge.

## How we arrived at these conclusions

### We identified these initial assumptions:

* Transformation is not as risky as government agencies may perceive it to be.
* Transformation doesn’t have an endpoint; you work on it continually. The process varies, but nobody is starting at zero.
* Changing culture to be more open and agile makes government services more user-centered and builds trust.
* There’s not one _right_ way to do this work.

### Next, we decided to investigate these fundamental questions:

* What does digital transformation mean in government?
* What is the goal or end-state? How do you know when you’re done?
* What are the biggest obstacles to this work? How can we help people get past those obstacles?
* Is there one digital transformation process or many?
* How do you make the changes last?
* What resources would be valuable for other agencies doing this work?

### We started with a broad range of research methods:

* Interviews with federal, state, and local government employees who are engaged in modernization efforts within their agencies—both successful ones and failed ones

* Reviewing industry case studies to learn how digital transformation happened for leading companies in the private sector

* Reviewing case studies and articles from leading consultancies that deliver “transformation services” to federal agencies

* Looking into laws and policies that hinder or support modernization efforts

Our initial research showed that in-depth case studies of transformation within private industry were rare, and shallow ones were surprisingly uniform, often written from a sales or PR perspective. They were interesting, but not terribly productive of wisdom that could be applied to government, unless we could track down more in-depth studies with a critical perspective.

After assessing our progress, we decided to double-down on one-on-one interviews with folks engaged in this work at government agencies for this initial phase of the research. If we are given additional resources to continue this research, we will likely devote some time to trying to track down more in-depth case studies from industry to see if there is anything of value to be learned there, but will otherwise continue to prioritize firsthand accounts from public servants engaged in this work within government.

### We adopted a “clustered” approach to recruiting research participants:

Digital transformation is a complicated process, and any one person’s perspective will ultimately be incomplete. Because transformation within an agency involves people from multiple job functions, levels, and departments, we’re pursuing a participant recruiting approach that we call _cluster recruiting_.

Most of the time, our first contact and first interview is with a hands-on or mid-level person recruited through an 18F contact. In some cases, that initial contact is even a contractor, rather than a permanent agency employee. In the course of understanding how transformation works within that agency, we ask each participant about other people or positions that have been important in authorizing, socializing, or otherwise supporting their work. At the end of each interview, we return to the person they described as most important and ask if the current participant would be willing to make an introduction. We then schedule an interview with that person and go through the same process, which helps us gather different perspectives on the same transformation efforts.

This recruiting method has a disadvantage in that it is slow—email back and forth simply takes time—but it has allowed us to reach people outside the 18F network, and to approach them with an introduction from a trusted colleague. This has led to a very high acceptance rate on interviews, but a relatively slow pipeline of recruits. Still, we think it’s worth the time.

## Lingering questions

While we’ve identified significant controllable factors in digital transformation work, we still have many questions to pursue:

* How much of an organization needs to be transformed before the new way is seen as _the_ way?

* What does “autonomy” for staff look like within government? (Signals that are accepted within the tech industry, such as remote work and flexible hours, are not necessarily the same in public service.)

* Are failed initial releases sometimes a good thing in the long run? They can be effective drivers of attention, but they are definitely embarrassing. How can we capture what worked without replicating what didn’t?

* Can Software Development Life Cycle documents (SDLCs) and similar agency-specific governance documentation be rewritten in such a way that they will be effective in 2016 without being automatically outdated in 10 years?

* How big an administrative lift is it to transition-proof changes by formalizing policies that originally start out as exceptions in support of small experiments?

* What are successful approaches for addressing significant technical debt? How do you begin, and how do you know when you finish?

## Next steps

We’re planning to share this preliminary report with our research participants and colleagues at 18F to gather their initial reactions and feedback.

In the next phase of research, we plan to continue with cluster recruiting and interviews with the goal of developing a thorough report for public distribution. We want to include more primary evidence, quotes, and stories to document and elaborate on our findings. We intend to address any gaps uncovered in initial review, check and re-validate the hypotheses we’ve shared here, and most importantly, dig deeper for concrete practices that we can recommend broadly. _How_ have agencies gotten past the obstacle of extreme technical debt? _Which_ types of communities of practice do the most to boost staff skill and autonomy? _What_ support signals from leaders are most important?

Along with a full research report, we’re planning to translate our findings into a pithy, actionable web resource or playbook to support agencies in executing this critical work. We’re planning to share the report and web resource in a post on the 18F blog and promote the work we’re doing with other transformation teams and working groups in government.

## In conclusion

Many of our findings will likely be familiar to people interested in transformation. User contact (or a customer focus in industry) is described as critical in every modern methodology. Empowered employees and new management relationships, too, are common recommendations. Finding the right way to collect evidence of impact, and struggling to let go of old ways, are other standard themes.

To focus for a moment on the things that surprised us, there were critical elements both more and less technical than we expected. There really is a technological threshold below which a team can’t start practicing agile and expect to reap the benefits. We heard an interesting example of a team choosing to address this kind of extreme technical debt as their first agile pilot project, but in general, the paths to get over that hump are not well known.

We were also surprised by the extent to which ongoing advocacy and communication work and emotional labor was involved in the most successful efforts. However digital and computer-focused the type of work, it is still done by people, and people need support structures in order to embrace change. Building those support structures requires significant skill and social/organizational capital. When we read case studies of digital transformation, they tend to prioritize top-level leadership (which we agree is important) but then undersell the role of mid-senior level, trusted, knowledgeable personnel spending their days answering questions, organizing meetings and working groups, and creating safe spaces for their organizations to learn. Supporting this work explicitly is crucial to the success of transformation efforts in government.

Finally, the role of authoritative documents surprised us, and that is perhaps a function of our own biases as technologists coming to government from industry. We discovered that every chain of people working on technology in government eventually reports up to someone who doesn’t have tech or digital as an explicit priority in their portfolio. The people managing those interactions with nontechnical leadership need bridges to another way of thinking about technical choices, and memos, playbooks, white papers, and the like play an important role in reducing perceived risks and setting precedents.

We initially did not expect a traditional report to be a critical outcome of this project, but now we’re committed to serving that final user need. We hope to develop this work further—with more specifics on successful approaches especially at the leadership and management levels—and turn it into a resource that can be relied on by others in government working to capture and extend the gains of innovation projects.

Thank you for reading, and we welcome your comments.

## Appendix

### References

* [Change Has Come to the White House](https://www.whitehouse.gov/blog/2009/01/20/change-has-come-whitehousegov), Macon Phillips
* [Digital Government Strategy](https://www.whitehouse.gov/sites/default/files/omb/egov/digital-government/digital-government-strategy.pdf)
* [U.S. Digital Services Playbook](https://playbook.cio.gov/)
* [OMB Memorandum M-13-13, Open Data Policy](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2013/m-13-13.pdf)
* [OMB Memorandum M-16-12, Software Licensing](https://obamawhitehouse.archives.gov/sites/default/files/omb/memoranda/2016/m-16-12_1.pdf)
* [TechFAR (Federal Acquisition Regulation) Handbook](https://playbook.cio.gov/techfar/)
* [Circular A-130, Managing Information as a Strategic Resource](https://github.com/ombegov/a130/)
* [Information Technology: Federal Agencies Need To Address Aging Legacy Systems, GAO Report](http://www.gao.gov/products/GAO-16-468)
* [NYC Digital Playbook](https://playbook.cityofnewyork.us/)
* [Design Principles](https://www.gov.uk/design-principles), GOV.UK
* [DirectGov 2010 and Beyond: Revolution, not Evolution](https://www.gov.uk/government/publications/directgov-2010-and-beyond-revolution-not-evolution-a-report-by-martha-lane-fox), GOV.UK
* [The CIO Problem](https://medium.com/code-for-america/the-cio-problem-part-1-678ae2e9d0bf?source=user_profile---------2-) and [The CIO Problem Part 2: Innovation](https://medium.com/code-for-america/the-cio-problem-part-2-innovation-af24ebc038e5?source=user_profile---------1-), Jennifer Pahlka
* [Slow Ideas](http://www.newyorker.com/magazine/2013/07/29/slow-ideas), Atul Gawande

### Team

Alex Pandel, project lead  
Cyd Harrell, research lead  
Nicole Fenton, content designer and researcher  
Nikki Zeichner, industry and policy researcher

### About 18F

18F is an office inside the General Services Administration that helps other federal agencies build, buy, and share efficient and easy-to-use digital services. We’re a team of technology experts that work with agencies to diagnose problems and then work alongside agency teams to find the right solutions.
