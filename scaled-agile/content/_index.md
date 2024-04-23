+++
title = "migrating-to-SAFe"
outputs = ["Reveal"]
[reveal_hugo]
theme = "night"
margin = 0.2
transition = "slide"
transition_speed = "fast"
+++


{{% section %}}

## Migrating to Scaled Agile Framework

<b> (SAFe) </b>

An anecdotal story
  
<span style="font-size:0.5em;">By: Russ Harrington</span>

{{% /section %}}

---

## Outline

- Scaled Agile Framework
- Project Background
- Migration to Agile
- Migration to Scaled Agile
- Scaled Agile Framework in Action
- Lessons Learned
- References

---

### Scaled Agile Framework

<img src="Portfolio.png" />
<a href="https://scaledagileframework.com/" target="_blank" >https://scaledagileframework.com/</a>

---

{{% section %}}

{{< slide id="intro" background-image="far-away.jpg" >}}

---

{{< slide id="logowars" background-image="coollogo.png" background-size="800px" background-color="#000000" >}}

---

## Disclaimer

All opinions in the following presentation are explicitly my own and do not necessarily represent the opinions of any company that I may have, or currently work for.

---

## Project Background

---

{{< slide id="SIZE" background-image="software-development.png" background-size="300px" background-position="right" >}}

### Project Size

- Incredibly large System of Systems!
- Thousands of engineers (Software, Systems, Test, Hardware, etc...)
- Dozens and dozens of customers
- 10s of millions of lines of source code alone.

---

### Why Migrate From Waterfall

- The waterfall model took a year or more to get capability to the customer
- Incredibly expensive when finding defects during validation testing
- Feedback loop took too long to adapt to change in priorities
- Rapid Changing landscape of technology and customer needs

{{% /section %}}

---

{{% section %}}

## Migration to Agile

---
{{< slide id="training" background-image="training-icon.jpg" background-size="600px" background-position="right" >}}

### Step 1: Training

- Project wide training blitz
- Covered agile principles and tools
- Full week of workshops
- 10-20% of Engineering and Management trained per week (8 weeks total)
- Massive initiative requires buy-in from top down

---

{{< slide id="tools" background-image="git-icon.png" background-size="600px" background-position="right" >}}

### Step 2: Adopting Tools

- Jira adoption for workflow
- Confluence adoption for documentation
- Bitbucket for GitOps
- CI/CD tools

---

{{< slide id="team-transition" background-image="diverse-team.png" background-size="600px" background-position="right" >}}

### Step 3: Team Transitions

- Project is grouped by functional domains
- Functional domain teams self-organized
  - Option to adopt Kanban or Scrum
  - Team formation and charters
  - DevOps or core-competencies
- 1-2 years of adoption across the project

---

{{< slide id="now-what" background-image="Question-Mark.png" background-size="600px" background-position="right" >}}

### Now What????

Individual teams were now planning and executing work in more agile approach

{{% fragment %}} Hardly improved the speed to customer{{% /fragment %}}
{{% fragment %}} Feed back loops still too long{{% /fragment %}}
{{% fragment %}} Requirements still very much waterfall{{% /fragment %}}
{{% fragment %}} Validation still planned for big bang deliveries{{% /fragment %}}
{{% fragment %}} Teams very resistant to change, change fatigue{{% /fragment %}}

{{% fragment %}}**Leadership** realized a more structured approach to a project of this size was needed.{{% /fragment %}}

{{% /section %}}

---

{{% section %}}

## Migration to Scaled Agile

---

{{< slide id="first-release" background-image="diverse-team.png" background-size="600px" background-position="right" >}}

### Team Re-Organization and First Few Releases

<span style="font-size:0.8em;">

