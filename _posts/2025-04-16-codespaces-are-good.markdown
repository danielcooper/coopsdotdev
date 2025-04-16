Letting anyone ship, without the usual setup pain

One of the most useful decisions we made early on at Jitty was using GitHub Codespaces for everything. No local dev machines. No onboarding doc that’s three weeks out of date. No weird edge case where someone's version of Ruby is haunted and no one knows why.

Just: open a codespace, make a change, commit it. Done.

It’s especially good for people who don’t want to set up (and try and maintain) a whole development environment just to tweak a button colour or copy block. Our designer can spin one up, make changes directly in the app, and see them in context, and crucially _try stuff out_, without waiting for an engineer to be free. 

No Homebrew. No weird shell config (which as a fish user I appreciate). No "oh you actually need this other service running", it’s the same for everyone. Same image. Same setup. Same version of Node or Rails or whatever else we’re breaking this week.

It’s the kind of thing that doesn’t feel like a big deal until you remember how painful it was before. Especially in early teams where people float between roles and new dependencies are still being added before everything ocifies.

Some things are kinda annoying - when running locally IO performance kinda sucks between mount-points. If the base dev image needs to be rebuilt you better hope it's a decent walk to your local coffee shop. But on the whole, 10/10 would containerize again.

So, if your team still has a multi-page setup guide in Notion and a Slack channel called #dev-env-help, or every new joiner suffers though a setup day before they can do anything - give codespaces a go. Let people ship.
