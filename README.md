# youtube-playlist-scheme
This repo will explain how the playlist scheme works on YouTube. I'm not an expert on this, it's just an observation of mine.

# Popular Video Scheme
The URL scheme should look like this:

https://www.youtube.com/watch?v=uy5pWDFq0vI&list=UULPCvVpbYRgYjMN7mG7qQN0Pg

where v=video_id should be the most popular video.

list=list_code contains two different parameters. UULP and the rest. The P in UULP indicates the popular video. The rest of the code is the channel ID.

In this case, UULP is Popular Videos, and CvVpbYRgYjMN7mG7qQN0Pg is the channel ID.

# Recent / Latest Video Scheme
Compared to the popular video scheme, we only need to change two things.
1. Video ID
2. From UULP to UULF
   
The video ID should be the latest video ID.

Changing these two will give you a playlist containing all videos with the given channel ID.

# What if I don't know which video ID to use?
In this case, use any video ID from that channel. Using a random video ID will start the playlist form that video location.

For example, in the Recent Video Playlist, if Video ID was the second most recent video, the playlist will start from number 2.

In short, a playlist containing a random video ID will start from the video's relative position in the given playlist.

Example: https://www.youtube.com/watch?v=jUnckT__yHI&list=UULFCvVpbYRgYjMN7mG7qQN0Pg Depending on when you visit this link and the recent videos on the channel, you will find the video number to change.

# How do I find the channel ID?
On desktop, go to the channel and then click on the channel description.

Scroll down until you see the option for share channel.

Click on it and select copy channel ID. You will get something like this. UCCvVpbYRgYjMN7mG7qQN0Pg

Just remove the UC from the beginning, and you have the channel ID, which you can use in the Playlist.