{{% fragment %}}\- Still domain driven teams but organized into DevOps like teams{{% /fragment %}}
{{% fragment %}}\- Each domain appointed a Release Train Engineer{{% /fragment %}}
{{% fragment %}}\- Coordinated 2 week sprints across all teams{{% /fragment %}}
{{% fragment %}}\- Release planning events established{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- 3 month releases{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- Backlog established for 6 months{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- All sprints planned to 80% capacity{{% /fragment %}}
{{% fragment %}}\- Stakeholder buy-in on team plans{{% /fragment %}}
{{% fragment %}}\- Cross team dependency boards{{% /fragment %}}

</span>

---

{{< slide id="reflection" background-image="Question-Mark.png" background-size="800px" background-position="right" >}}

### Time for Reflection

{{% fragment %}}\- Process still too rigid for changing priorities{{% /fragment %}}
{{% fragment %}}\- Impossible for stakeholders to attend all individual team demos{{% /fragment %}}
{{% fragment %}}\- Lots of fall-over due to capacity planning{{% /fragment %}}
{{% fragment %}}\- Teams still not bought in{{% /fragment %}}

---

{{< slide id="round-2" background-image="diverse-team.png" background-size="600px" background-position="right" >}}

### Round 2: Electric Boogaloo or Great Success?

<span style="font-size:0.9em;">

{{% fragment %}}\- Sprint planning only to the next few sprints{{% /fragment %}}
{{% fragment %}}\- Continual backlog refinement{{% /fragment %}}
{{% fragment %}}\- Combined team demos{{% /fragment %}}
{{% fragment %}}\- RTE coordination events stood up{{% /fragment %}}
{{% fragment %}}\- Customer coordination events to agree on priorities{{% /fragment %}}
{{% fragment %}}\- Coordinated requirements and development{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- Just in time requirements where applicable{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- Capability threads as opposed to full delivery{{% /fragment %}}

</span>

---

{{< slide id="reflection-2" background-image="Question-Mark.png" background-size="800px" background-position="right" >}}

### Reflection on Round 2

{{% fragment %}}\- Teams able to complete more of planned scope{{% /fragment %}}
{{% fragment %}}\- Still need to incorporate validation in team activity{{% /fragment %}}
{{% fragment %}}\- More awareness across both teams and customers{{% /fragment %}}
{{% fragment %}}\- Priority shifting still causing churn{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- Invisible or Unplanned Work{{% /fragment %}}
  {{% fragment %}}&nbsp;&nbsp;\- Popup still a killer{{% /fragment %}}
{{% fragment %}}\- Reoccurring events (test event support) does not fit well into sprints{{% /fragment %}}

---

{{< slide id="round-n" background-image="diverse-team.png" background-size="600px" background-position="right" >}}

### Round N: Continual Learning

{{% fragment %}}\- Project wide retrospective collections{{% /fragment %}}
{{% fragment %}}\- Evolution and Technology teams{{% /fragment %}}
{{% fragment %}}\- Even more coordination{{% /fragment %}}
{{% fragment %}}\- Continual trim of unnecessary process{{% /fragment %}}
{{% fragment %}}\- Less rigid releases, reduce release time{{% /fragment %}}
{{% fragment %}}\- Validation built into release cycle (shift left){{% /fragment %}}
{{% fragment %}}\- Evolution of the release train{{% /fragment %}}

---

### How Scaled Agile Fits

{{% fragment %}}\- Promotes continuous learning{{% /fragment %}}
{{% fragment %}}\- Well groomed domain backlogs across the entire project{{% /fragment %}}
{{% fragment %}}\- Continuous releases, full project release 12+ times a year{{% /fragment %}}
{{% fragment %}}\- Agile across all engineering disciplines{{% /fragment %}}
{{% fragment %}}\- Support from coaches{{% /fragment %}}
{{% fragment %}}\- Engagement with customer across whole product lifecycle{{% /fragment %}}

{{% /section %}}

---

{{% section %}}

## Lessons Learned

---

{{< slide id="change" background-image="contemplation2.png" background-size="600px" background-position="right" >}}

### Change Is Hard

{{% fragment %}}\- Develop a change management plan{{% /fragment %}}
{{% fragment %}}\- Avoid change fatigue{{% /fragment %}}
{{% fragment %}}\- Need to accept that it may not go well at first{{% /fragment %}}
{{% fragment %}}\- Leadership buy-in is essential{{% /fragment %}}
{{% fragment %}}\- This may be a culture change!{{% /fragment %}}

---

{{< slide id="incremental" background-image="incremental.png" background-size="600px" background-position="right" >}}

### Incremental Progress

{{% fragment %}}\- Don't try to big bang SAFe{{% /fragment %}}
{{% fragment %}}\- Make small changes at first{{% /fragment %}}
{{% fragment %}}\- Focus on continual learning{{% /fragment %}}
{{% fragment %}}\- Start with teams, and keep them healthy{{% /fragment %}}

---

{{< slide id="framework-approach" background-image="incremental.png" background-size="600px" background-position="right" >}}

### Framework Approach

{{% fragment %}}\- SAFe can be a very large scale approach, find what fits and adapt{{% /fragment %}}
{{% fragment %}}\- Focus on value, eliminate waste{{% /fragment %}}
{{% fragment %}}\- Its more than just software development{{% /fragment %}}
{{% fragment %}}\- Use established tools, don't re-invent the wheel{{% /fragment %}}

---

{{< slide id="benefits" background-image="value-stream.png" background-size="500px" background-position="right">}}

### Benefits

{{% fragment %}}\- Once the kinks are worked out, it really shines{{% /fragment %}}
{{% fragment %}}\- It is a culture change tool{{% /fragment %}}
{{% fragment %}}\- For large projects this can be a huge enabler{{% /fragment %}}
{{% fragment %}}\- Visibility across the whole project{{% /fragment %}}
{{% fragment %}}\- Constant value mapping of the process, eliminates waste{{% /fragment %}}
{{% fragment %}}\- Has workflows and resources for all things agile{{% /fragment %}}

{{% /section %}}

---

{{< slide id="thanks" background-image="yoda.png" background-size="500px" background-position="center">}}

## Thank you

<br><br><br><br><br><br><br><br><br>
