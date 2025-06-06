---
title: AI got no taste
---
I like AI. Let’s get that out of the way.

It’s useful. Sometimes it’s clever. Occasionally, it’s right in that way that makes you look at the laptop like it might wink at you. But here’s the thing: it’s got no taste.

You know what I mean, right? It can write code. Or copy. Or make an entire onboarding flow if you let it. But it has no idea whether what it just did is good. Or boring. Or going to bring prod down. It just did something plausible, maybe coherent, vaguely shaped like an answer. You watched the agent spend 5 minuites trying to run a test only to eventually `cat` it and realize the file didn't exist. 

And maybe that’s fine for now. Maybe “plausible” gets you through the sprint or your demo built. But long term? Long term is where taste lives.

![pls](/assets/images/taste.png)

## Taste is what stops a system from turning into soup

What do I mean by something as silly as taste?

It’s the difference between a service you can confidently extend, and one you have to look at sideways for fear it breaks just from being perceived. 

When we talk about “well-architected systems” or “clean code” or any of the other phrases we’ve collectively stripped of meaning, what we actually mean (if we mean anything) is taste. A sense that someone, somewhere, gave a shit. Made a call. Chose not to chase every abstraction dragon into the fog. Thought about their future selves when it's time to change the system.

Taste is what makes things maintainable.

And yeah, we’ve tried to codify it. SOLID. DRY. YAGNI. KISS. A load of little mnemonics from animal covered tech books. And fair enough they’re often not *wrong*, but they’re just the guard rails. Taste is what happens between them. It’s the difference between “this follows the rules” and “this doesn’t make me want to delete it all and start again.”

## The strange part is AI *should* have taste

It’s seen more code than any human ever will. Whole GitHubs full of it. The good, the bad, the Stack Overflow. You’d think it would have developed a sense of style by now. Or at least be less happy about having to do so much Python.

But it hasn’t. Because taste doesn’t come from exposure alone. It comes from judgment. From experience doing painful things. From fucking up and finding out. From suffering.

AI isn’t opinionated. It doesn’t have a favourite way to do things. It doesn’t recoil at a three-level nested service layer. It’s not haunted by the time it tried to genericise everything and ended up with `BaseBaseControllerService`. It’s not proud of a bit of craft, or ashamed of a shortcut. It doesn’t learn lessons, it just makes predictions. It has no concept of "this will hurt me later".

Try it now, ask it to do something and watch it litter the code with:

```ruby
  # save the user
  @user.save
```

Taste is what happens when experience meets values. AI has the former, but none of the latter.

## The trouble is, taste is slow

Taste needs context. Experience. Curiosity. Ten rounds with some legacy code and a whiteboard on a PiP. You can’t prompt-engineer it. You can't ship a PRD that says “make it tasteful.” You have to feel it. You have to *know* that “just chucking in a kafka queue” isn’t always the flex you think it is.

### And to be clear: you probably *should* use AI

It’ll make you faster. Sometimes *much* faster. It’s incredible at blank pages and boilerplate. Great at filling in gaps you can’t be bothered to fill yourself. It’ll scaffold a service, mock a test, rewrite a README, and help you avoid typing the same three boring lines for the fifth time today. It’s not taste, but it is speed, and that's not bad. You just have to point it in the right direction. Like a Roomba with a machete.


## That said, you *can* use AI to express your taste

With the right nudges, examples, patterns, prompts—it can absolutely be your sous-chef. You make the calls; it preps the ingredients. If you know what “good” looks like, you can get it to draft five slightly-wrong versions and pick the one that feels right. You can iterate. Direct. Sculpt.

But that’s not what agents are for.

The whole point of the “AI agent” thing is that they go off and do a bunch of stuff *without you*. That they take a vague task and break it down and just handle it. And the problem is, taste doesn’t survive delegation very well.

An agent doesn’t know when something’s *just fine* versus when it’s *ghastly but functional*. 

When it’s doing ten steps in a row, you don’t get to insert that frown you would’ve done at step three. No matter how many times you tell it you'll send it to prison if it doesn't make the code better

And that’s the problem: the more you hand over to an agent, the less of your taste gets through and the harder it it to make the next change without an agent. 

You can really strictly review it. Tell it to do it again, but like this or like that. Have you saved any time?


## So maybe we end up with a world full of plausible systems

Things that technically work. Products that feel a bit like template demos. Codebases that just about hold together, but will need 25 million tokens and a small prayer to add an unexpected feature, because underneath it's a fucking mess. 

Or maybe, and this is the hopeful bit, we get better at teaching taste. At encoding it. At making it part of our tooling and training and team culture. Maybe taste stops being this ephemeral thing that lives in the back of your brain and starts being something you can actually share.

Or maybe we just teach it to suffer like we do.
