I'd think carefully about letting AI code reviews become the norm.

Code reviews can be boring, difficult, or both. Everyone hates how long they can take. So why not just automate them away using the power of large language models?

I suspect a lot of what people will say about AI code reviews will be some sort of worrying about correctness. What if it misses some glaring error? What if we take production down because the machine said something was great when it was a mess? I'm not too worried about the ability to review. I'm sure it's been benchmarked and it's most likely fine - I'm almost certain it'd do a better job of reviewing a pile of tailwind styling changes than I would.

But in the same way unit tests aren't really for proving your code to be correct, reviews aren't really about avoiding mistakes.

A good review does two things for two or more people

## It collects the thoughts of the author

Write a description if it's complicated. If it's big (and it shouldn't be) give reviewing instructions or break the changes up into logical commits. Hell, if you've realized it's going to be hard to review reconsider if you still think what you've done is a shippable-unit.

# It helps the reviewer understand what the hell they're maintaining.

Now I don't know about you, but I don't read my codebases for fun. Most of what's there I see for the first time in review and then probably not again until I need to fix something or add something. Seeing code go by, asking questions, and understanding the 'why' – even superficially sometimes – turns 'their code' into 'our code'.

## What'll happen (maybe, idk)

Pessimistically, I suspect what'll inevitably happen (because no one is lazier than an engineer) is that as an industry, we'll slowly stop doing human reviews. PRs will grow increasingly large and unreviewable except by the dogged determinism of a GPU boiling a lake. We'll lose the shared context of what's being shipped in our teams beyond the ticket level. 

Maybe people will have to start doing UML diagrams again.