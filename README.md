# Scraping "Adventure Time" Transcripts

Code along on scraping the transcripts for the show "Adventure Time" from the
fan-made site https://adventuretime.fandom.com/wiki/Category_talk%3ATranscripts


## Second day 2019-08-02

Recording: [https://youtu.be/5GDP9ElGt7c](https://youtu.be/5GDP9ElGt7c)

We continued to in formalizing our process to scraping one episode so it will be
easier to apply this to scrape all episode transcripts.

- Creating a function all is needed to scrape is simply passing the transcript URL
- Preparing data to be stored 
- Next time:
  + Use RegEx to find and save action descriptions
  + Create a (tidy) database of episode transcript information


## First day 2019-07-26

Testing out how to scrape the first episode's transcript and loading it into a
data frame.

Recording: [https://youtu.be/137SOCvr4vg](https://www.youtube.com/watch?v=137SOCvr4vg&list=PLVoXE6pv5LIgE4NEXtH3qmz0gMFowUgcS&index=5)

- Made soup from first episode's transcript page: (Slumber Party Panic)[https://adventuretime.fandom.com/wiki/Slumber_Party_Panic/Transcript]
- Identified the "speaker" (extra narrative info or character)
- Removed extra white space
- Saved into a DataFrame
