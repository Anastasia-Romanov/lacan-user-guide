# Problems with commands in the "Nitrotype" category.

## cash

- It requires about a trillion arguments in a specific order which is quite easy to forget.  An actual UI (such as slash commands) would greatly improve this command.

## checkbot

- Graph like never updates.

## id

- What the fuck does a clock mean.
- Serves practically no purpose since NT removed the players API so ids are useless for everyone now.

## news

- Breaks without manage messages.
- Literally the worst paginator I've ever seen.

## register

- Let's iterate through every item in the db collection 😳.

## stats

- Allows you to @ an unverified user and it'll show the stats for whatever account they're pending verification of.  
  - Opens up the possibility for people to mistakenly register to the wrong account and well imagine if they won a giveaway and the host used n.stats to check the account. RIP them.
  - Opens up the ability for impersonation.
  - "Just run n.id username to find out whether the account is verified or not." because that is ever-so-user-friendly.  Just fix it for christs sake.

## team

- Breaks on any team without a description.
  - Developer says "Oh smh @GoodGradesBoy just stop critizing ahit" "Ill fix it when Ive got enough time to look into it smh literally Nobody besides sou cares about that But because No one wants to see Teams without descriptiond".  Very interesting to see how the developer has interviewed every Nitro Type player ever to be able to draw that astounding conclusion.  Also quite interesting to see how they have a problem with people criticizing broken things.
  - If I had a dollar for everyone try/except block in that command...

## verify

- Default verification type involves changing titles or trails, both of which users are likely to change frequently as is.  Opens up the possibility for users to become verified to accounts they don't own.
- Friend request verification type often doesn't work.
- Car update verification type is slow as hell (albeit, due to nt's cache).
- After verifying, it requires you to run n.update as a seperate command in order to update your roles in the current server.  Is that necessary lol like ui is a thing.
