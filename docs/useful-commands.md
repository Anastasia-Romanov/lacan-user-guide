## This document contains a list of issues with the current version that affect "useful" commands.


"help" command
 - Paginating to the first page correctly disables the back button, however using the home button (which takes you to the first page) doesn't.
    - This is likely due to code duplication or poor state management.  Code should be de-duplicated and state handling should be fixed.
 - Using the select menu to view a specific category disables pagination between other pages.
    - This feels inconsistent and should be changed to provide a better user experience.
 - There appears to be a time limit for inactivity.
    - There is nothing in the command that is preventing it from being made stateless.
        - Running a new help command several hours later will re-activate the earlier messages, implying that there is no *need* for it to be tied to a specific message.
