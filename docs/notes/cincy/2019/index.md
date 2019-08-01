# CincyDeliver 2019
*July 26th, 2019*  
*Cincinnati, OH*

## A Playbook for an Agile Manager 
with [Chris Philipsen](https://www.linkedin.com/in/chris-philipsen-7929502/)

| Traditional Organizations 	| Agile Organizations 	|
|---------------------------	|---------------------	|
| Date-driven               	| Value-driven        	|
| Individual performance    	| Team performance    	|

The Agile manager is often caught in the middle of these two value systems.

When the pressure is on, we fall back on what is rote/habit/muscle-memory. In order to transform the way we work, we must intentionally pause under pressure instead, and consider carefully how we react.

### Define and Build a Great Culture

Culture happens, whether you shape it intentionally or not. The culture your organization ends up with affects the daily execution of your organization's work more than anything else.

In order to be effective, managers must get out of the weeds of the work, and focus on the people doing the work. Focus on growing these people. This comes down to **building their confidence**.

The job of a manager is to create an amazing work environment.

You will get the culture that you *build*, not the culture that you *want*.

### Strengthen Through Alignment

Be transparent, and talk about your values as a team. A lot.

A team/org that is aligned will work faster, better, and more responsively in a changing environment.

Aspire to your cultural values.

### Identify Your Leadership Principles

Get to know who you are as a leader, and broadcast it in your words, work, and actions.

Build in time for improvement.  
Build confidence in your people.  
Adopt change one step at a time.  
Meet and discuss these things regularly.  

**Further Reading**  
[Above the Line](https://www.amazon.com/Above-Line-Lessons-Leadership-Championship/dp/1101980729), by Urban Meyer

## A Developer’s Guide To Docker
with [Lee Brandt](https://about.me/leebrandt)

### Images and Containers

Image:Container::Class:Object::Blueprint:House

[Dockerhub](https://hub.docker.com/search?q=&type=image), a repo for images.

Retrieve an image from the hub:

	docker pull {name}:{tag}

Start a container from the image, running a command in interactive mode, and terminal in to it.
	
	docker run -It {name}:{tag} {cmd}

Generally, run 1 app/process per container.

Images are built up in layers (OS, Applications, configuration, etc.).

### The `Dockerfile`

Code for creating an image ("infrastructure as code").

	FROM {scratch|{image}}
	
	COPY {src(files in your app)} {dest(path on the container)}
	
	RUN {cmd}
	
### Docker compose

A .yml file that defines how to start one or more containers together (web, db, cache, etc.)

The `Dockerfile` should be shared across environments (local, test, production), while environment specifics (paths, connection strings, etc.) are defined in environment-specific `docker-compose` files.

## Rediscovering Extreme Programming: Retro or Resurgent?
with [Mark Windholtz](https://twitter.com/windholtz)

### Two conferences

There were once two conferences: **XP Universe** (run by [Robert Martin](https://en.wikipedia.org/wiki/Robert_C._Martin)) and **Agile Universe** (run by [Ken Schwaber](https://en.wikipedia.org/wiki/Ken_Schwaber)). Since their audiences and content overlapped so much, they decided to combine forces (under the **Agile Universe** name).

Years later, Agile Universe had become far more business and project management focused. Uncle Bob reflected that he did not foresee this shift away from technical focus in the agile culture.

### Quality

**External**, measured in the user's experience.  
**Internal**, measured in the developers experience, but not limited to it.

XP covers **the last agile mile**; it comprises the 20% of agile practices that deliver 80% of the promised value of agility.

| Agile Manifesto (2001)                                	| Modern Agile (2015)        	|
|-------------------------------------------------------	|----------------------------	|
| Individuals and interactions over processes and tools 	| Make people awesome        	|
| Working software over comprehensive documentation     	| Deliver Value Continuously 	|
| Customer collaboration over contract negotiation      	| Make Safety a Prerequisite 	|
| Responding to change over following a plan            	| Experiment & Learn Rapidly 	|

### Waterfall to Agile
For a team that is used to working with SDLC, they follow the **waterfall** at first (Requirements, Design, Code, Test, Deploy). But then there is a natural period of iteration after deployment, when everything is driven by Change Requests.

To introduce these teams to agility, just tell them to **skip the first part and go straight to the Change Requests**.

## Using concrete data for a more predictable flow of work
with [Dr. Chuck Suscheck](https://twitter.com/dr_chuck)

(This session drew heavily on [PSK](https://www.scrum.org/courses/professional-scrum-with-kanban-training) training material + [#noestimates](https://twitter.com/search?q=%23noestimates))

> Kanban is Scrum done right.

### Start with a better board

Not all Task Boards are Kanban Boards. A *Kanban* Board  

- reflects the team's actual process/value stream (not just To Do, Doing, Done)
- has limits on WIP on each column

Don't name columns after people's roles or job titles. This discourages collaboration and cross-functionality. When you can't pull into your "comfort" column, look right or left to move other work along.

For a new team, set initial WIP limits to 1.5-2 items per team member.

### Flow metrics

- Cycle Time
- Item Age
- WIP
- Throughput

All **passively collected**&mdash;they don't require extra effort or compliance to capture.

**Charts**  
CFD  
Scatterplot of cycle time  

With a cycle time scatterplot, we can draw lines horizontally at different altitudes to predict how long a new item is likely to take *along with a percentage of confidence in that number*.

![](https://www.agilesparks.com/wp-content/uploads/2018/05/cycletimescatterplot-1.png)

This can be used to create a **Service-Level Agreement** with your customers/stakeholders.

### How to read a CFD

![](https://www.agilesparks.com/wp-content/uploads/2018/05/cumulativeflowdiagram-2.png)

#### [Little's Law](https://en.wikipedia.org/wiki/Little%27s_law)

![](https://image.slidesharecdn.com/littleslawagileisraelmay201425mins-140601012558-phpapp01/95/littles-law-and-predictability-daniel-vacanti-agile-israel-2014-22-638.jpg?cb=1401602096)

**Further Reading**  
[Actionable Agile Metrics for Predictability](https://www.amazon.com/Actionable-Agile-Metrics-Predictability-Introduction/dp/098643633X), by Daniel Vacanti  
[Kanban Guide for Scrum Teams](https://www.scrum.org/resources/kanban-guide-scrum-teams)

## The Science of Focus: Unleashing the power of focused teams

with [Kyle Morton](https://www.linkedin.com/in/kylemortonagilecoach/)

Why can we multitask with some activities, but not with others?

Working on multiple projects incurs a cost for context switching, but mostly if the switching happens within the work day.

There are two phases to each context switch:  

1. Goal shifting
1. Rule activation/deactivation

We can lessen the impact of these if we take a break at the point that we switch contexts.

### Strategies for mitigating the negative effects of interruption and context switching

- Hold Office Hours
- Wear earphones
- Hang a STOP sign in your work area
- Block off half of the day for focused work
- Establish a "no laptops in meetings" policy/culture
- Build slack into your schedule

ELMO (Enough, Let's Move On)

## When Agile “Doesn’t work”

with [Michael Burchett](https://www.linkedin.com/in/michael-burchett)

> Regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand.

--[The Prime Directive](https://www.retrospectivewiki.org/index.php?title=The_Prime_Directive)

Applying this assumption, we can overcome any objection to agile practices.

Q: What should we do when the team achieves the Sprint Goal early?  
A: Depends on the team/product/company. Maybe pull in more work, maybe pay down technical debt, etc. Whatever you decide, it should be a team conversation, and the resulting decision should be part of your team's [Working Agreement](https://agilefaq.wordpress.com/2007/11/21/what-is-a-team-ground-rule-or-team-working-agreement/).


