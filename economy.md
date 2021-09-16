# Issues regarding economy commands.

## buy

- Doesn't respoond if you specify an invalid item ID.
- Formatting of literally every part of this command is horrible.

## shop

- Weekly and daily cars used to reset every 8 hours when the bot restarts.
  - The "fix" for this involved causing it to display negative numbers.
  
  ![image](https://user-images.githubusercontent.com/86816930/133685085-972455a1-101e-44f9-92e7-d8d9e5143033.png)

## daily

- Gives you 15 lacans.  You can literally get more from the hangman command.

## equip

- Doesn't respond if you don't specify any arguments.
- ![image](https://user-images.githubusercontent.com/86816930/133685520-461bebe9-a807-41a7-aee5-cf41c905b95c.png) Doesn't truncate an incorrect index's length, meaning that Nitro users can send ~4k characters and cause the bot to receive a 4xx error.
- Yet to figure out why it's necessary to have a trailing "'" on command responses 🤔.

## gamble

- Doesn't respond if you don't specify an amount.

## give

- Doesn't respond if you give no arguments.
- Almost any error, no matter what, will give a "Unfortunately, you haven't won a guess game yet so you have no lacans to give!" error, even when that isn't what the response should be.
- Adl is still listed as a dev on this command.
- Attempting to give someone 0 lacans will result in "Did you seriously just attempt to get yourself more :lacan_economy_4: by giving your friend 0:lacan_economy_4:`:flushed:?".  This error is completely incorrect.
- ![image](https://user-images.githubusercontent.com/86816930/133686651-4a16470f-b017-4ba4-ae98-a1c5eb1e7c6b.png)
Developers give 0 fucks about the quality of their bot. 

## guess

- ![image](https://user-images.githubusercontent.com/86816930/133687011-dbb8a06a-f4fc-4db6-8ec7-f2071ff3af6a.png)  Because that's definitely 🙄 a car.
- ![image](https://user-images.githubusercontent.com/86816930/133687721-2379f182-b013-43f0-88dc-22448a237204.png) G e t  f l a s h b a n g e d  l o l.
- ![image](https://user-images.githubusercontent.com/71782391/133697446-2c38677a-e156-44b7-bb2a-d948394dc397.png) Incapable of checking or preventing duplicate answers.
- Car names are outdated since they're hardcoded.

## hangman

- No option to type the whole word.
- Often ignores guesses.
- Always attempts to delete the guess, uses a try/except block to handle when it doesn't have manage messages - no proper permission checking.

## noobguess

- Doesn't respond.

## typerace

- Color combination is literal eye bleach.
- Text is often so large that the majority of it is cut off or so small that's it's not easily legible.
-  You can respond with the typed text in a different channel and it will recognize it.
-  Adl, again, has bypasses.



  
