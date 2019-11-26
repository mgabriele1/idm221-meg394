# FTP, Media, & Audio
## FTP
- File Transfer Protocol
- Gateway from computer to server
    - files from computer to server
    - files from server to computer
- Copies
    - hard drive
    - server
    - github
- Programs
    - Apple
        - Fetch (free with Drexel)
        - Transit
    - Windows/ Apple
        - <b> Cyberduck (free) </b>
        - Filezilla (MALEWARE)
- Once Connected
    - DO NOT DELETE ANYTHING PRESENT
    - Public HTML
        - Website folder
        - Where website files go
        - People can access any information in this folder from a browser
    - Delete
        - WP -
        - index.php
    - Home page should be named <b> index </b>
---
## Media
- Types
    - MPEG
        - video, audio, text, images, synced by time
    - AVI
    - MP3
    - AAC
- "Containers" for getting music to us, different players for these containers
- Plug-ins
    - For some browsers, some media types need a plug-in
    - Plug-ins allow media to play
    - Support without a plug in: browser natively supports media type
- Will be differences in playback between browsers
### Video
- Video Codes: different ways of encoding a video so it can play on the internet without a plug-in
    - H.264
        - MPEG
    - Theora
    - VP8
### Steps to Include Media
1. Browser determines media type
2. Browser decides if it can decode media
    - yes? continue
    - no? error
3. Browser decodes/ displays media
    - most expensive step
4. Decodes and plays audio
5. Interprets metadata
    - extra
---
## Audio
- Types
    - AAC
    - FLAC
    - MP3
    - Vorbis
    - WMA
- Can I use website
    - shows what formats are supported by what browsers
- <b> WILL NEED a few different formats of every media </b>
    - don't use a third party
---
## MIME Types
- Media Type : MIME Type
    - MP3 : audio/ MP3
    - Ogg Vorbis : audio/ ogg
    - WebM : video/ webm
    - Ogg Theoa : video/ ogg
- If media doesn't work, add MIME Type
---
## Encoding Media
- Give one video type --> creates another
- Programs
    - Adobe Media Encoder (ok)
    - Handbreak (great)
    - Miro Coverter (good, free, windows)
        - high res .MOV file
        - drop into comverter
        - click format
            - choose audio, video
            - choose file format
        - click convert
        - now you have a new file
---
## HTML
- Videos
    - src
        - point to file types (one for each)
    - poster
        - call a file
    - preload
        - loads video before played so no buffer
    - autoplay
    - loop
    - muted
    - controls
        - boolean
        - call to include
- Caption Files (508 COMPLIANCE)
    - VTT File
        - Text file
    1. WEBVTT
    2. Timecodes (00:00:00.5 --> 00...)
    3. Captions
    - < track >
    - label, kind, language, src
- Transcript
    - all text into one line in a < p> tag
    - inside < details >
        - creates a clickable dropdown
- Audio
    - controls
        - user cant stop audio
    - preload
    - autoplay
    - loop
    - controls
    - src
- Examples
    - Video
        - < video
            - controls
            - autoplay
            - poster="media/myvideo-poster.jpg">
            - < source src="media/myvideo.mp4" type="video/mp4" />
            - < source src="media/myvideo.webm" type="video/webm" />
            - < source src="media/myvideo.ogv" type="video/ogg" />
        - </ video>
    - Audio
        - < audio controls autoplay>
            -  < source src="media/myaudio.mp3" />
            -  < source src="media/myaudio.ogg" />
        - </ audio>
