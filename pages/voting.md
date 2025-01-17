import Bleed from 'nextra-theme-docs/bleed'

# Voting

<Bleed>
<div align="center">
  ![Velocimeter Launch](/dome5.jpg)
  </div>
</Bleed>

&nbsp;


## Requirements

Only `FLOW` that is locked as `veFLOW` can be used to vote. To understand more on the mechanics of `veFLOW` refer to the section [Protocol Overview](/protocol)

New epochs start on Thursday as 00:00 UTC. Vote anytime before this. Waiting can allow you to see any bribes that come in, but not waiting ensures you get your vote in on time.


## Restrictions
There are several restrictions that you need to keep in mind when your voting. 

* If you have several `veFLOW` nfts in your wallet, you need to select each one individually
* You can only cast your vote ONCE per epoch, so make sure you allocate 100% of your voting power, and are comfortable with 
your choices before you cast your vote. You cannot change your vote after it is cast in the current epoch

## Rewards
Voting has several benefits that should be considered.

* Voting directs `FLOW` token incentives. So if you care about this, vote accordingly.
* Voting on a pool grants you a pro-rata share of all the trading fees of the pool you voted on. (Only the LPs that are staked to receive `FLOW` rewards)
* Voting on a pool grants you a pro-rata share of all the bribes that are added to the pool by any 3rd party. Bribes can be added
to a pool at any time during an epoch. A snapshot of votes is taken at the end of each epoch at ~23:59 UTC on Wednesday. Bribe rewards are available between 24-48 hours after the new epoch starts. 


 It is REQUIRED that you CAST VOTE 🗳️ every week in order to register for the bribes. This transaction will cost gas⛽️. If you do not cast your vote every week, you will still direct FLOW to the gauge but you will NOT get a prorata share of the bribes.


## Reset to Transfer

If a `veFLOW` holder wishes to transfer, or sell, their NFTs, they need to be aware that they first must reset their NFT which causes them to vote on NO gauges this epoch, thus forfeiting trading fees and any bribes. A recipient of the NFT (buyer from a market) should also be aware that they will not be able to vote until the next epoch. This feature rewards participants that stay consistent in their voting activity.

## Voting APR
In the front end, you will see a column that displays the voting APR. This metric is calculated as follows
&nbsp;

<div align="center">
*voting apr = (tvb / tv) * weeks / flow price * 100%*
  </div>

weeks = 52.179 (approx number of weeks in 1 year) 

tvb = total value of bribes in usd term 

tv = total number of votes 




