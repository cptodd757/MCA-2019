# MCA

This repository is for a class entitled Music Curation and Analytics at the University of Glasgow.

## Week 1

### Task 2

*Identify a theme for your dataset. This will be the central, cohesive strand that will bring your data together. It can be an artist, composer, songwriter, performer, album, larger work (i.e. opera, musical, etc.), time period, genre, archival grouping, etc. You will want to be sure that you can gather all three types of data based on your selected theme.*

For my dataset this semester, I am planning on compiling music that has been used in films and television that I enjoy, original compositions or not.  I have chosen this unifying theme because, while I certainly appreciate music for music’s sake, it is often more enjoyable either to form internalized associations between certain pieces of music and visual media (for example, Simple Minds and the Breakfast Club), or to be pleasantly surprised by favorite musical works appearing in new movies (for example, a performance of Nessun Dorma in a recent installment of Mission Impossible).  I also don’t want to limit myself to a particular genre or time period of music--I don’t know exactly what sorts of analyses we will be doing in later labs, but I want to have the option of working with all types of music, which is freely allowed by a theme such as this.  I may narrow down this theme later on, depending on my interests or any new ideas that come to mind.


### Task 3

*Describe the current manifestations of data relating to your selected theme. Has it already been curated somewhere? How is the data presented, described, and analysed?*

There are definitely pre-made playlists and albums  on Spotify containing metadata and acoustic data for movie hits in general and specific soundtracks/scores.  One example might be Hans Zimmer’s original score for The Dark Knight, available as an album in chronological order on Spotify, with basic information such as artist, duration, release date, etc.  Another example might be a user-made playlist containing the soundtrack used by, but not entirely composed for,  the Netflix original series called Bojack Horseman.  Original film scores may be hard to come by in notated form due to copyright laws, but that’s another reason I’ve left my theme broad enough to include older pieces used in popular films (like a number of classical blockbusters in Fantasia 2000).  These I would obtain from IMSLP, where the data is presented as sheet music in a database searchable by composer, style, era, and other filters, and upon selection of a piece, further organized by instrument and edition.  

Most of this data is not already analyzed; however, I have some experience with Spotify’s excellent Web API that exposes extensive data about tracks within the library of a given user (in this case myself), which I would love to leverage for the purposes of this assignment.  

## Week 2

I have chosen to transcribe and arrange a 16-bar segment from The Light of the Seven by Ramin Djawadi, featured in the Season 6 finale of Game of Thrones.  [Click here for the raw data](./Light_of_the_Seven.mscz)

## Week 3

[Click here to see my transcription presented with Verovio.](https://cptodd757.github.io/MCA-2019/verovio.html)

## Week 4

| Category      | Value           
| ------------- |:-------------:|
| Number of Pitches     | 30 |
| Number of Pitch Classes     | 9      |
| Range | 48    |
| Mean Pitch | 64.89 |
| Most Common Pitch | 67 |
| Relative Prevalence of Top Pitches | .963 |
|Mean Melodic Interval | 9.647 |

These are some of the highlights from the jSymbolic I generated for Light of the Seven.  One thing that is interesting is the difference between the most common pitch (67, which is a G) and the mean pitch (64.89)--the fact that the latter is lower is indicative of the presence of more lower notes, which in this case, are played by the two cellos.  I also notice that the "Relative Prevalence of Top Pitches" has an exceptionally high value (.963), which can be explained by the fact that the left hand on the piano is always arpeggiating a chord, and many of the chords used in this piece predictably include C or G, which comprise the "top pitches" in this piece.  The Mean Melodic Interval also warrants attention because it seems rather high--assuming this is measured in semitones--but it, too, can be explained by the arpeggiation in the left hand, which routinely makes jumps of 7 or 8 semitones.  

Below is a  piano roll for this piece:

![An error occurred.](./Week_4/piano roll.png)

And here, a histogram of the pitches used in the piece:

![An error occurred.](./Week_4/histogram.png)
