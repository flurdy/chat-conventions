# Chat conventions

Conventions for organisations use of chat communication tools. E.g. Slack. Suggestions for naming conventions, notifications, type of channels/groups, etc.

## Table of Contents

1. Assumptions
1. Kill the General
1. Random, randomer, randomest
1. Prefix, prefix, prefix channels
1. Robot police
1. Robot gardeners
1. Team public and private channels
1. Contact us convention and pseudo-SLA for responses
1. Threads and replies
1. @all and @here
1. Real profile photo and names
1. Don't hide alerts in channels
1. Status use
1. Notifications
1. Chat convention wiki


## 1. Assumptions

What works for an organisation of 20, 500 and 10,000 is very different. Most of these conventions assumes chat members of over 100. And built on experiences of members size of over 1000.

Most of the conventions are aimed at Slack workspaces. BUt also works with Microsoft Teams, Hipchat, etc. Others like IRC, Discord, etc are slightly similar.

These are conventions and not rules. Suggestions but not never to be adjusted laws.


## 2. Kill the General

In Slack there is a *#general* channel. Once you have enough members of your workspace this channel gets busy and noisy.

With general chat about random news hat really belong in #random. To people chasing their favourite mug, or anyone with a specific bank fob thing. Or selling 2nd hand items, or about social gatherings at a specific office, which is annoying in a company with many locations.

Kill it. It is too ambiguous. For tiny workspaces it is fine otherwise just noise.

Enterprise Slack has had the option to rename this channel. Do it. I would suggest "*#announcements*".

I would also police this channel to only be official company announcements to prevent noise. And hardly even use it for that.


## 3. Random, Randomer, Randomest

A *#random* chat is nice to chat about things that can not be pidgeon holed elsewhere. And as a water-cooler chat for building some bridges.

But if your workspace do not use threads heavily then random becomes very noise and unclear. You might want to add a *#randomer* and *#randomest*, etc. to try to split the conversations. Or insist on using threads...

However in larger workspaces *#random* just does not make sense any more. I would kill it, or just have smaller random in subset channels.


## 4. Prefix, prefix, prefix channels

To help people use and navigate all the channels you need to start prefixing every channel. And police this so that it does not start to slip.

Short prefixes also make sense, 2-4 characters for example.

Basically you are namespacing each type of channel. By location, by project, by business area, by topic.

Subprefixing also helps.


Suggstions:
* "*alt-icehockey*" for discussing ice-hockey.
* "*dep-wonderdog-random*" for the *Wonderdog* department's random chat.
* "*eu-sales-leads*" for collecting sales leads for the European business.
* "*off-lon-engineering*" to indicate a London office specific engineering chat.
* "*proj-rex-profile-public*" for the *Rex* project's profile team's public channel.
* "*syd-tmp-social-xmas-2025*" A short lived channel to discuss an upcoming Christmas party in Sydney.
* "*tool-github-access*" for Github access requests.

If you start to allow unordered root channels like "*#java*", "*#madrid*" or "*#tomstest*" then navigating will start to fail as people cannot see the wood for the trees.

*#dadjokes* and *#catchat* are exempt. They are great and should be mandatory. Though you could put them under an *#alt-* or similar.

### 4.1 Suffix

Conventions for *-public* or *-private* at the end of public or private team channels and similar will also make navigation easier.

Standardising on others such as *-support* for separating support conversations with other teams may be useful.

## 5. Robot Police

As these are conventions people may not be aware of them and regularly violate them. Or aware but ignore them. Or come across a situation where the conventions needs to evolve.

You could rely on only other members policing each other but often people will be reluctant to step on others toes. Also if some put on their police hat to remind people of the conventions people may react negatively to those people.

Some manual intervention and education will always be needed but a lot of this friction can be remedied by automated bots to police the workspace.

You can have the built in *@slackbot* inform new members of the conventions as part of the onboarding.

You could write or find bots that post the first post in every new channel created to remind people of the conventions. People can then quickly rename the channel to comply if they were lazy with the channel naming.

You could write some bot tool that people can snitch to if they see people ignoring the conventions. Trickly moral balance but could be helpful.

A gentle reminder from a non-person is sometimes not as offensive as being told off by a colleague. Especially if not a public message but perhaps a direct message. Most violations are simple mistakes than can quickly be corrected.


## 6. Robot Gardeners

On top of policing there are useful bots that keep the workspace clean.

There is a gardener tool that checks if channels have not had any new posts for a long time, and can warn then archive that channels. Removes old and stale channels.

