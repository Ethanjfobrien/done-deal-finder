# done-deal-finder

A more effecient way to buy things from donedeal.ie

## How it works

* Once the service is started it checks the site every hour for any ads matching the search criteria
* the search criteria are described in a file called search.json
* Every time it does a search it adds any new posts that match the criteria to persistent storage
* All stored posts are measured for how long they stay up in order to gather data about what kinds of posts sell the fastest
* Any stored post can be either temporarily filtered out of the current result displayed or permently removed (added to a blacklist) to exclude from further tracking

## Installation

1. Clone the repo
2. ```yarn install```
3. ```yarn run```
