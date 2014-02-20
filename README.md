Matlab-Progress-Bar
===================
Original by Jermy Scheff- jdscheff@gmail.com - http://www.jeremyscheff.com/
Edit by Hyo Byun, while at Mayberg Lab, Emory University, 2013

This script may be used for for and parfor loops in matlab.
To Use:
1. Call progress(N) before entering loop with N as the number of expected iterations.
2. Call progress() at end of loop, inside the loop.
3. Call progress(0) after loop block is over.

Time estimation works best for iterations with lengths that don't increase/decrease.
