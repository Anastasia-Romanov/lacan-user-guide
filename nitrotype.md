# Problems with commands in the "Nitrotype" category.

## ~~cash (removed)~~

- It requires about a trillion arguments in a specific order which is quite easy to forget.  An actual UI (such as slash commands) would greatly improve this command.
- Using an accuracy below 0 or greater than 100 results in an inaccurate error statement to use "whole, rounded numbers" even with 101, 102, etc.
- A decimal amount of friends is interpreted as you having none.
- Apparently `n.cash 0 0 0 0 False piss` doesn't get an error smh my head.
- An actual UI (such as slash commands) has options to only allow integers or booleans.

## ~~checkbot (removed)~~

- Graph like never updates.

## id

- What the fuck does a clock mean.
- Serves practically no purpose since NT removed the players API so ids are useless for everyone now.

## news

- Breaks without manage messages.
- Literally the worst paginator I've ever seen, you can see more detailed information about the paginator [here](/paginator.md).
- Incapable of loading images apparently.
- Is removed due to it being broken and not responding rather than being fixed.

## register

- Input: Why require the user to type `n.verify` when you can provide instructions here.

## stats

- Allows you to @ an unverified user and it'll show the stats for whatever account they're pending verification of.  
  - Opens up the possibility for people to mistakenly register to the wrong account and well imagine if they won a giveaway and the host used n.stats to check the account. RIP them.
  - Opens up the ability for impersonation.
  - "Just run n.id username to find out whether the account is verified or not." - glory says, because that is ever-so-user-friendly.  Just fix it for christs sake.
- Discord supports timestamps which provide a much better interface but Lacan still uses plaintext for the users account creation.


## team

- Completely broken, responds with "Couldn't find that team" for valid teams.
  - Developer says
     > "Oh smh @GoodGradesBoy just stop critizing ahit"

     > "Ill fix it when Ive got enough time to look into it smh literally Nobody besides sou cares about that But because No one wants to see Teams without descriptiond".

    Very interesting to see how the developer has interviewed every Nitro Type player ever to be able to draw that astounding conclusion.  Also quite interesting to see how they have a problem with people criticizing broken things.
  - If I had a dollar for everyone try/except block in that command...

## verify

- Input: After verifying, it requires you to run n.update as a seperate command in order to update your roles in the current server.  Is that necessary lol like ui is a thing.
- Displays a 500 word **essay** that discourages the user from reading the command response and ultimately gets frustrated.
