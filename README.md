# Backpacker

API documentation in API.md

## Summary

Player is given objects of varying sizes to pack within a grid that represents the player's backpack which cannot be moved after placed. Score is based on how many of the squares are filled. Once the player cannot fill up backpack anymore, a ship button is pressed to tally up points for that backpack and a fresh grid is spawned. The ship button sends the current score to the database, which adds it to the player's total lifetime score. The leaderboard is made up of the top 10 highest scorers.

- Game page
- Sign up page
- Backend for scores
