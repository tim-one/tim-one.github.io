---
title: The Puzzling Moderation of Guido
---

On 25-Aug-2024, Guido van Rossum (Python's creator) posted some [very mild shade](https://discuss.python.org/t/should-we-consider-ranked-choice-voting-for-sc-elections/61880/6) at my ban, in a topic about moving to a different voting method for Steering Council (SC) elections.

>  I don’t know much about voting systems, but I know someone who does. Unfortunately he’s currently banned. Maybe we can wait until his 3-month ban expires and ask him for advice?

That's all of it. After considerable time passed, his post was "hidden" by Discourse, due to "community flags". That's a Discourse gimmick that lets anyone logged in click a button to indicate that a post should not remain visible. It's a complicated topic (ill-documented and subject to many administrator settings that are invisible to users) which I'll skip. Suffice it to say that I believe enough time passed that it really was the case that enough random users clicked the button to trigger an automatic hiding algorithm.

When that flag is clicked, the user has a choice to make about _why_ they clicked. The reason is visible to mods and the original poster, but not to users. This is the reason given for Guido's:

> Your post was flagged as inappropriate: the community feels it is offensive, abusive, to be hateful conduct or a violation of our community guidelines.

That's it. Extremely broad, and in my experience impossible to guess _what_ was found to be "offensive", etc.

Whenever I got one of these, I ignored it. Hidden posts sit in a queue waiting for moderator review, and for a long time mods always unhid my posts again on their own initiative (although very late in my pre-ban life, that changed, and it _appeared_ the mods had an agenda of hiding my posts ASAP on their own, and never unhid them again). But that doesn't matter here.

What does is that Guido's mild post was not getting unhidden by mod magic. There are more stories here about how tech-gossip sites speculated about why the PSF hid a post by Guido, and threatened to turn into another PR mini-disaster for the PSF. I'll skip those too. Suffice it to say that Guido and I both communicated with "press contacts" to assure them that it was probably just Discourse's auto-hiding algorithm at work, and that the post would soon enough become visible again.

And so it was, before any "reputable" news site reported on the tech-gossip speculations.

But it turns out there's more to this story that hasn't been told before. Guido sent direct messages to the mods to ask why his post was hidden, and one mod in particular wouldn't reply. I'll call that mod "Judge Dredd" here. Another mod did reply, and quickly made the post visible again.

After Guido & I recounted this story on Discourse, Matthew Dixon Cowles sent me email to reveal that he had asked the mods about why at the time, and got a truly remarkable reply. I assumed at first he wanted to remain anonymous, but, nope! He has courage:

> Do whatever you think is best with it including posting it publicly verbatim. And please keep my name on it. In my opinion the problem here is lack of public scrutiny and open debate.

> What are they going to do? Ban me from posting somewhere that I already don't post? Prevent me from answering questions on the python-help mailing list? Unilaterally revoke my status as a fellow? I've been kicked out of fancier clubs.

Here's the entire exchange. I've changed the name of the mod to Judge Dredd. While part of me wants to name them, larger parts don't want to accuse someone in a forum where they can't speak. Under the principle of charity, I'll just assume they were having a very hard time thinking that day, for whatever reason(s) that aren't my business.

\---------------------------------------------------------------------<br>
    **Matthew Dixon Cowles mdcowles Aug 28**

    Please tell me what rule Guido’s post violated.

    Matthew Dixon Cowles

\---------------------------------------------------------------------<br>
    **Judge Dredd doom Aug 28**

    Multiple people indicated they felt that post was inappropriate
    through flags and private discussion. The person was suspended in
    part because of their actions and statements about votes and the
    board. To turn around and suggest that they are the best person
    to ask about votes and the board is inappropriate. Especially in
    the midst of plenty of other people being able to speak to the
    nuances of voting just fine. And especially from the language
    author who wields a great amount of public attention and trust in
    anything said by them. Core team members are expected to act as
    role models for the community, and that post didn't match that
    expectation.

\---------------------------------------------------------------------<br>
    **Matthew Dixon Cowles mdcowles Aug 28**

    > Multiple people indicated they felt that post was inappropriate
    > through flags and private discussion.

    I asked about a rule.

    > The person was suspended in part because of their actions
    > and statements about votes and the board. To turn around and
    > suggest that they are the best person to ask about votes and the
    > board is inappropriate.

    You seem to be saying that Tim was banned for expressing certain
    opinions and expressing respect for his knowledge on a related
    subject is a satisfactory reason for you to cancel a post. Is
    that right?

    Matthew Dixon Cowles

\---------------------------------------------------------------------<br>
    **Judge Dredd doom Aug 28**

    > I asked about a rule.

    You can find the guidelines we expect everyone to follow here:
    Guidelines - Discussions on Python.org as well as here: Python
    Software Foundation Code of Conduct - Python Software Foundation
    Policies. We evaluate flags in the context of these guidelines in
    order to come to decisions.

    > Is that right?

    No, your interpretation does not match our understanding of the
    situation. If you’re concerned with moderation decisions beyond
    this, please send a report to the Code of Conduct team: Python
    Software Foundation Code of Conduct - Python Software Foundation
    Policies.

\---------------------------------------------------------------------<br>

And Matthew adds:

> Following Judge Dredd's suggestion, I emailed the Code of Conduct group to ask them to explain the situation since he wouldn't. They were also unwilling to provide any clarification.

I'll spell out some reasons for how absurd the claimed "reasons" for hiding are.

- Guido not a "role model"? Beneath contempt.

- I was supposedly banned for posts in an earlier topic debating whether the PSF Board should adopt some specific bylaw changes. That Board vote had nothing in common with any future SC vote. And the election method the SC wants to use bears no relation to the earlier specific bylaw changes. Thrashing at random to come up with "well, the word 'vote' is needed to discuss both" is beyond just absurd. It reeks of spectacular bad faith informing an utterly irrational conclusion.

- "Plenty of other people being able to speak to the nuances of voting just fine" is just false. People were sharing personal anecdotes, which is fine, but none showed the slightest knowledge of any election theory, or election research, or even of election methods beyond their personal experience (there are dozens I know non-trivial things about).
 
    In the PSF's history, 3 people showed non-trivial knowledge of such stuff: me, David Mertz, and Donald Stufft. I was banned for 3 months. David had been suspended from Discourse forever. Donald did chime in, but had no interest: he said SC elections are so trivial (in formal senses) that the choice of election method probably wouldn't make any difference to which 5 winners were picked. I agreed with him on that. but also had a lot of sympathy with Gregory Smith's motivating desire to switch to a method that allowed voters to express more of what they believed (in the then-current "block Approval", for each candidate you can only say "yes" or "no" - no possibility to express that you like one more than some other, or, if so, to express how strongly you like one more - it's a fine method, but can leave people frustrated with how little they can express).

