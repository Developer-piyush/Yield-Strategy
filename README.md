## Leveraged-Yield-Strategy on compound

# Strategy 
=>	We will start investing with 100 DAI into compound protocol, here 100 DAI will act as collateral.<br>
=>	Now we will borrow 75% of the collateral from compound i.e. 75 DAI <br>
=>	Now our strategy is to reinvest the borrowed token (75 DAI) into compound protocol as collateral, we will repeat this process 5 times to maximize our return.

# Note: In our code we have borrowed 70% of the collateral amount instead of 75% in order to prevent any glitch/ or to payout interest or something. 

![1](https://github.com/Developer-piyush/Yield-Strategy/blob/main/assets/1.jpg)
![1](https://github.com/Developer-piyush/Yield-Strategy/blob/main/assets/2.jpg)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# You can see in contract code how we have used openposition, -supplyandborrow, closeposition functions to implement the strategy we have discussed above.
[click here to view contract code](https://github.com/Developer-piyush/Yield-Strategy/blob/main/contracts/YieldFarmer.sol)

