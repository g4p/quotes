# Gavin Andresen: Consensus Changes Should Use a Flag Day, Spin Up Hundreds of Machines, Convince the Vast Majority

First, "potentially forking" changes like that would be structured as:

if (block number < SOME_BLOCK_NUMBER_IN_THE_FUTURE)
  ...old rules
else
  ...new rules

Assuming a super-majority of people agree with the change and upgrade before we get to SOME_BLOCK_NUMBER_IN_THE_FUTURE, the switch will happen smoothly.

Is there a chance of changing?  Sure, but I think anybody who wants to make such a fundamental change would need to do a LOT of testing-- maybe spin up or recruit a few hundred machines all over the world on a test network, have them mine and simulate transactions to each other (ideally with similar volume to the real network) while going through the transition and making sure there weren't any unintended consequences.  And convince a super-majority of people that the benefit of their potentially forking change outweighs the risk of disrupting the network if there's some consequence they didn't think of or that their test network didn't simulate properly.

https://bitcointalk.org/index.php?topic=3441.msg49982#msg49982