- Guido told me that the other mod told him that none of the flags came from core developers. But core developers are the only ones who _can_ vote in SC elections now - they're the only ones with direct interest in the topic. None objected to Guido's post via the flag mechanism.

As things turned out, the core devs agreed to switch to "bloc STAR", thanks to Guido pushing for it. Is Guido an election theory expert? He wasn't at the time :wink:. In the background, I gave him a crash course on election theory via email, and pushed him toward STAR. He is, of course, a very quick learner, and convinced himself it was the best choice. So he spoke his own mind, and by agreement never mentioned that, in some senses, he was channeling me for a change.

But that isn't the point here either. The point is how very maddening bad moderation policies can be. And also how maddening trying to point that out can be. Matthew's is one of the few cases I've heard of where the CoC WG even bothered to reply to email. Sure, they're busy. In which case perhaps they shouldn't butt in so much on trivialities to begin with :wink:.

Note: I believe Judge Dredd, and the CoC WG, couldn't identify "a rule" Guido's post violated because there simply isn't one in the cited

>  Guidelines - Discussions on Python.org as well as here: Python Software Foundation Code of Conduct - Python Software Foundation Policies

The "not a role model" justification comes from a somewhat strained reading of PEP 13, and applies _only_ to core devs (of which, of course, Guido is one). There is no attempt of any kind to explain what "role model" means, and the SC has taken the position that it can do anything it likes to any core dev who isn't acting like a role model, in their sole opinion. No CoC or "community guidelines" violations are needed. This is strictly a "core dev, via PEP 13" thing.

But it's surprising news to me if the mods are tasked with enforcing their own opinions of what the SC's opinions about what "role model" may mean. Leaving aside that, as above, there was no credible explanation given for in what way Guido wasn't acting as a role model. To the contrary, his suggestion was perfectly sensible in context. There was no actual rush to pick a new voting method, as the issue was raised far too late to be implemented for the upcoming SC 2025-term election. He didn't even say he had any objection to my ban.
