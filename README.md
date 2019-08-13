# Foreword
These are a few questions I've gathered based on my experiences in a few orgs. PRs welcome! (especially on culture and diversity topics)


# Questions to ask
- [ ] VCS? Github/gitlab?
- [ ] CI ? 
	- [ ] How many apps/targets/schemes?
	- [ ] How big is your Fastfile?
	- [ ] Does it have several environment references (ENV["Something"] make things more difficult to debug)?
	- [ ] Can you dry run a lane on your machine right now (CI machines should not be *unique* in any way, if possible)?
	- [ ] Codesigning? 
	- [ ] Does your CI script modify the project before building it (other than say, incrementing build numbers?). (More mutation = more unpredictable CI builds)
- [ ] Testing ? 
	- [ ] Does the management feel testing is not an important aspect of software development / can be taken up later?
	- [ ] How many people in the team have heard about Test Driven Development?
	- [ ] What are the types of test you write (Unit/Integration/functional/UI)?
- [ ] What architectural patterns are you using to make development easier or more consistent? What problems with your current approach have you come across after settling on one (if you have one)?
- [ ] Team/People
	- [ ] comms - slack?
	<!--alex ignore sick-->
	- [ ] Do people ever take sick days to get work done?
	- [ ] When was the last time someone worked a late night/weekend in order to meet a deadline?
	- [ ] Does the company support/allow remote work? How about working from home?
	- [ ] How many meetings do you have in a day? Do you have the liberty to say no to meetings?
	- [ ] Does your calendar look like a losing game of tetris? Do you have large continuous uninterrupted hours?
	- [ ] Are there any private spaces in your office?
	- [ ] Is there  a gym/field/court close to your office for physical activity?
	- [ ] Do people feel comfortable calling attention to systemic issues/heavily “band-aid”-ed systems?
	- [ ] Are any of your engineering managers mobile engineers? Do mobile devs feel like they have to learn backend dev to "prove themselves" / feel like they have a seat at the table?
- [ ] Designers?
	- [ ] What’s the handoff process like?
	- [ ] Do you let devs get into the weeds and edit/view sketch files (as opposed to say, viewing them through zeplin/invision)?
	- [ ] Do you focus on making your android and iOS apps look consistent?
	- [ ] Example of the above: Do you have the “title” of a VC on the left in iOS/on the center in android for consistency? Do you have a modal View Controller presented with a back arrow on the left?
- [ ] Q/A?
	- [ ] What’s the handoff-to-QA process like?
	- [ ] How does the QA team test applications? How is regression testing done? Is there any test automation present?
- [ ] Learning
	- [ ] Do you sponsor conference tickets?
	- [ ] Books/online resources?
- [ ] Product
	- [ ] Do devs get access to support tickets? 
	- [ ] How involved are devs in product decisions?
	- [ ] Do you consider the societal impact of the products you’re making?
	- [ ] Does your marketing org ensure your marketing materials are inclusive (I like to call this the [Revolut filter](https://twitter.com/ingridepure/status/1097486380152827904)) ?
- [ ] QoL
	- [ ] Does your workplace overly manage MacBooks at work (I've learnt places lock down sudo, don't allow App Store access etc which is utterly foolish)
	- [ ] Do you have an open office?
	- [ ] If you do, do you have private spaces? Do people quarrel over the few private spaces like in WeWork locations around the world? https://www.wsj.com/articles/the-best-spot-in-the-office-is-a-phone-boothif-you-can-get-into-one-1543333379
- [ ] I found this _amazing_ twitter thread about ["Bellweather" questions - these do a lot about revealing the culture of an org](https://twitter.com/joshwcomeau/status/1160592395131641861?s=123). IMHO, there is a little bit of bias - there are some really small, really good teams encumbered by bureaucracy in large cos, but I would still think working at these places wouldn’t be too bad. Then again, this really depends on you personally. PS: I've tried to paraphrase the tweets - I really suggest you click and open the original tweets if you can. Here's my favorite questions:
	- [ ] [Do people actually use "unlimited" PTO](https://twitter.com/jbrancha/status/1160678967529156608)
	- [ ] [Is there bureaucracy around procurement?](https://twitter.com/JoshWComeau/status/1160592396918448128)
	- [ ] [How long would it take to make a copy change?](https://twitter.com/marcuslyons_/status/1160594191153393664). Honestly, I'd consider anything over an hour (including build and deploy time) a red flag. Also, excellent @patio thread in the replies!
	- [ ] [How do you solve disagreement between engineers?](https://twitter.com/xander76/status/1160670531785580545). Great point about HiPPO in the replies.
	- [ ] Another great list: https://gist.github.com/vcarl/14275c72baf976ff1665392e14225dcc
	- [ ] [How did this position become open?](https://twitter.com/jm_rives/status/1160627079135633409). If the person mumbles something about "not hardworking enough" or "not a great fit", you might want to prod further.
	- [ ] "What’s special about this org that you wouldnt have anywhere else?" - this I got from @tal who is awesome (Hi Tal!)
