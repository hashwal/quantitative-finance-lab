# Lesson 1 — Simple and logarithmic returns

For positive prices P0 and P1, simple return = P1/P0 - 1; log return = ln(P1/P0). Simple returns compound multiplicatively; log returns add across periods.

## Exercise
A hypothetical stock closes at 100, 110, 99 and 108 on four successive days. Calculate each daily simple return and log return, the cumulative simple return and the sum of log returns. Explain why a 10% gain followed by a 10% loss does not break even.

## Implementation
Write two Python functions accepting positive starting and ending prices. Reject nonpositive inputs. Use math.log for log returns. Write tests for unchanged prices, gains, losses and invalid inputs. Verify that exp(sum of log returns) - 1 equals the compounded simple return within floating-point tolerance.

## Deliverable
Commit your calculations, implementation and tests. Explain the result in your own words before using real market data.
