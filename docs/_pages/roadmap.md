---
layout: single
classes: wide
title:  "Steady.Social Development Roadmap"
categories: about updates
excerpt: The plans for upcoming features and improvements to Steady.social, updated as needed.
permalink: /roadmap/
---

These are our current priorities - features will be worked on as time allows, so I can't give specific dates yet, but our current mindset is that they'll release in roughly the following order.

Existing feature releases are discussed on our [updates page][updates] and in [our blog][posts].

Do you have a new idea?  Or do you wish that something would be prioritized higher?  Please contact us at [our feedback site][feedback]!

## Upcoming Work

**High priority bugs.**  Scrolling and the feed on mobile are fragile, and sometimes stutter and need to be fixed.  We also need to show a user's real name when you are responding to friend invites, as it might not be clear who is requesting the friendship by email alone.

**Fixing and simplifying Invites.**  Replacing the current invite link solution for users who aren't already members of the site works, but is unintuitive (in how it results in the invited user requesting *your* friendship) and it also is against the spirit of the website (in that we want to discourage people from inviting strangers).  I want to replace it with a one time code system, where you generate and can share those codes with friends.  For GDPR reasons, we cannot store who the code was meant to go to, but the fact that it is one time use should remove some of the bad outcomes of having a general purpose invite link.

**Allow limited editing and visibility of your current day's post.**  I don't want editing your post to be an anti-pattern where you can come back multiple times a day and merely edit your post, but I would like to provide a brief window after posting where you can edit it.  I also think that you should be able to see your post after you've made it, which will both help to remind you about what you've already posted today and would be a good spot for initiating editing.  This will probably replace the "Make a post" text box in the activity feed once you've made a post already.

**Setting your own refresh time.** Currently your refresh time is based on the last time you visited the site, or the last time you posted.  I would like people to be able to instead set the time that they *want* it to refresh, and have it always refresh at that time.  This way, if you've set aside your 10 minutes a day at a specific time but miss it, you won't find your whole schedule being thrown off in the future.

**Post replies.** Many people have requested the ability to respond to posts in-app.  This would provide more context about what you're replying to, and give people an option to communicate that doesn't involve mostly email, which apparently people hate more than I realized.  In the spirit of the "only come here once a day" nature of this site, however, I feel that this must be addressed carefully.  My current thought is that this will be have more like "pen pals" - not instant messaging where you could spend a significant time chatting back and forth during the day, but rather like a mailbox where you will receive your replies on a daily basis along with your activity feed refresh, and can reply to them but your own reply to their reply will also not be received until the next day.  This keeps the site "slow".  I will retain the ability for people to contact each other through links to external systems, so that in the event where more urgent communication is needed, you still have those options.

**Dark mode.** Some have requested a dark mode, and I'd like that too.

**Making the backend more reliable.**  There are several improvements that I need to make to the backend if this site is to scale to a large number of users.  They are detailed on the [feedback][feedback] site, but need to be addressed as soon as possible.

**Link to your own profile.**  It's not a huge deal, but it'd be nice to have a quick way for users to see their own profile.

**Profile picture customization.** Currently we just grab the profile picture from the platform you used to sign in, but I'd like you to be able to edit it.

**Uploading a single image with your post.** I would like users to be able to associate their post with a single image.  Often it's useful to have a visual of what's going on in your life to go with text.  There are infrastructure changes that I need to make in order to do so however, and legal requirements that I need to fulfill which makes the prospect a bit more of a long term project than I'd like.  I also want to limit it to a single image, both to keep the costs of the site down and to prevent the kind of "misinformation by image spam" that you often see on Facebook.  A picture is worth a thousand words - and a picture filled with disinformation is worth a thousand deceitful words.

**Post "likes"/"reactions".**  At first I didn't like the idea, but I think there is something to be said about people getting feedback about whether others have read their posts.  It helps people to know that their posts aren't just falling into the darkness unread.  In the spirit of the site however, they both should not be seen by anyone but the person who made the reacted-to post, and they should not be seen for your previous day's post until the next day's refresh so that it doesn't become a reason to come back to the site (to "react watch" or dwell on whether people are reacting to your post). 

**Improved new user experience.** Tutorial?  Examples in your activity feed?  I'm not entirely sure yet, but I feel that new users need a way of knowing what to do next when they get to the site.

**Opt-in Daily Email Summaries.** Make it easier to treat the site like a daily newspaper by literally letting people opt into receiving the daily summary of new posts from their friends via email.  Potentially even let them respond via email in order to make a new post, so that if they want to they don't even have to come to the website at all anymore to gain the benefits that it provides.  (which is fine by me, because we're not here to advertise to people or "maximize engagement")

**Donation capabilities.** If the site becomes more popular, I will need a way to continue paying the costs of uptime.  I would like for this to be an honor system of donations, so Patreon seems like a reasonable avenue to explore: though I could look into other options as well, like Stripe.  Either way, I'd love to give people the ability to make reoccurring donations, perhaps in exchange for something like being recognized as a donor in a special credits page.

**Invite by username.** At first I felt that friends would know each other's email addresses, and I have since realized that's not necessarily true.  I could use something more sharable, like a username that people could use to share invite info more easily.  Though perhaps with invite codes this will matter less.

**Friend Contact Reminders.** This feature will allow you to set reminders for how often you want to contact certain friends or groups of friends.  The site will remind you to reach out to them as that time period approaches, and give you the opportunity to mark that you've contacted them - or it will reset the reminder counter automatically if you use the "reply" feature above or contact them through one of the other contact links on the site.  With this feature, Steady.Social becomes essentailly a "friendship management tool" so that you don't suddenly remember that it's been too long since you've contacted a friend!

**Circles and Restricted Posting.** If you have a post that you would prefer only a specific subset of your friends to see, you'll be able to restrict your posts to those friends, and create "circles" of friends as a quick way of selecting those privileged groups when making a post.  

[core-values]: /core-values/
[feedback]: https://github.com/Steady-Social/feedback
[posts]: /posts/
[updates]: /updates/