Strategy Overview: RENKO-Based Strategy with Donchian Channel & Awesome Oscillator
Chart Type & Timeframe
Chart Type: Traditional Renko Chart
Time Frame: 1-Minute (for closing checks)
Brick Size Calculation: (Index Value / 1000)
Example:
BN = 50,000 → Brick Size = 50
Nifty = 22,000 → Brick Size = 22
Indicators Used
Donchian Channel
Awesome Oscillator
Rules for Buying & Shorting
Buy Rule
A buy is triggered when:
The Renko closes above the Upper Donchian Channel of the given base symbol + (Half the Brick Size / Buffer)
The Awesome Oscillator is green
Buy Order Placement:
Buy the nearest ATM/ITM Call Option of the indices
Example: If BNF = 47,810 → Buy BNF CE 47,900
Short Rule
A short is triggered when:
The Renko closes below the Lower Donchian Channel + (Half the Brick Size)
The Awesome Oscillator is red
Short Order Placement:
Buy the nearest ATM/ITM Put Option of the indices
Example: If BNF = 47,810 → Buy BNF PE 47,800
Multiple Exit Rules
Partial Exit: Exit half the quantity upon reaching a certain target
Trailing Stop Loss (TSL): Exit the remaining quantity based on TSL
Intraday Exit: If Target / SL / TSL is not triggered, exit by 3:15 PM
Re-Entry Rule
After TSL/SL Hit, re-enter when any brick closes above or below the Donchian Channel as per the above rules.
Configurable Parameters
Renko Brick Size: Adjustable parameter to set Renko brick size
Donchian Channel Periods: Configurable upper & lower periods
Target: Profit target in points
Stop Loss: Place SL, and upon reaching the target, update it to TSL
Trailing Stop Loss (TSL): Dynamic stop loss adjustment
Number of Lots: Adjustable lot size
Start Time: 9:16 AM (Trading start)
Exit Time: 3:15 PM (Exit if conditions are unmet)
