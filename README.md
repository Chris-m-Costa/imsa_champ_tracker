# imsa_champ_tracker
IMSA Championship Tracker

The aim of this project is to build a fully functioning live tracker for championship positions in the IMSA Weathertech Sportscar Series.
The intention is to live update lap by lap through each race (accounting for mid-race points payouts in MEC events) as well as post session updates from official qualifying and race results once event results are finalised (ie once any post race penalties/dsq have been updated in the official results)

The event schedule and full entry list have been webscraped and stored into DataFrames. The full points schedule has been taken from the official regulations and stored as a tuple.

Post-race official results will be pulled in from the results.imsa.com page as they become available (wip)

Live, in-race positions will have to be taken by watching the live timing/scoring streams made available by the series. This aspect of development can not be started until there are live sessions running to test and develop a method to interect with this data stream. Due to my planned in person attendance at the first few rounds, this stage of development will be delayed until mid-season. 


My goal is to have a funtional, accessible, shareable product running before the penultimate round of the season in September, 2024
