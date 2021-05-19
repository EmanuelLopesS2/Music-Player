<hr>
<h1>Things to do:</h1>

Show the Environment.UserName
Minimalist style
Easy to use
Buttons to -> Play/Pause, Startover, Previous, Next, Volume control bar, and Progress song bar
Different languages (need to know how to use xaml)
Use a batabase to safe information for me to steal and sell it to facebook and google for 3cents
Show musics filtered by Title, Album, Artist, ...
Show the title, album, artist, rating, ... while the track is playing
A button to search for songs


<h1>Things to do in the database</h1>

<u>A table with basicly everything below</u>

<table name="playHistory"> <!-- or songHistory smt like dat-->
    <tr>
		<th>songID</th>
        <th>songTitle</th>
        <th>songArtist</th>
		<th>songAlbum</th>
		<th>songRate</th>
		<th>songTime</th> <!-- maybe in seconds idk -->
		<th>playedAt</th> <!-- system time when the song was played -->
		<th>songPlayedTimes</th>
	</tr>
</table>
