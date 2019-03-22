## Check list for reviewing pull requests ##

Code reviewing is one of the most effective ways of improving code quality
as its a forum for error spotting, improvements and to discuss decisions.         

Taking criticism is hard, so be kind to your colleagues! pair program with the
author instead of leaving a bad tempered comment (or if that is not possible, at least have a chat)  

#### Message:
  - Why is this commit needed?
  - How does this commit solve the issue?
  - Spell check

#### Commit size:
  - Is the commit a logical unit? More than one concept per commit can be hard to follow.
  - Size matters, but smaller is often better as it makes the reviewing work easier.

#### Checkout code
  - Run the tests. Which parts are covered.
  - Focus on the 'heavy' functions / classes

#### Code smells to look for:
  - Missing tests, boundaries are easy to forget about.
  - Large methods.
  - Large classes.
  - Bad variable / method / class names. Does the name reveal what it is doing.
