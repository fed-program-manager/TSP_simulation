This file contains a simple monte carlo simulation to project Thrift Savings Plan returns from the current day until a retirement month.

Needed inputs:
  - Starting balance - the current balance as of the start of the simulation
  - Monthly contribution - includes TSP deposits and any matching contributions. Do not use per pay period contributions. Instead, annualize the total pay period contrbutions and divide by 12.
  - Retirement month - The month you plan to retire
  - Retirement year - The year you plan to retire
  - Optimistic return - Average annual return in the best case
  - Likely return - Average annual return in the most likely case
  - Pessimistic return - Average annual return in the worst case

The program simulates 10,000 possible scenarios and provides:
   - Mean return
   - Median return (50th percentile)
   - 10th percentile
   - 25th percentile
   - 75th percentile
   - 90th percentile

This can be used for other investment projections but is really geared toward the TSP.
