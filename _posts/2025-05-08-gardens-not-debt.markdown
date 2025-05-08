---
title: It’s Not Debt, It’s a Garden
---

"FFS, not another blog post about technical debt". 

I know.

<iframe width="560" height="315" src="https://www.youtube.com/embed/i2k8jhGFJDA?si=sTLALZTdqQ9iIg_i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


But I do think we need to talk about the metaphor of "technical debt." because I think it's bad for you and your team.

It’s not just that it’s overused (it is), or that it’s often misunderstood (yep), or that it makes people outside engineering immediately glaze over (and who could blame them?). 

The real issue is: it’s the wrong metaphor. And bad metaphors shape behaviour. They shape teams. In this case, they make things worse.

"Technical debt" was meant to be a helpful analogy. Ship now, cleaning up later. And to be fair, Ward Cunningham didn’t mean it as a slur. But somewhere along the line, it turned into a stick to beat engineers with. Suddenly, any bit of messy code, any shortcut, any unfamiliar system, **“debt.”** As if someone on the team has gone on a mad one and bought a Kafka bus with Klarna.

The problem is that debt implies someone did something wrong. That you owe. That interest is mounting and you better pay it off before you get a CCJ for improper monad useage.

But that’s just not how software works. Code doesn’t sit in a spreadsheet quietly accumulating interest. It’s not a liability that can be paid off and then forgotten about. Code lives. It’s used, it’s touched by people, increasingly by machines. It grows and then withers. It needs pruning, feeding, replanting. Sometimes it needs to be ripped out and started over. That’s not debt. That’s a garden (I assume because let's be honest, I wouldn't be caught dead gardening).

A good engineering team isn’t a bunch of accountants trying to balance the books. It’s a group of gardeners, tending a living system.

Yes, there’s mess. Yes, things get overgrown. Yes, that thing we planted last summer turned out to be a weed and we found rhododendrons tank retention. But that’s not failure, it’s natural. It’s how gardens (and software) evolve. It’s also why it’s never "done." And why regular tending is part of the job, not some shameful backlog item to apologise for at the next planning session.


# So what do gardeners do?

Here’s where I think teams get stuck. They know they need to "pay off the debt" but they don’t know how, or when, or what that even means. And because the metaphor’s wrong, the tactics are often wrong too: big "debt payback" projects that take months, rightfully deprioritised, and make everyone miserable.

Let’s stop pretending we can just pull out the company credit card and settle things in a single transaction.

Gardeners don’t "fix" the garden once a quarter. They weed as they go.

So try this instead:

### Tend as you build
Don’t wait to schedule cleanup later because you wont. Make it the work. If you’re in a part of the code that’s a bit gnarly, leave it better than you found it. Not perfect, just a little less shitty. A lighter refactor here, an extra test there. Over time, this compounds. Like compost, I assume.

### Stop relying on "20% time" or cleanup days
It sounds nice on paper: a day a sprint, or a Friday every so often, to fix things. But in practice you almost definitely wont do it. If your team’s under pressure (which they probably are), that time will vanish. Pushed to next week. Overwritten by a deadline or treated as optional. It’s not that these ideas are bad, it’s that they’re too easy to cancel. And the garden just keeps growing.

### Involve the whole team
Tech health isn’t just the engineers’ secret shame. Product managers and designers should know what parts of the system are healthy and what’s choking the tomatoes. Share diagrams. Demo what’s painful. Make the garden walkable.

### Pay attention to signs of overgrowth
Slow builds. Flaky tests. Spaghetti logic. These aren’t sins but they do tell you something. Not reasons to panic, but invitations to step back and ask, "What would make this easier to grow with?"

### Celebrate the tidy-ups
If someone clears out 1,000 lines of dead code, that’s a good day. If someone unpicks a terrible interface and makes it boring even better. Brag about it. Show before-and-after. Reward the boring bits that make future work better.

### Accept some weeds
Not everything needs to be pristine. Some awkward bits of code are fine, as long as you know they’re there and they’re not strangling the rest of the garden. Every team has legacy stuff, messy corners, forgotten pots round the back. That’s not failure, that’s just what happens when things grow. It’s OK, you didn't do a bad job.
