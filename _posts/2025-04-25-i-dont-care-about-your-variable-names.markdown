PR reviews aren’t about taste. They’re about trust.

Every engineer has a PR review horror story. I once worked somewhere where a dev would edit _my_ comments on PRs for spelling.

Not the code. Not the tests. The comments. Quite why Github even has this feature I couldn't tell you - but the silent edit, the pedantry, taught me more about engineering culture than any onboarding doc ever could:

Some people review to collaborate, others review to control.

## Most of the time, "LGTM" is enough

I’m not here to optimise your nouns.
I’m here to help us ship things that don’t break, solve a problem, and isn't going to make future us sad.

Too often we confuse polish with clarity. And so reviews turn into taste audits and nitpick sessions. We’ve started correcting things that don’t need correcting. Not because they’re wrong, just because they’re not how we would have written them.

Most of the time, "LGTM" is enough. And it ain't lazy, it’s generous. It’s a way of saying: "This isn’t how I’d have done it, but it works. Let’s keep moving."

Not everything needs to be maximally idiomatic.
Not every block of code needs to teach the secrets of the monad.
Sometimes it just needs to pass the tests, make sense to the person who wrote it, not take down production and not make the linter too angry.

Obviously, there are exceptions. Critical systems, tricky edge cases, anything security-related — those deserve extra scrutiny. But most of the time, we’re just trying to ship something solid and understandable.

If I think it might break, I’ll say so. And if I think it’s confusing or dangerous I’ll raise it.
But if the worst thing I can say is "this could be cleaner"?

![Ship It](/assets/images/shipit.jpg)

Now, I'm not saying don't express your preferences when reviewing. Or hold back from giving advice. But make it just that - advice. Unless you see a genuine reason to block, *approve* with "you might try this" or "you could write this like that".  


## Let people learn by doing, not by pleasing

The best engineers don’t just read the right blog posts and absorb the correct patterns.
They learn by making things.
By getting it slightly wrong.
By fixing it.
And by noticing what changed and why it mattered.

PR reviews should protect that process - not interrupt it.

If we treat every review like a search for perfection, people stop exploring.
They write for approval, not for clarity.
They start anticipating nitpicks instead of thinking in systems.

But if you let someone ship something that’s good enough but imperfect, they get something even better than approval: a chance to learn from experience.

That’s how taste develops. That’s how confidence grows.
That’s how you turn engineers into problem solvers - not just rule followers.

Code review is a collaboration, not a performance

Your job in a review isn’t to win.
It’s to understand.
- Does this make sense?
- Does it do what it claims to do?
- Will this create more pain later?
- Does the person who wrote it seem like they learned something?

If the answer to those is yes, you don’t need to rewrite their variable names to prove you’ve read the file.
