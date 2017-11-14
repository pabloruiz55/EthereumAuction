# Ethereum Auction
The Dollar Auction made in Ethereum

## How to play

1- Call highestBid() to know what’s the highest bid so far.
2- Call myLatestBid() to know what was your latest bid.
3- Call Bid() while supplying the corresponding eth. (The highest bid plus 0.05 eth, minus whatever you had already sent in your previous bid).
4- Wait for the auction to finish and call withdrawBalance() to get the corresponding eth you are entitled to. Unless yours was the second highest bid, in which case… bummer.
