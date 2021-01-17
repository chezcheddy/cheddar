This is a clone of a simple Sushiswap-like mechanism for CHDR and on NEAR

## Phase 1 - Early Participants

It's like a token sale, but we only accept NEAR.
We mint 100.000.000 CHDR and sell at x CHDR per NEAR

After Phase 1, we will have x amount of CHDR minted, and x amount of NEAR in the CHDR contract.
The reserve-price of CHDR at this point is CDHR minted/NEAR in the CHDR contract

## Phase 2 - Initial Farming

For a few weeks/months. We allow people to stake CDHR and we provide more CHDR. We can, during that time, stake the NEAR and after
the phase 2, add the rewards to the total NEAR backing the CHDR

## Phase 3 - Liquidity Pool

We open-up the Liq pool with CHDR<->NEAR

People owning CHDR can ADD LIQUDITY by adding CHDR and more NEAR. 
When someone adds liquidity they get CHDRLP. We incentivize people to do that.
Other people can choose to participate now acquiring CHDR by inputing NEAR at swap-price.
Other people can choose leave by getting ner for their CHDR at swap-price.

## Phase 4 - Cheese Farm

People owning CHDRLP, can stake that in the farm and they get: More CHDR and CHDRGOV (the governance token).
The first week the rewards are very high (10x multiplier), and become less and less as weeks passs by.
The rationale is that the people giving liquidity to CHDR get rewards.

## Phase 5 - DAO based on CHDRGOV

DAO voting on what to do with CHDR treasury funds. The treasury gets a cut of each CHDR/NEAR swap

----------------------------------------------------

Notes: 
 * We need to either keep the priv key to update/upgrade the contract, or create a mechanism for the contracts to update themselves upon voting.
 * I'm inclined to do everyting on a big multi-token contract, instead of having a per-token contract. We only keep the farm and the DAO on separated contracts.
 There's a WIP mulit-fungible-token standard here that we can use: https://github.com/near/NEPs/pull/138

