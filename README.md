# yt-dmenu
This script uses dmenu's amazing features with youtube data api to launch videos
Please use your own api key :)
You can watch on youtube how to get a api key

# Features
1. Can play all videos from a playlist from demenu's stdout
2. Can play a video from dmenu's stdout

# Requirement
 Please install these dependencies before
 1. jq
 2. dmenu
 3. xargs
 
 # How to use
 Simply run the script 
 1. To sort your search according to date (latest first)
 -> bash player.sh -l "crab rave remix"
 2. To sort your search according to view count (highest viewed first)
 -> bash player.sh -v "crab rave remix"
 3. To sort your search according to relevance (highest related to query will come first)
 -> bash player.sh -r "crab rave remix"
 4. If you find a playlist during your search it will have big video attached to in the list a dmenu prompt will
 ask you for your permission and it will go through all videos in that playlist.
 
 Once again I will provide you my API key, but please you can have your own key and it will be easier for you, what you have
 to just do is all the url's replace the string after "apikey=...&" and before "&" and place your api key
