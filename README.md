Python script for inputing a movie's tmdb page number and a video file that outputs bbcode generated for an info page.
Simply double-click the script to run, and follow the prompts. The bbcode output is dumped to a txt file in the same folder as the script, using the name of the movie.

**Important to edit this section of the script with your own info.**

    api_key = "YOUR_TMDB_API_KEY"  # Replace "YOUR_TMDB_API_KEY" with your actual TMDB API key
    
    imgur_client_id = "YOUR_IMGUR_CLIENT_ID"  # Replace "YOUR_IMGUR_CLIENT_ID" with your actual Imgur client ID
    
    imgur_client_secret = "YOUR_IMGUR_CLIENT_SECRET"  # Replace "YOUR_IMGUR_CLIENT_SECRET" with your actual Imgur client secret"_

This requires mediainfo.exe, the CLI version, to run which can be grabbed separetly here:
https://mediaarea.net/en/MediaInfo/Download/Windows
Put the .exe in the same folder as the script, along with template_mediainfo.txt before running the script

template_mediainfo.txt is used for formatting the output and can be adjusted to your liking.

**Sample Output:**:
https://i.imgur.com/t2Ubf2P.jpeg
