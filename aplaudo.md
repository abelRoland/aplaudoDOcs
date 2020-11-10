# Aplaudo Items

## Search Bar

Search bar with items to select/filter like Amazon, [IMDb](https://www.imdb.com/) and so on. Some inspiration / examples can be seen [here](https://codepen.io/scottmbulloch/pen/gpdYdR) and [here](https://bootsnipp.com/snippets/9Avx).

## Search Sessions (filters).

When a user will search on the search bar, it's possible to search the entire dB (default with the label `all`) or, within the categories of the dropdown menu of the search bar (Search sessions on the wireframe).

The categories of the dropbown from the searchBar are: 

- All (default)
- Concerts
- Artists
- Genre
- Style
- Instruments
- Instrumentation
- Country
- Keywords

## Fields for Artist profile update

After the basic fields of the registration form (first name / last name / email / password) the user can complete his/her artist profile with further information. The fields to edit on the profile are:

 - Bio (Artist Bio): Text Area for the artist to write the bio.
 - Username/Artist Name/Nickname: `string` for the artist create a username. FOR FUTURE IMPROVEMENTS: We can make this dB field `UNIQUE` so for the personal 'concert hall' of each user we can just attach the ID of the user on the page (e.g. www.aplaudo.com/concertroom/1234) or, in the case that the user update a username, we can append this username (to be more nice) on the address, like on GitHub (e.g. if my username is abelroland my concert room on Aplaudo would be www.aplaudo.com/concertroom/abelroland). The same goes to profile page and so on.
 - Instrument: Dropdown list of instruments for the artist to choose which instruments he/she plays.
 - Style: Dropdown list of styles for the artist to choose which styles he/she fits in.
 - Country: Dropdown list of countries for the artist to choose the country of origin.
 - Social MediaLinks: On the front-end, it will be like a to-do list, where the user can just push the button `ADD LINK`. When the user pushes this button it opens a table with two fields: "LINKS" and "VALUE". The user can choose which social he/she wants to add to the profile (YouTube / Spotify etc.) and then insert his/her personal profile on this social medias. After push submit the user will see the links that he/she added and can choose to add new links.
 An HTML file with the table is send to explain it in a more clear way. NOTE ON QUALITY: This is not something to focus too much if takes too much time, but it would be good that all the links that are added pass for validation, so YouTube links can just be added if YouTube is choosen and so on.  You can see the HTML example [here](https://github.com/abelRoland/aplaudoDOcs/blob/main/tableLink.html)
 - Creations: Place where the user can put some links for YouTube videos. On the user profile that will be a carousel with the videos that the user upload.
 
 ## Fields for Concert
 
 When creating a concert, the artist can upload the follow information:
 
 - Date: the date of the concert;
 - About: Text about the concert;
 - Style: List of styles of the concert (same list of styles of artists, but for each concert an artist can choose different values of styles;
 - Genre: List of genres of the concert (same list of genres of artists, but for each concert an artist can choose different values of genres;
 - Artist(s): The artist can choose if he/she will make the concert alone or with another musicians. In the case that the artist will make the concert with other musicians and this musicians are also registered on the platform, the user can tag this musician.
 - Instruments: List of instruments of the concert (same list of instruments of artists, but for each concert an artist can choose different values of instruments;
 - Instrumentation: List of instrumentation to choose.
 - Country: A list of countries for the user to choose, in case that the user is playing music from a specific country.
 - Links: YouTube links for teaser / trailers and so on.
 - Picture: A jpg/png picture of the event:
 - Programma: A pdf/jpg file with the programma of the concert, if there is one>
 
 ### Links for the Socials
 
 Altought they are already on the HTML file, we put here the links / values that the user can choose to update his socials on the platform:
- YouTube
- Spotify
- iTunes
- SoundCloud
- LinkedIn
- Website

### Values for the genres
 
### Values for the styles

- African
- Alternative
- Asian
- Avant-garde
- Blues
- Caribbean
- Classical
- Country music
- Easy Listening
- Electronic
- Folk
- Fusion
- Heavy metal
- Hip-hop / Rap
- Inspirational
- Intrumental
- Jazz
- Latin
- Other
- Pop
- R&B and soul
- Reggae
- Rock
- Traditional
- Vocal
- World
 
### Values for the Instruments
- "accordion", 
-	"bass",
-	"bassoon",
-	"banjo",
-	"cello",
-	"clarinet",
-	"classical guitar", 
-	"clavichord", 
-	"double bass",
-	"drums", 
-	"electrical guitar",
-	"electronics", 
-	"english horn",
-	"flute",
-	"flugelhorn",
-	"french horn",
-	"harmonica",
-	"harp",
-	"harpsichord",
-	"keyboard", 
-	"lute",
-	"mandolin",
-	"oboe",
-	"organ",
-	"other",
- "oud",
-	"percussion",
-	"piano", 
-	"piccolo",
-	"recorder",
-	"saxophone",
-	"sitar",
-	"theorbo",
-	"traverso",
-	"trombone",
-	"trumpet",
-	"tuba",
-	"ukulele",
-	"vihuela", 
-	"viola",
-	"viola da gamba",
-	"viola d’amore",
-	"violin", 
-	"voice"


### Values for the Instrumentation

- Solo
- Duo
- Trio
- Quartet
- Quintet
- Chamber Music
- Choir
- Band
- Big Band
- String Quartet
- Combo
- Orchestra
- Other
 
 
