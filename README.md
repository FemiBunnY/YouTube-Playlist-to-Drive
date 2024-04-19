# YouTube-Playlist-to-Drive
Download a YouTube playlist and automatically upload it to Drive with Google Colab

## Instructions
1. Copy the playlist link you want to download
2. Paste the link in ```LINK:str = "youtube.com/playlist_link"```
3. Google Colab menu > Runtime > Run all
4. If no error occurs, go to your Drive and search for the compressed file

### Extra options
- By default the videos will be downloaded at max resolution, you can choose a custom res changing the value in ```RESOLUTION:str = "480p"``` **(be sure that the res is available)** and activating ```video.streams.filter(res=RESOLUTION).first().download()```, also deactivate ```video.streams.get_highest_resolution().download(filename=f"{video_title}.mp4")```

### If you found helpful this repository consider leaving a star 🌟 before you go ;)
