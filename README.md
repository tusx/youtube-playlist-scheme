# youtube-playlist-scheme
This Repo Will Explain how Playlist scheme works on YouTube. Im no Expert, this is just an observation of mine.

# Popular Video Scheme
Then Url scheme should look like this.

https://www.youtube.com/watch?v=uy5pWDFq0vI&list=UULPCvVpbYRgYjMN7mG7qQN0Pg

where v=video_id sould be the most popular video.

list=list_code contains two diffrent parameters UULP and the rest. P in UULP indicates the Popular video. the rest code is the channel ID.

In this case UULP is Popular Videos and CvVpbYRgYjMN7mG7qQN0Pg is the channel id

# Recent / Latest Video Scheme
Compared to Popular Video Scheme we only need to change two things. 
1. Video ID
2. From UULP to UULF
   
Video ID should be the latest Video id.

Changing these two will Give you a playlist containing all Videos of given channel ID

# What if i dont know which video id to use?
In this Case use any video id from that channel. using random Video id will start the playlist from that video.

for example In Recent Video Playlist, If Video Id was the second most recent video the playlist will start from number 2.

In short Playlist conatining random Video ID will Start from the video relitive position in the given playlist.

Example: https://www.youtube.com/watch?v=jUnckT__yHI&list=UULFCvVpbYRgYjMN7mG7qQN0Pg depending upon when you will visit this link and the recent videos on the channel you will find the video number to chnage.

# How to Find channel ID?
On Desktop go to the channel and then click on the channel discription.

Scroll down until you see the option for share channel.

Click on it and select copy channel ID. You will get something like this UCCvVpbYRgYjMN7mG7qQN0Pg

Just Remove the UC from the beginning and you have the channel ID which you can use in Playlist.

