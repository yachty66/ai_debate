# ai_debate

## Steps to reproduce 

1. generate debate with claude
2. uncensored workflow?
3. find 30 second audio clip for speaker 1 and 2 
    - download video from yt: yt-dlp -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best" --merge-output-format mp4 https://www.youtube.com/watch?v=6EkKbYxr8x4
    - trimm the video: ffmpeg -i marck.mp4 -ss 00:01:30 -to 00:02:00 -c:v libx264 -c:a aac marck_trimmed.mp4
    - convert trimmed video to mp3: ffmpeg -i yann_trimmed.mp4 -q:a 0 -map a yann_audio.mp3
4. isolate voice with eleven labs https://elevenlabs.io/blog/voice-isolator
5. clone voice of both speakers
6. run script for creating debate audio files for both speakers
7. search image for both speakers
8. run model and create lip sync
9. put it together in capcut
10. post 


- [ ] video of zuck and caesar bringing zuck down on his chain
- [ ] make a nice intro where people laughing loudly at the beginning - yapping.ai or yappers.ai or laugher.ai - yapping.ai is like a wirbelstorm flying into the scene

One indicator for when to switch from human to AI is if the input tokens you need for having the task accomplished are a smaller amount then the amount of input tokens you need for the AI


One indicator for when to switch from human to AI is if the number of input tokens you need to accomplish the task for the human is bigger than the number of input tokens required for the AI


Homo sexuality perse is not anti existential only the refusal of sexuality with the other gender fo the reason of having kids






One indicator for when to switch from human to AI is if the number of input tokens you need to accomplish the task for the human is bigger than the number of input tokens required for the AI