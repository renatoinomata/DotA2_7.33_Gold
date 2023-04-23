# DotA 2: Patch 7.33
## What has changed in the economy?

DotA 2's newest patch came with an overhaul of long awaited changes. Some of the notable ones include an increased map size (up to 40% from before!), change in Roshan's location and the addition of new objectives. As a result, the game's economy has also been affected.

Some of the changes that impact the gold available on the map were:

- New jungle camps added (12 in total);
- Lane creeps providing less gold as the game progresses;
- The addition of Tormentors include up to two Aghanim's Shards each 10 minutes (starting at the 20 minute mark);

This notebook will provide an overview for how much the game has changed economy-wise. We'll begin by estimating how much gold is available from different sources, namely: GPM (passive gold per minute), Lane creeps, Neutral creeps, Bounty runes and Tormentors.

The information for this project came directly from [DotA 2's Wiki](https://dota2.fandom.com/wiki/Gold), and the [official 7.33 patch notes](https://www.dota2.com/patches/7.33). 

The Python implementation uses mainly `pandas` and `numpy` libraries, and `matplotlib` for plotting graphs.

The full analysis can be seen in the [`dota2_7_33_analysis.ipynb`](https://github.com/renatoinomata/DotA2_7.33_Gold/blob/master/dota2_7_33_analysis.ipynb) file.