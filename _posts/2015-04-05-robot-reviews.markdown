# I'd think carefully about letting AI code reviews become the norm

Code reivews can be boring, difficualt, or both. Everyone hates how long they can take. So why not just automate them away using the power of large langauage models?

I suspect a lot of what people will say about AI code reviews will be some sort of worrying about correctness. What if it misses some glaring error? What it we take production down because the machine said something was great when it was a mess? I'm not too worried about it's ability to review. I'm sure it's been benchmarked and it's most likely fine - I'm almost certain it'd do a better job of reviewing a pile of tailwind styling changes than I would.

But in the same way unit tests aren't _really_ for proving your code to be correct, reviews aren't _really_ about avoiding mistakes.

A good review does two things for two or more people

## It collects the thoughts of the author into shippable units

Write a description if it's complicated. If it's big (and it shouldn't be) give reviewing instructions or break the changes up into logical commits. 

