# FOREX BTC
A litte experiment with elastic rebase token. 

## WHUT??
The idea behind this is that the price itself matters not as the supply will be rebalanced porportional to the holder count and fragmentation of the token supply in relation to a target rate increase per rebasement period. 

This is to eventually rise the price itself to the pegged price of BTC (Bitcoin) and stay there. The token supply will drop or raise depending on the rebasement each time. 

An extreme but simple example: 
A holder holds 10 tokens of $1 with a total supply of 100 tokens with 50% in circulation.
A rebasing occurs after which the total supply has been cut in half to 50 after which the price is now $2 per token and the holder now has 5 tokens. 
The value remains the same as previous but the relative price of the token has risen. 

## WHY???
This little experiment is to give more weight on the market cap as the price valuation marker as opposed to the absurd pricing points seen in the market. The other reason is because it will discourage buying and selling as rebasing will occur when targets are met pending schedules. 1 time an hour it will check and if a deviation rate is met it will rebase. Holders don't want to sell right before or after as it would screw themselves. There is no way to turn off the feature or reverse it. There is no way to count down to it or call functions external to the contract to know when a rebase may occur based on any parameters available externally.

Also why not? It is an interesting concept to explore for potential arbitrage opportunities when potentially setting up extra liquidity pairs against a elastic rebasing peggy token like this. 

The primary idea that sparked this was to find an semi-automated way to recover a token with too little liquidity to recover on its own. With this pegged to the lp-pair the idea is that you could have vast reserves of this letting it rise up naturally with rebasing then when needed you could sell in tiny quantities against the coin in need putting directly into the liquidity pool. As there could be multiple liquidity pairs on a token you could set up a cyclicle type of system where failing token is sold into this through the lp pair instead of the bnb pair thus not removing any of that liquidity and not hurting any of the primary holders. Then when you have the upswing entry you sell this out into failing token through pancakeswap ensuring that a multihop transfer occurs and the bnb lp pair is hit along the way that way the liquidity for the failing token is accessed and helped via transaction fees and reflections etc.

## NOTE
NOTE: There is a mint and burn function on this token contract. As I mentioned this whole thing is experimental and in the event a rebase occurs that completely F*cks the whole thing I do want a way to recover as I don't anticipate anyone joining this little shindig. And let's be honest here I really don't encourage anyone to join me on this. This is pure experimentation.