+++
baseURL = "https://www.trinitytakei.io"
Categories = ["leadership tech"]
Description = "17 Traits of Awesome Tech Leads - summary of my leadership philosophy I developed during my tenure as an engineering manager/tech lead of a Ruby on Rails team"
Tags = ["leadership","tips","methodology"]
title = "17 Traits of Awesome Tech Leads"
+++
>
> Old programmers never die.<br>
> They simply give up their resources.
>

At the time of writing, I'm not ready to give up my resources yet ( I'm a long-running process!), but I have arrived at an earlier point happening to old programmers: they are cast (or coerced) into team leads, architects, or managers.

{{< figure src="/images/3/dilbert1.gif" title="Image Credit: https://dilbert.com/strip/2017-03-24" >}}

Most of my coder friends perceive a 'promotion' like this as an epic fail of galactic proportions that any self-respecting programmer should try to avoid at all cost. At best, it's the worst thing that could happen to a coder; at worst, it's a pact with the devil (a.k.a the 'others', the non-coders, the suits, the pointy-haired bosses, the C-suite dwellers, the-guys-that-don't-do-shit-but-make-more-money-than-us), inevitably leading to your dismissal from the programmer's Valhalla on Earth and thereafter.

Dear friends, I have a confession to make: I'm having the time of my life as a team leader! I have been happy as a clam cranking out code, and I was neither planning nor wishing for this, but now that it happened, I'm even happier! [wipes laptop screen from rotten tomatoes].

Below is a summary of my leadership philosophy. I'm new to this role, so you'll likely find some youthful naïveté entwined with threads of useful advice. Unfortunately, you can't have your cake and eat it too: similar articles are either lacking due to the curse of knowledge affecting veterans or oozing with a gung-ho slant of newly found joy by a rookie.

In other words, take it with a grain of salt.

Okay, enough rambling - here's the list you actually came for, in no particular order:

### Teach Your Team to Fish

If I'm coding (fishing myself), I'm sure creating some value, but the real magic happens when I'm teaching my team to fish: by reviewing their code, mentoring them, doing workshops for them, listening and actively trying to solve their problems (even real-life ones, if they share them with me - their well-being is of paramount importance on every level, if I expect them to churn out ninja code most of the time), praising them during sprint retros for their contributions and continually looking for feedback to improve my process of doing all of the above, setting an example along the way.

### Code Reviews :  the Best Opportunity for Teaching

Probably my biggest superpower as a team leader is mentoring developers. There's more than one way to skin this cat (and then some), but I'm finding a good code review session the most effective of all. It's _organic_: rather than explaining an abstract concept or unrelated code snippet **I** find interesting, we are discussing code **he** or **she** wrote (and thus, knows intimately and understands thoroughly), so the developer has (cat)skin in the game.

A word of warning- this goes both ways: bungle a code review (ignoring the pleas for the review because you have 'more important stuff to work on' (what?!), doing a half-baked job or even scolding the committer for errors (worst idea ever)) and you'll deal more damage than you could with any other form of teaching. 

Don't take code reviews lightly, devote time to them as soon as possible and treat the author with utmost respect if you want your mentoring to sink in. Try asking 'how could we make this better?' instead of saying 'this is wrong!'

### Know thy Protégés and Help Them to Level Up Accordingly

Do not force round pegs into square holes. Case in point: no amount of pleading, rationalizing, bait-dangling or any other tactic will ever turn hardcore coders into happy team leads.

Sure, because of your authority, you can turn them into resentful managers, always yearning to go back to their beloved code - but unless your goal is to demonstrate the Peter principle in action, bad managers are… bad. 

Turn great programmers into 10x developers, and look elsewhere for future managers.

Some team members will have a knack for writing, refactoring, testing, or showing a potential of becoming good team leaders themselves - train them accordingly. Know your team members personally, and play to their strength.

### Look for Your Successor From Day One

In my previous point, I mentioned that some team members might show promising potential of becoming team leaders themselves.

Identifying and training them is THE most important task you have as a team leader: it's much more difficult to find and train future leaders than anyone else on your team. Also, future leaders will have a more profound impact on the organization than anyone else on your team.

### Teaching Soft Skills is Crucial

Even when a team member's sole task is writing code day in, day out (i.e., a typical junior to mid-level dev role), a good chunk of 'writing code' is spent on everything but writing code.

Most of the time is spent on honing the ancient art of yak shaving: communication, understanding of tasks, fumbling with git, configuring your system, updating unrelated software, mending rejected pull requests, hardware failures, documentation, wifi issues, asking questions, answering questions-the list is endless.

And then there are the non-strictly-coding tasks: meetings (that I find difficult to survive more often than not, and I'm assuming this is true for most devs), writing emails, explaining stuff, asking for raises, leveling up, office politics-another endless list.

Let me share a real-life example: I noticed that one of my more senior devs was routinely deflecting praise like a pro - all the time, without fail. I sent him this email [unredacted, except the real name]:

> Hey Joe,

> I came across this article today and it made me think about you instantly:
>
> https://anaulin.org/blog/self-deprecation-bad-habit/

> I've been with the team for less than 2 months, but I can already see that you are doing it all the time:
>
> 'Yo Joe, great work' -> you: ah, it's nothing
>
> 'Hey Joe really thanks for all the bugfixes' -> you: no, it was not a big thing, and the whole team worked on it, and it was easy and quick and …
>
> I have to call BS! You are doing fantastic work [and it's not easy, quick, etc.], right now you are the fucking Messi of the team - you practically banged out 80% of the work for the last two sprints.
>
> This is a fact [please do not reply with 'No, that's not true, because … ' :-D]
>
> I'm in the same shoes btw. - I'm fighting impostor syndrome all the time, I feel really awkward when people give me praise, and I wish they would just shut up and leave me alone :-) I have been way worse, but I'm forcing myself to get better, and just say 'Thank you' if nothing else, and move on. It feels weird, but gets better over time if you start practicing it.
>
>I liked this section:
>
>"As I've grown into leadership roles, I've also come to see the negative effects of my self-deprecating speech on my teams. If your manager or lead keeps trying to make herself small, what does that mean for you? If she really doesn't believe that she is that good, you're really a long way off from mastery yourself, aren't you?"
>
>You are eventually going to grow into a leadership role (and by seniority, you are already in a leadership role right now) and your team needs to hear that you are doing great work - so don't make yourself small (there are enough envious and malicious people who are ready to do that for you 24/7).

Joe expressed his gratitude in a reply email and indeed, I didn't notice him deflecting praise ever since, at least not in my presence.

It's not like I taught him a new language or methodology, but these small steps can add up in the long haul.

### Extreme Ownership 

This one is coming from [Jocko Willink](http://jockopodcast.com/). The leader is always responsible. _Always_. _No excuses_. _No exceptions_. _No scapegoats_.

After all,

* _I_ gathered all the info I could (woe on me if I didn't - maybe I didn't listen carefully, see the previous point, 'Always Listen')
* _I_ weighed the options diligently from the information I possessed at the time
* _I_ made the decision (if that's not the case, and I just delegated decision making to someone else by acting on their suggestion, then I failed then and there already, regardless of the outcome).

{{< figure src="/images/3/ownit.gif" title="Image Credit: https://dilbert.com/strip/2012-05-31" >}}

It's possible that my decision turned out to be a bad one, causing some distress or downright wreaking havoc. It's water under the bridge, though: whining, finger-pointing, or blaming the circumstances won't help anyone. Taking responsibility, discussing how to avoid a similar blunder in the future and cleaning up the fallout effectively, will.

### Your team consists of humans - treat them as such

Treating your devs as a bunch of drones who should be happy to execute your commands is a strategy that might work to some extent, but in the long term, it will hurt team cohesion and foster resentment.

Sure, your task is to make things happen, and you need to make decisions, give directions, delegate, and even discipline if necessary - but that doesn't mean you have to be a douchebag while doing so.

The members of your team are sentient beings who have a life outside your organization, sometimes dealing with personal issues, insecurities, office politics, and only-god-knows what else. Going the extra mile and helping them with personal issues now and then, or just giving a little encouragement at the right moment can go a long way.

### Stick your neck out for them

A few months into the project the offshore CTO came to visit us, and after a day of tiresome meetings casually announced that they are cutting the project budget by 50%. Cold shower out of the blue, if I ever saw one!

Only one thing was sure: they wanted to keep me as a full-time team lead. I had to pick team members to be removed from the project to meet the budget.

Everyone on the team was devastated: I'm leading the only Ruby on Rails team in the company; removal would mean being transferred to one of the PHP projects, and all of my team members preferred writing Ruby code.

I couldn't make a decision based on this fact - and I didn't. I made my decision based on my vision of the team members working together: by then, everyone had a dedicated place (s)he was happy with and good at, and I didn't see who could we sacrifice without maiming the team.

Therefore, I pushed for keeping everyone on-board and reduce time spent on the project by 50%. I convinced my boss that I don't see any other way out of it without hurting the team badly. In the end, everyone accepted, and my team was really grateful.

### Reciprocity, Not Authority

Related to the previous two points: if your team members repeatedly witness that you are willing to stand up for them in critical situations and you treat them with respect, they will reciprocate it by doing the same when the going gets though.

If you are doing a truly fantastic job, you won't even have to ask: they will gladly do things on their own accord. That is one surefire way to get everyone to row in the same direction. Chaining them to the ship and occasionally whipping them is another, but if you got so far, I'm sure you realize that's not my style.

{{< figure src="/images/3/listen.jpeg" title="Photo by Mohammad Metri on Unsplash" >}}

### Always Listen First. Listen Some More

If you think your role as a team leader should be exclusively focused on talking, giving commands, and generally pushing your agenda through, think again.

Sure, it's way easier to talk than to listen; in the short term, talking will produce more quantity, if not necessarily quality, than listening. However, by speaking rather than listening carefully, you are wasting the opportunity to get valuable feedback, to acquire a deep understanding of the issue at hand, to gain insights from a different perspective and so much more.

Thus, bite your tongue before everyone finished speaking, have a keen ear, and learn to read between the lines - it will help you to spot the elephants in the room. Sometimes the less experienced developers won't be able to articulate their issues unambiguously; to be able to ask clarifying questions, you need to listen first.

{{< figure src="/images/3/kindness.jpeg" title="Photo by Sandrachile . on Unsplash" >}}

### It's Not Enough to Be Right .  You Also Have to Be Kind

[This one](https://medium.com/s/story/its-not-enough-to-be-right-you-also-have-to-be-kind-b8814111fe1) is coming from one of my favorite authors, [Ryan Holiday](https://ryanholiday.net/).

Your goal is not to have the last word, but to find common ground and get the other person to agree with you. Everyone is a professor emeritus in their version of the truth, and in that world, you are just a clueless bozo.

Trying to convince anyone that your version of truth is the real truth is a fool's errand. Reaching for power in that situation will lead to resentment and resistance. You have to be delicate and skillful to turn the tide - in Ryan's words:

> Reason is easy. Being clever is easy. Humiliating someone in the wrong is easy too. But putting yourself in their shoes, kindly nudging them to where they need to be, understanding that they have emotional and irrational beliefs just like you have emotional and irrational beliefs - that's all much harder.

A necessary clarification: this does NOT mean to be aloof, or subtle, or vague (that's the other extreme, and it's communicating indecisiveness.) It's OK to dazzle your team with your brilliance, but only if you do it humbly, empowering them and making them feel like part of the solution.

### Create an upbeat atmosphere

This one might sound like a filler point, but it's far from it; it's coming from a very recent experience I'd like to share with you.

The budget cut I mentioned earlier also involved losing our project manager. I didn't see it as anything horrible at that time - we have daily standups with the CTO and another PM on the 'client side', so I thought our PM, a cheerful Aussie, was a nice addition to the team, but not a crucial one, and we won't feel his loss.

After just one sprint (two weeks) my opinion changed drastically. I realized that the energetic vibe he radiated during daily standups, ad-hoc meetings, sprint planning sessions/retros, and all the time we spent together made a huge difference. He was not a techie, and thus he didn't add much to that sort of discussion, but he filled another hole I didn't even realize existed: he got everyone pumped up and going into the day like a hero.

I'm a very introverted person, so I can't and won't even try to emulate his style, but I will make an effort to lift the team spirit on every occasion my way.

_<heavy Aussie accent> Mate_, we are sorely missing you!

### Don't lead by example

Don't try to do everything yourself, thinking that your team will be impressed by your example and follow suit. It's actually more likely that they will feel confused and disempowered: instead of trusting them with important tasks, you are all over the place. The signal it's sending is that only you are good enough to do everything.

{{< figure src="/images/3/example.jpeg" title="Photo by Jehyun Sung on Unsplash" >}}

Micromanaging suffocates. Setting clear expectations and trusting your team member's ability to carry them out empowers.

### Fight in the front line

This might sound like a contradiction to the previous point, but it actually complements it. While 'leading by example' would mean fighting alone to show how it's done, 'fighting in the front line' means leading the charge.

A few examples from history: Alexander the Great, Julius Caesar or King Leonidas (of '300' fame; fun fact: some historians estimate that he was about sixty years old when he led his men into their final battle against the Persians at Thermopylae).

{{< figure src="/images/3/300.jpeg" >}}

These leaders didn't have to move a finger when it came to fighting - their men rallied around them and considered it an honor to fight by their side.

### Get better every day and ask for feedback often

I guess no explanation is needed here - the landscape is continually shifting, and in the words of Bear Grylls: 'improvise, adapt, overcome.' Never stop learning, experimenting with new things - you can always do better!

Asking for feedback on your progress is crucial. We are horrible judges of ourselves, so always turn to people you respect and ask for their advice - be a good follower if you want to be a good leader!

### Cut yourself some slack and find plenty of time to relax

Unrelenting high-octane burn leads to burn_out_ - and that's a huge loss for your health, for your family, for your team, for your organization, for your bank account.

Don't have time to rest because there's always so much to do? Prioritize making EVEN more time for relaxing - replenishing your resources is paramount.

If your boss doesn't understand or agree with this, do yourself a favor and move on.

A side effect of winding down is that you can take a step back and see the big picture. Failing to see the forest for the trees is a typical result of constant over-involvement.

### Know when it's time to move on

Everything and everyone gets old and mundane after a certain amount of time. There's no exact formula for this, but when you feel like your growth as a leader slowed down, your team is not progressing as fast as it used to, you lost your initial passion, there's time to look for a new challenge.

Don't wait until you start stagnating, and don't be afraid to make radical changes. If you can't switch gears where you are right now, it's time to move on and embark on a new adventure.

### Think about your legacy

Even though Jesus, Buddha, Muhammad and other great prophets unquestionably did a lot of good during their life, their real impact manifested after they left - through their disciples.

{{< figure src="/images/3/prophet.jpeg" title="Photo by Adli Wahid on Unsplash" >}}

Be the prophet of your team, and do as much as you can during your time at the company, but make sure to train disciples from day one.

Treat your people as subordinates, and they will do your bidding because you have authority over them, but they will secretly throw a party when you resign.

Turn them into disciples, and they will follow in your footsteps and spread the word once you are gone.

Do this right, and the ripple effect will have a more profound impact than you could ever have accomplished or imagined.