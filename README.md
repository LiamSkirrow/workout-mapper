# Workout Mapper

I often split up my runs into multiple smaller distances, for example *3km -> 2 minute walking break -> 2km*, however MapMyRun will instead display this as a 5km run. The goal of this program is to obtain a record of my runs from MapMyRun using the developer API (free tier -> 100k requests/day) and then parse my notes/comments on each run and histogram my workouts from there.

## Notes
- The goal is to have a command based terminal program that outputs my workouts in JSON format ready to be read in the next time the program is run. When running a 'pull' command, the API is accessed and the latest/untracked workouts are fetched and then appended to the JSON file and the stats are updated.
