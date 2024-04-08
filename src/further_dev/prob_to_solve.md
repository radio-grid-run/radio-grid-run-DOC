# Problem to solve

## Problems

### What3Words API is proprietary and the concept patented

Using what3words [https://what3words.com](https://what3words.com) as a locator implies to rely on the API of charges money for each API call. You can check for details on the [related comment page](https://wiki.openstreetmap.org/wiki/What3words) of OpenStreet map.

## What3Words lookup cannot be implemented off-grid and without a cell phone

What3Words pricing model implies that groups of player have Internet acces. This has negativ consequences on where you can play as it excludes remote camp grounds, which is a common cases in scout activities.

Expecting the team player to be older enough to operate a cell phone is too restrictiv. As long as one player per team is able to read, every children would be able to make calls with a talkie-walkie.

## What3words is adressing a locator to every single square meter of the world

Adressing the whole world makes the list of words very big and implies to use uncommon words. As this is overkill for a game that is played by foot and last about 2 hours, another appro would be better suited.

## Suggested alternativ approach

- restrincting the described area within a few square kilometers while keeping a relativly coarse resolution (square of 3 by 3 meters)
- using the base coordinate as the (0,0) coordinates for all locations. Dereferencing the relativ coordinates as WGS84 coordinates only as a final step.
s