# Spotify Streaming Analysis Report
## 🎶 __Decoding Your Listening Habits: A Spotify Streaming Deep Dive__ 🎧

User's Spotify streaming history tells a unique story—one filled with favorite tracks, repeat listens, and the rhythms that define User's soundtrack. This report takes a data-driven approach to analyzing User's listening trends, uncovering the most played songs, top artists, and total streaming duration that shape User's musical journey. From repeat-worthy hits to deep-dive listening sessions, this analysis reveals the patterns behind User's streaming behavior. Whether it’s the most streamed track, the songs User's can’t stop replaying, or the ultimate earworm that keeps User's hooked, this deep dive into User's Spotify data highlights the music that truly moves User's. 🚀🎵


## Report Overview
This report presents an analysis of Spotify streaming data, focusing on key performance indicators such as total streams, streaming duration, and the number of artists, albums, and tracks streamed. The analysis highlights year-over-year trends, platform usage, and top-performing artists and tracks.

### __Data Source__ 
__Dataset:__ Maven Data Challenge  
Get the dataset here 👇👇👇👇👇👇  
https://maven-datasets.s3.us-east-1.amazonaws.com/Spotify+Streaming+History/Spotify+Streaming+History.zip

### __Report Dashboard__   
Interact with the PowerBI Dashboard  
👇👇👇👇👇👇👇👇👇👇👇👇👇👇  
https://app.powerbi.com/view?r=eyJrIjoiMGUyZjIyODAtMWFjNi00MjhlLWJmMTEtM2VlM2I1NTk2NzNmIiwidCI6IjgyMjU5N2NkLTQ1ZTYtNDEzMS1hM2JkLTNiNWUwZTFhNzI0MyJ9

## Key Performance Indicators
•	Total Streams: 150K (YoY increase of 7.05%)

•	Streaming Duration (Minutes): 320K (YoY increase of 9.93%)

•	Number of Artists: 4,112 (YoY increase of 7.14%)

•	Number of Albums: 7,907 (YoY increase of 6.56%)

•	Number of Tracks: 14K (YoY increase of 5.94%)

## Streaming Trends
•	Streaming Duration Over Time: The line chart illustrates streaming duration trends from 2013 to 2024, showing steady growth with peaks in 2020 (55K+ minutes) and a slight decline in recent years.

•	YoY Percentage Change: Significant growth observed in 2015 (860.29%) and 2016 (738.49%), followed by fluctuations and a more stable trend in recent years.

## __Platform Usage__
•	Android: Dominates with 291.48K minutes streamed.

•	Other Platforms: Include cast devices (12.12K), iOS (8.38K), mac (4.20K), Windows (3.90K), and web player (0.42K).

•	Shuffle and Skip Rates: 74.46% of streams were shuffled, while 5.25% were skipped.

## __Top most Stream Artists, Albums & Tracks base on Streaming Duration(Minutes)__
#### __•	Top 5 Artists with most Streaming Duration(Minutes):__
1.	The Beatles: 20.2K minutes
2.	The Killers: 17.7K minutes
3.	John Mayer: 12.1K minutes
4.	Bob Dylan: 9.5K minutes
5.	Paul McCartney: 6.0K minutes
#### __•	Top 5 Albums with most Streaming Duration(Minutes):__
1.	The New Abnormal: 3.1K+ minutes
2.	The Beatles: 3.1K+ minutes
3.	Imploding The Mirage: 2.6K+ minutes
4.	Abbey Road: 2.4K+ minutes
5.	Blood On The Track: 2.4K+ minutes
#### __•	Top 5 Tracks with most Streaming Duration(Minutes):__
1.	Ode To The Mets: 1,123.86 minutes
2.	The Return of The King (feat. Sir Jame Galway, Viggo Mortensen & Renee Fleming): 1,073.36 minutes
3.	The Fellowership Reunited (feat. Sir Jame Galway, Viggo Mortensen & Renee Fleming): 746.95 minutes
4.	19 Dias y 500 Noches - En Directo: 715.23 minutes
5.	In The Blood: 640.45 minutes

## __•	Highest Streaming Duration(Minutes) base on Reason the Streaming was Start (Reason_Start) & Reason it was End (Reason_End):__
#### __Top 5 Highest Streaning Duration(Minutes) by (Reason_Start)__
1.	trackdone: 246.8K minutes
2.	fwdbtn: 37.3K minutes
3.	clickrow: 23.6K minutes
4.	appload: 5.3K minutes
5.	backbtn: 3.7K minutes
#### __Top 5 Highest Streaning Duration(Minutes) by (Reason_End)__
1.	trackdone: 281.4K minutes
2.	fwdbtn: 17.2K minutes
3.	endplay: 9.3K minutes
4.	logout: 8.3K minutes
5.	unexpected-exist-while-paused: 3.0K minutes