You could have bots that monitor language use with gentle reminders of swearing, or use of bigoted terms. Be aware of shaming people publicly with these, that would often be counter-productive.


## 7. Team public and private channels

It is very helpful for teams and departments to have public and private channels. A public one can be were they announce new features, engage with stake-holders, report any outages, and as a channel for contact the team.

Private channels are for all chat and notifications. And more frank discussions. This avoids noisy chats for people external to the team.


## 8. Contact us convention and pseudo-SLA for responses

Different companies and teams have preferred channels for others to reach them.
Maybe there are scrum masters that act as a gatekeeper,
or project managers than handle all communication.

Or an insistence that all communication is via a Jira ticket or similar.

But some accept or even prefer that all communication is via a public Slack channel.

You may in the channel's topic have a link to a wiki page describing the contact preferences. And hopefully state possible response times, a pseudo-SLA for acknowledging messages and full responses.

That way external people know when they might get a response instead of starting to chase via other mediums. And keeps the team aware of people contacting them.


## 9. Threads and replies

For smaller Slack workspaces and non busy channels replying and adding to conversation directly in the channel is fine. It is clear and easy to read.

However once the workspace and especially specific channels starts to have a lot of members then a convention of insisting on all replies be in threads makes a lot of sense.

Otherwise the channel will just be a car crash of messages and hard to follow who is replying to what.


## 10. @all and @here

Ban them all. They are soap boxes for people to shout about things that is only relevant to a few people, and mostly irrelevant for everyone else. Especially in large channels. Just pure noise.

But also in e.g. not that large team public channels. Someone shouting with an *@here* about something they are having a minor problem with related to that team will also disturb all eternal passive members that have little interest with that person's problems. Just noise for most.

Sure, if a message is ignored beyond the pseudo-SLA, shame the team to respond, but otherwise don't be a dick.

An alternative is way to have a quota for each time you *@here*. Multiplied by how many in the channel. If you exceed your quota you have to buy cupcakes for everyone in that channel?

There might even be bots that replies in threads to an *@here* poster to remind them how rude they may be.


## 11. Real profile photo and names

If your workspace members reach a larger number that everyone wont know each other then you should insist on people putting real profile photos of themselves. Recent, cropped, focussed and easily identified as them.

Perhaps use the Id card photos if you have that. They are usually very suitable.

Also make sure real names not nicknames are used.

"Tom the Man" with a profile photo of his football team crest may be what he identify as him. But for someone that does not know it they are useless, and very unprofessional.

Having a photo of a Simpson character, or your children is also useless. This is not facebook. Slack are for most people also a people directory to find people in the company that the don't know.

Perhaps a colleague wonder if this is the *Andy* they just talked to in the lift and need to ask them a follow up question about the problem they discussed. But there are 4 *Andys* in that department and their profile photos are not helpful...


## 12. Don't hide alerts in forgotten channels

Slack has over time become an intersection of integration with other services. Mostly for  notification of events. And they can be very useful.

Notifications such as
* Pull Requests submitted in Github repositories.
* Build fail in a Continuous Integration service.
* Production deploys.
* New stories in Jira, or status changes.
* Monitoring alerts for production services.

Many teams would create specific channels for these alerts to go into as they believe it would be too much noise to go into their normal chat channels. E.g. a *#proj-rex-profile-jira* channel.

But for most that is where these messages go to die. Most people mute these channels so mostly ignored. So they have no value.

Instead I suggest PRs, "build fails" and similar go into the normal team chat, perhaps their *-private* channel. That way they are not ignored and action quickly. Don't fix the problem of many "build fails" by hiding the alert, fix the actual problem instead.

For critical monitoring alerts I suggest they go into the *-public* channel. That way they are responsed to straight away as it reflects badly on the team. Also external people that might go to the channel to ask why their integration with that team is having issues, they will see straight away there is a serious problem that seems to be the root problem.

Again if there are too many alerts in the *public* channel, fix the root service problem, and perhaps adjust the alerting if needed. But don't remove it from the *-public* channel.



## 13. Status use

Most people do not use the status for your user. But it can be useful for some uses. Such as stating that you are offline due to lunch.


## 14. Notifications

Part of the onboarding should be to teach people to tweak their notifications.

Perhaps with suggestions such as:

* Mute most larger channels.
* Set notifications to be totally off for weekends and weekday non office hours.
* And for hardly any notifications for your mobile.


## 15. Chat convention wiki

All these conventions should probably be available on a wiki. With details for how to evolve them.
