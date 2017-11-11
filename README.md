## Problem:

In energy production, the power grid is a a large directed graph of energy consumers and producers. At times you need to cut at certain nodes and trim demand because you cannot supply enough of a load.

In DailyProgrammeropolis, all buildings are connected to the grid and all consume power to varying degrees. Some generate power because they have installed on-site generation and sell the excess to the grid, some do not.

The scenario you're facing is this: due to a fault with the bulk power generation facility not local to DailyProgrammerololis, you must trim the power grid. You have connectivity data, and power consumption and production data. Your goal with this challenge is to maximize the number of powered nodes with the generated energy you have. Note that when you cut off a node, you run the risk the downstream ones will loose power, too, if they are no longer connected. This is how you'll shed demand, by selectively cutting the graph. You can make as many cuts as you want (there is no restriction on this).