## __Detailed Artist Performance__
 **•	Top Artists  :**   **Johnny Cash,** **The Killers,** & **The Rolling Stones** lead in terms of the number of Albums streamed.    

**• The Beatles,** **Paul McCartney** & **The Killers** had the most streams interms of number of Tracks streamed.

**•	Total Listening Time(Streaming Durations)   :**  **The Beatles**  have the highest (Streaming Duration) Total Listening Time (20,169.74 minutes), followed by **The Killers** (17,659.28 minutes) & **John Mayer** (12,086.99 minutes).

# __Favorite User's Track Details__
•	User's Favorite Track_Name: __"Ode To The Mets"__ by 

•	User's Favorite Artist_Name: __"The Strokes"__

•	User's Favorite Album_Name: __"The New Abnormal"__

•	User's Favorite Platform: __"Android"__

•	User's Favorite Track Shuffle Rate: __"55.1%"__

•	User's Favorite Track Skipped Rate: __"0.5%"__



### __User's Favorite Track Analysis Report__ 
Determining a user's favorite track requires a balanced approach that accounts for different dimensions of engagement, loyalty, and reach. This report explains the methodology __I__ used to calculate the Favorite Track metric, how each factor was weighted, and why these metrics were chosen as the best indicators of song popularity.

#### __Key Metrics Used in the Analysis__

To determine the user's favorite track, three key streaming metrics were considered:

##### __1. Total Streaming (Listening) Duration (50% Weight)__

__What It Shows:__ Measures the total duration a user has spent listening to a particular track.

__Why It’s Important:__ Tracks with longer listening durations indicate higher engagement, meaning users enjoy listening to them for extended periods rather than skipping or stopping early.

__Weight Justification:__ Since deep engagement reflects true preference, this metric was given the highest weight (50%) in the ranking.

##### __2. Total Streams (Play Frequency) (30% Weight)__

__What It Shows:__ Represents the number of times a track has been played by the user.

__Why It’s Important:__ High play frequency suggests strong loyalty and replay value—tracks that the user keeps coming back to.

__Weight Justification:__ Since repeating a track multiple times indicates a preference, but doesn’t necessarily mean the user listens all the way through, this metric was assigned a moderate weight of 30%.

##### __3. Qualified Streams (10% Weight)__

__What It Shows:__ Measures the number of times a song has been played for at least 30 seconds (industry-standard for a valid stream).

__Why It’s Important:__ Tracks with a high number of qualified streams indicate general popularity.

__Weight Justification:__ While this metric is useful, it does not directly indicate preference as much as the other two. Some tracks may be played frequently but skipped early, so it was given the lowest weight of 10%.

### __Key Takeaway & Insight__ 

##### __Total Stream Count:__

Qualified Streams: 94K  
Total Streams: 150K  
**Insight:**  Only about 63% of total streams are considered "qualified," meaning a significant portion of streams were either skipped or did not meet the criteria for qualification.
Streaming Duration (Minutes):

Qualified Streams Duration: 317K minutes
Total Streams Duration: 320K minutes  
`Insight:` Despite the lower count of qualified streams duration, their duration is nearly the same as total streams duration, indicating that non-qualified streams are much shorter.
Shuffled & Skipped Streams:

Qualified Streams: 67.62% of the Qualified Stream were shuffled, and 1.94% were skipped.
Total Streams: 74.46% of the Total Stream were shuffled, and 5.25% were skipped.  
`__Insight:__` Qualified streams have fewer skips than total streams, suggesting that users are more engaged with these tracks.

__Platform Breakdown:__

Android is the dominant platform across all Platform, with over 287K minutes in Qualified streams and 291K minutes in Total streams.
Other Platforms (iOS, macOS, Windows, web player) contribute relatively little to overall streaming duration.
`Insight:` Android users account for the vast majority of streaming duration (listening time), making it a key focus platform.


__Final Insights:__  
Qualified streams tend to have longer play durations and lower skip rates, suggesting stronger user engagement.  
Shuffled play is high, meaning users often rely on algorithmic or playlist-driven listening.  
Android is the dominant platform for streaming, making it a crucial area for further analysis.

## __Conclusion__
The analysis reveals a growing trend in Spotify streaming, with Android being the most popular platform. The Beatles and "trackdone" stand out as the most streamed artist and track, respectively. The high shuffle rate indicates a preference for varied listening experiences, while the low skip rate suggests overall user satisfaction.

