# Intro
- 1/ https://www.youtube.com/watch?v=g9qTZqGiPH0
- 2/ https://www.youtube.com/watch?v=Ea0JQh54amc
- 3/ https://www.youtube.com/watch?v=7RW3ddZRlEM

### Serve video in .m3u8 format

**Preliminary step** : Serve someone else's online m3u8  
https://github.com/Ruslan-Aliyev/video_streaming/blob/master/m3u8-online.html  
Guided by: https://www.youtube.com/watch?v=eVKm12T0BPg  

**Final result** : Serve your m3u8  
https://github.com/Ruslan-Aliyev/video_streaming/blob/master/m3u8.html  
Download and install FFmpeg: https://ffmpeg.org/download.html  
Convert video into m3u8 using FFmpeg: `gist:[lukebussey/]4d27678c72580aeb660c19a6fb73e9ee#file-ffmpeg-mp4-to-hls-conversion-md`  

### Serve video as BLOB  

**Preliminary step** : Convert video to BLOB upon user upload  
https://github.com/Ruslan-Aliyev/video_streaming/blob/master/video-blob-by-upload.html  
Guided by: https://gist.github.com/edin-m/889fa79a0fa124b1a8c3  

**Final result** : Convert your own video to BLOB then serve it  
https://github.com/Ruslan-Aliyev/video_streaming/blob/master/video-blob.html  
Initially guided by: https://stackoverflow.com/questions/26533691/how-to-create-blob-of-a-video-file/42664008#42664008  
Then guided by: https://stackoverflow.com/questions/60072027/html5-video-source-as-locally-stored-blob-not-working-anymore  
