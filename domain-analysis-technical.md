# Domain analysis: technical

    State of the art, competition

- [ ] interviewing domain ‘experts’
- [x] existing relevant documentation
- [x] procedure manuals, job descriptions and forms


## The field

I picked the field of **music streaming and sharing**. Here various ideas and business models can be found. Over the curse of the recent years several variations have come to the forefront. I will explore a few of them and try to capture the variety within my selection.

According to Wikipedia users pick their music service according to:<sup>[1][1]</sup>

> [...] the type or purpose of the streaming service, whether there are free options available, the presence of advertisements or lack thereof, the platforms or applications that support each service, what the cost of subscription is, and the size of the music library offered.

This provides me with a first conceptual frame to look at the field.


### Contenders

These are the services that seem to be the relevant contenders to the field:

- [x] [Amazon Music](#amazon-music)
- [ ] Google Music
- [ ] iTunes
- [ ] Lastfm.com
- [ ] MTV Television
- [x] [Plex](#plex)
- [x] [Soundcloud](#soundcloud)
- [x] [Spotify](#spotify)
- [x] [Tribler](#tribler)
- [ ] Youtube

From this plain list I will pick a few (marked) and go into the details of their offering.


### "Spotify"

- Desktop and smartphone streaming
- ~ 75 million users in 2015<sup>[1][1]</sup>
- ~ 20 million songs<sup>[1][1]</sup>
- Users can create/share playlists and songs
  - Federates friends via Twitter/Facebook
- Integrate with Last.fm for scrobbling and music recommendations
- **"Radio"**: Generates playlists based on artists, genres and decades
- Closed source software with DRM
- Music gets cached locally
- **Free account** available
  - Radio service free
  - Caching happens but will not be used on network interruptions
  - Adverts are played more or less regularly
  - Limited amount of skips per time
  - Limited playbacks of user chosen tracks per time
- Accused of not compensatining artists fairly/transparently
- **Lack of privacy**: Users expose the way they listen to music to Spotify
- Third-party playes can be used under a premium subscription


#### Business model `freemium`

*My understanding of their business model:*

> **Consumer side:** We offer music streaming for your desktop and mobile device. We provide a music overview for you and offer you a easy to use radio-like listening functionality. We offer our basic service for free but if you want a advert free and completely flexible experience you need to pay.

> **Creator side:** You can distribute your music and receive a share of the profit depending on how much your music gets played.

Monetization happens on the consumers side.


### "SoundCloud"

- Desktop and smartphone streaming
- ~175 million users in 2014<sup>[2][2]</sup>
- ~12 hours of music are uploaded every minute in 2014 <sup>[2][2]</sup>
- Content creators are allowed to upload
- Sound files can be **embedded everywhere**
- Listeners can form groups to organize music
- Music is depicted as waveforms and users can post **"timed comments"** on specific
  parts of the track
- Payed accounts allow for more music to be uploaded
- Was used once to leak a recorded phonecall of a turkish prime minister


#### Business model `distributor`

*My understanding of their business model:*

> **Consumer side:** We offer music streaming for your desktop and mobile device. We allow you to form and join groups to organize music content and get a better overview. We offer you a way to comment on individual sections of the sound files.

> **Creator side:** We offer you a way to host and distribute music. We offer free basic functionality but require payments if you want to upload more music or receive better usage statistics.

Monetization happens on the creators side.


### "Amazon Music"

- **~29.1 million songs** in 2015<sup>[3][3]</sup>
- Desktop and smartphone streaming
- Users can **upload their own music**
- Music previews snippets are available
- **Music needs to be purchased** or uploaded before it can be listened to fully
- **Devices need to be activated** in order for the web player to work. 10 devices can be activated.
- Recommends music


#### Business model `distributor`

*My understanding of their business model:*

> **Consumer side:** We allow you to preview and buy music online. We help you discover new music you like. You can then download it or listen to it using our web player after you have purchased it from us. You can also upload your own music to have one place to manage all your music. 

> **Creator side:** You can offer your music for purchase on our website.

Monetization happens on the consumers side.


### "Tribler"

- **Torrent network**
- Collaborative/shared downloading<sup>[4][4]</sup>
- Desktop streaming
- **Distribured search**<sup>[10][10]</sup>
- Tries to generically **recommend download candidates** based on downloading history<sup>[9][9]</sup>
- Users can group to spread or faster download content<sup>[8][8]</sup>
- Strives to be a **zero-server p2p network**<sup>[5][5]</sup>

#### Business model `non-profit`

*My understanding of their business model:*

> **Consumer side:** We provide you a censorship free distributed index of files. You can download or stream the files. You can form groups to help spread or faster download content.

> **Creator side:** You can use the upload capacity of your machines to increase the download/streaming speeds for your content. You can start groups to ease finding and downloading your content.

Montization happens through grants. This is a scientific project.

### Plex

- Desktop and smartphone streaming
- **"10-foot user interface"**<sup>[5][5]</sup>
- Uses the users **own music/movies/pictures**
- Server-client streaming infrastructure
- **Identifies music and movies**<sup>[6][6]</sup>
- **Automatically acquires thumbnails and synopsis**<sup>[6][6]</sup>
- **Transcodes** to accomodate mobile clients<sup>[7][7]</sup>
- Music is **automatically grouped** by categories such as "mood"<sup>[6][6]</sup>
- Can acquire content from iTunes, iPhoto, Aperture<sup>[5][5]</sup>
- Some of those features need to be unlocked by a subscription

#### Business model `freemium`

*My understanding of their business model:*

> **Consumer side:** We provide you with an easy way to consume your own media may it be photos, music or videos. You host your own infrastructure and we provide you the software. You can conveniently stream via your mobile device. We preprocess your files and add thumbnails and synopsis. We also order in a meaningfull way so you music so you can play it easily. Some of these features and faster access to new ones are bound to a recurring fee.

> **Creator side:** No offering.

Monetization happens on the consumers side.

[1]: https://en.wikipedia.org/w/index.php?title=Spotify&oldid=687804596
[2]: https://en.wikipedia.org/w/index.php?title=SoundCloud&oldid=688027513
[3]: https://en.wikipedia.org/w/index.php?title=Amazon_Music&oldid=676049603
[4]: https://tribler.org/CooperativeDownload/
[5]: http://tribler.org/4thGenerationP2P/
[6]: https://plex.tv/music
[7]: https://plex.tv/subscription/about
[8]: https://www.tribler.org/CooperativeDownload/
[9]: https://www.tribler.org/DecentralizedRecommendation/
[10]: https://www.tribler.org/ContentSearch/
