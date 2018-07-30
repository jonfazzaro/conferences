# Beer City Code 
*June 23, 2018*

## Keynote: The Post-JavaScript Apocalypse 
with [Douglas Crockford](https://www.crockford.com/)

![](https://pbs.twimg.com/media/DgYUOB1WsAAD7e9.jpg)

### Clutter in JavaScript

**Konmari**  
When decluttering, gather your things.  
For each thing, hold it and ask yourself, "does this spark joy?"  
If not, say "Thank you for your service", and discard it.

*in JavaScript*  
`var` < `let` < `const`  
`'` < `"`  
`null` < `undefined`  

*in general*  
tabs < spaces  
[NULL](https://en.wikipedia.org/wiki/Tony_Hoare#Apologies_and_retractions) < an immutable, empty object

### Pure functional programming
If our code never has side-effects and is 100% functionally pure, we will not only eliminate disk and network access, but also user interaction and any value provided by the software whatsoever.

> The Universe is mutating. Use purity when you can.

[DEC64](http://dec64.com)  
A better number type that is "intended to be the only number type in the next generation of application programming languages", and does not encounter the issues we currently have when working with floating point numbers.

### Reserved words
Having a word in a language that no programmer can use as a name is a restriction based on the constraints of the 1950's. 

Instead, the language tools should be smart enough to understand whether the word is being used as a name or a keyword. This would enable freer naming in code while also allowing language developers to implement new language features without fear of breaking existing code.

### Q&A

> I don't have an answer to that. I'm sorry.

(In response to a question he either didn't have anything to say about, didn't know about, or didn't want to spend time on.)

Code font used in presentation (and in his editor): [Programma](http://programma.us/).

Correct pronunciation of JSON: *zhah-SOHN*.

Web Assembly is less open than JavaScript, and in terms of performance, tunes the part of the system that does not need to be tuned.

He has eliminated the use of the `this` keyword from his JavaScript because of its unreliability. (Me too)  

On attempts to make js more Object-Oriented:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">“People who use classes in JavaScript will go to their graves never knowing how miserable they were.” ~ Douglas Crockford, just now at <a href="https://twitter.com/hashtag/BeerCityCode?src=hash&amp;ref_src=twsrc%5Etfw">#BeerCityCode</a></p>&mdash; Fazzaro (@jonfazzaro) <a href="https://twitter.com/jonfazzaro/status/1010522090678702083?ref_src=twsrc%5Etfw">June 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


## I'd Hire More Women if They Would Apply! 
with [Ronda Bergman](https://twitter.com/rabergman)

### Diversity
Not just because diversity--diversity in teams leads to their being more robust, better solutions to problems, and lower turnover.

Speaking of turnover, **replacing an employee costs up to 213% of their base salary**.

So, greater diversity on a team leads to more profit.

Companies that are not diverse typically don't have a sexism problem. Not explicitly, at least. The problem is that women tend not to even apply for their jobs because of the way the company presents them, and itself.

### Better job postings

#### DON'T
Aggressive, dominant wording  
Rockstar/Ninja/Guru  
Bro-culture (foosball tournament listed as a perk)
Gender-specific words ("our guys", "craftsman")

#### DO
Gender-neutral words  
Promote real perks (work-life balance, paternity leave)

### Better hiring
Get rid of "culture fit" interviews. Think instead in terms of a "culture add".

Track your applicants through the hiring funnel. Where are the non-white-male folks falling off?

### Resources
[Gender Decoder](http://gender-decoder.katmatfield.com/)  
[textio](https://textio.com/)  

NPM's [job postings](https://twitter.com/npm_hiring) and [culture broadcasting](https://www.npmjs.com/jobs) are good examples of all this in action.  

## Uncovering the Hidden Strengths and Expertise on Your Team 
with [Brianna Marshall](https://www.linkedin.com/in/brianna-yael/) and [Kelsey Perdue](https://www.linkedin.com/in/kelseyperdue/)

### Optimal Teams
An **optimal team** is a group of *happy people* who are responsible for an *amazing product*.

Optimal teams have four characteristics emphasized.  

1. **Asset-focus**   
They spend time *strengthening their strengths* (over remediating their weaknesses).

2. **Psychological Safety**  
If they are afraid to fail, they won't try anything new.  
More emphasis on communication than productivity  
Rely on trust and respect, rather than on specific practices  
See Google's [Project Aristotle](https://rework.withgoogle.com/print/guides/5721312655835136/)  
  
3. **Diversity**  
In age, race, ethnicity, etc. BUT ALSO across work style, first language, socioeconomic background, etc. (see [Loden's Wheel](http://www.loden.com/Web_Stuff/Dimensions.html))  

	There are three levels of diversity.
	
	1. **Compositional**. There are diverse people on the team.
	2. **Interactional**. The team actively engages in positive interaction and perspective sharing across diverse backgrounds
	3. **Structural**. Diversity is necessary to the team's work, and cannot be reversed.

4. **Inclusivity**  
Diversity in the team/org is not simply tolerated, it is actively encouraged and promoted.

### Covering
A person is **covering** when they are hiding an aspect of their personal lives (religion, sexual orientation, disability, hobby, etc.) from their coworkers. This tends to decrease the person's sense of opportunity from and commitment to the team's work.

Bring your whole selves to work, to the team. This doesn't mean interfering in the work of the team by espousing your radical political opinions so much as it means stop spending energy/cycles on *concealing* them and keeping them from influencing your choices. They may be valuable in terms of your unique creative contribution.

### Cultural Intelligence
How well your organization relates and works effectively across cultures. Analogous to Emotional Intelligence.

You may have a conversation with people who feel that "we're fine" with the as-is diversity (or lack thereof) in the company. And they may be right--you're *fine*. But consider the **opportunity cost**: how much better/happier/more competitive could you be with more?

## Give Feedback Fearlessly
with [Aisha Blake](https://twitter.com/aishablake)

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Giving feedback using the oft-recommended shit sandwich (compliment, criticism, compliment) format just dilutes/discounts the message. ~ <a href="https://twitter.com/AishaBlake?ref_src=twsrc%5Etfw">@AishaBlake</a> <a href="https://twitter.com/hashtag/beercitycode?src=hash&amp;ref_src=twsrc%5Etfw">#beercitycode</a></p>&mdash; Fazzaro (@jonfazzaro) <a href="https://twitter.com/jonfazzaro/status/1010583623882498050?ref_src=twsrc%5Etfw">June 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### When giving feedback to a coworker (or any other human being)
1. **Be specific**. Make sure what you say is focused and actionable.
2. **Deliver proactively**. Don't wait until the problem is too big to solve. But also, wait for a pattern instead of jumping on someone who maybe just had a bad day.
3. **Take a breath**. Wait until you're not angry.
4. **Check your bias**. Everyone has a unique perception and lived experience. Take this into account between you and the person you're dealing with.  
	State the facts, then describe the result from your perspective.  
	"When you (did the thing), that made me (feel bad)".
5. **Invite discussion**. Listen more than you speak, it may clear things up drastically.

**Further reading**  
[Crucial Conversations](https://www.amazon.com/Crucial-Conversations-Talking-Stakes-Second-ebook/dp/B005K0AYH4/)   
[Radical Candor](https://www.amazon.com/Radical-Candor-What-Want-Saying/dp/1509845364/)  

## Becoming an Effective Mentor
with [Olivia Liddell](https://twitter.com/oliravi)

The word mentor comes from the Odyssey, in which Mentor was a character.
> In his old age Mentor was a friend of Odysseus who placed Mentor and Odysseus' foster-brother Eumaeus in charge of his son Telemachus, and of Odysseus' palace, when Odysseus left for the Trojan War.

### What is my unique value as a mentor?

1. Pick five people you know. Have them complete the following sentence in relation to you.  
"I am at my best when..."
1. Find the pattern in their responses
1. Use the pattern to compose a self-portrait of you as a mentor

What did you struggle with at the start of your career?  
What would you do differently if you had to do it again?  

### Formal vs. Informal Mentoring

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Let the mentee drive things in a mentoring relationship, whether formal or informal. ~ <a href="https://twitter.com/oliravi?ref_src=twsrc%5Etfw">@oliravi</a> <a href="https://twitter.com/hashtag/beercitycode?src=hash&amp;ref_src=twsrc%5Etfw">#beercitycode</a></p>&mdash; Fazzaro (@jonfazzaro) <a href="https://twitter.com/jonfazzaro/status/1010598156436934656?ref_src=twsrc%5Etfw">June 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Informal
Mentor/mentee self-select one another  
The relationship is casual, not measured  
To begin, seek out and connect  
Don't force it  
Be approachable  

Hold an internal [speed-networking](https://en.wikipedia.org/wiki/Speed_networking) event to foster informal mentorships.

#### Formal
Established/assigned "on-paper"  
Goals are set, tracked, and measured  

### Backward Design
1. Identify desired outcomes
2. Determine acceptable evidence 
3. Plan learning experiences and instruction

(That sure sounds like *User Story*, *Acceptance Criteria*, and *Architecture*)

### Listen
Two ears, one mouth.

#### Give feedback
Active listening  
Paraphrasing  
Asking clarifying questions
Be mindful of body language and presence  
Consider the other person's perspective  
Be specific and direct  
Make suggestions and explain the "why"

### Write
to clarify the words you use when you speak.

*What are you afraid of as a mentor?*

## Antifragile Teams
with [Charlie Sweet](https://twitter.com/mkecharlie)

### Antifragility
What is the opposite of "fragile"? Not robust/durable--those things only resist damage when stressed. 

If something is the opposite of "fragile", it gets *stronger* under stress. **Antifragile**.

**Eustress**, the good kind of stress.  
Moderate, not extreme.  
Periodic, not chronic.  
Like good exercise.

#### Volatility 
The restaurant industry is volatile. It's a difficult business to run. Restaurants are closing (and new ones are opening) all the time. The upshot: there's always somewhere to go to lunch.

The banking industry is not volatile. It's highly regulated, and has the appearance of stability. The upshot: when something goes wrong, it goes very wrong, and the effects [ripple through the whole economy](https://en.wikipedia.org/wiki/Great_Recession).

#### More examples
Martin Luther King, Jr.'s 1963 "I have a dream" speech was improvised. He was faltering in delivering his prepared remarks, but when Mahalia Jackson prompted him from the crowd to "[Tell them about the dream, Martin!](https://www.nytimes.com/2013/08/28/opinion/mahalia-jackson-and-kings-rhetorical-improvisation.html)", the words that everyone remembers came flooding in. 

Netflix's [Chaos Monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey), of course.

[Dynamic Reteaming](https://www.agilealliance.org/resources/experience-reports/dynamic-reteaming-how-we-thrive-by-rebuilding-teams/)

#### Procrustean Bed
> A Procrustean bed is an arbitrary standard to which exact conformity is forced. Named for [Procrustes](https://en.wikipedia.org/wiki/Procrustes#Cultural_references), the bandit from Greek mythology who stretched or amputated the limbs of travelers to make them conform to the length of his bed.

### Teams

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Most of the groups we call “teams” are probably better described as “working groups”. <a href="https://twitter.com/mkeCharlie?ref_src=twsrc%5Etfw">@mkeCharlie</a> <a href="https://twitter.com/hashtag/antifragile?src=hash&amp;ref_src=twsrc%5Etfw">#antifragile</a> <a href="https://twitter.com/hashtag/beercitycode?src=hash&amp;ref_src=twsrc%5Etfw">#beercitycode</a></p>&mdash; Fazzaro (@jonfazzaro) <a href="https://twitter.com/jonfazzaro/status/1010620838389997570?ref_src=twsrc%5Etfw">June 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

A **working group** is a collection of *independent* individuals applying effort to the same work.

A **team** is an *interdependent*, interactive group who's value is greater than the sum of its parts.

If you want to build an actual team  

DON'T use **the 5U method** of building a team: "Okay, you, you, you, you, and you! You're a team."

DO define **who is on the team** and **who is not on the team** explicitly. Set clear expectations and drawing clear boundaries, these constraints free both parties to do better work and collaborate more effectively.

[Psychological Safety](https://rework.withgoogle.com/print/guides/5721312655835136/) is the most important prerequisite to a great team.

#### [Amy Edmonson](https://g.co/kgs/k5yRbD)'s Questions
For identifying whether your team is psychologically safe.

1. If you make a mistake on this team, will it be held against you?  
1. Are members of this team able to bring up problems and tough issues?  
1. Do people on this team sometimes reject others for being different?  
1. Is it safe to take risk on this team?  
1. Is it difficult to ask other members of this team for help?  
1. Would anyone on the team deliberately act in a way that undermines efforts?  
1. Working with members of this team, are unique skills and talents are valued and utilized? 

(Maybe we should use these in a retrospective?)

BTW: A **knowledge worker** is a person who knows how to do their job better than their manager does.

### Antifragile Teams

#### *Via Negativa*
> a way of describing something by saying what it is not, especially denying that any finite concept of attribute can be identified with or used of God or ultimate reality.

So, what can we STOP doing that will make our team more Antifragile? 

- Premature over-standardization
- Metrics for managers (they're for the team!)
- Having a separate support development team 
	- deprives the support devs of working on the new hotness
	- denies the tiger team exposure to the results of their actions
- Long-lived teams

And what can we START doing?

- The job of an Agile Coach is to grow the team by keeping them in eustress
- Embrace volatility, rather than avoiding it
- Establish psychological safety
- Push "[power to the edges](https://en.wikipedia.org/wiki/Power_to_the_edge_(management_technique))"--establish the goal and direction, but defer decisions down to the team.

**Further reading**  
[Antifragile](https://www.amazon.com/dp/B0083DJWGO/)  
[The Wisdom of Teams](https://www.amazon.com/dp/B00WDDOS7I/)

**Performance note**. Charlie frequently *turned off the slides* while talking. This was an excellent use of negative space during his talk. It removed the subtle distraction of an irrelevant slide when he was speaking about something that he did not necessarily have a visual for. It was super-effective.

## What I've learned interviewing more than 200 people face to face
with [Michael Stahnke](https://twitter.com/stahnma)

When deciding on a candidate, ask: "If you only got to hire one person this year, would this person be it?"

Make a **Scorecard** for the job.  
1. Define success for the role in terms of outcomes.  
2. Write the job description based on that.  

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Diversity and inclusion begin at the hiring pipeline, in the wording of the job description. ~ Michael Stahnke <a href="https://twitter.com/hashtag/BeerCityCode?src=hash&amp;ref_src=twsrc%5Etfw">#BeerCityCode</a></p>&mdash; Fazzaro (@jonfazzaro) <a href="https://twitter.com/jonfazzaro/status/1010621314250498049?ref_src=twsrc%5Etfw">June 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Make sure that the interview panel isn't ALL WHITE DUDES. Observe how the candidate treats/relates to the interviewers who are female/non-white/etc.

Scrap the "culture" interview--that's how you find a friend, not fill a job.

**Interview questions**  
"Tell me about a time you pushed back on management."  
"Tell me about something you did that you are really proud of."

After the interview, with you fellow interviewers:  

- Have a gladiator-style thumbs-up/down vote.  
- Retrospect on the interview process.  
- **Put your evaluation of the candidate in writing**. This is good for two reasons:  

	1. Writing makes you and your team think through what otherwise might be a flip/emotional/gut decision  
	2. Having your reasoning in writing is good legal protection in case a rejected applicant attempts litigation

**Applicant tracking**  
[Jobscore](https://www.jobscore.com/)  
[Greenhouse](http://www.greenhouse.io/)  

**Further reading**  
[Who](https://www.amazon.com/dp/B001EL6RWY/)

## Urban Legends: What You Code Makes You Who You Are
with [PJ Hagerty](https://twitter.com/aspleenic)

Our developer communities are too siloed. We should not have *Python*, *.NET*, or *JavaScript* meetups--we should have *Tech* meetups. *Developer* meetups.

Cross-pollination over specialization. Seeking diversity in teams, not the next *Rockstar* *Ninja* *Guru* *Wizard*.

**DevRel (Developer Relations)**. A team that coordinates cross-functional communication between developers and other non-technical teams. Either internal or consultative. See [DevRelate](http://www.devrelate.io/).