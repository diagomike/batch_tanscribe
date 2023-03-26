### a Clone of Whisper with Silero VAD by ANonEntity modified to work on batches of media files from a folder

### Translater has been removed for now [Deepl removed]

### Maybe Use Source Separation In Music Transcription but for [Spleeter removed]

`future`
```shell
!pip install -U yt-dlp

!wget -O - -q  https://github.com/yt-dlp/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-linux64-gpl.tar.xz | xz -qdc| tar -x

!yt-dlp -xv --ffmpeg-location ffmpeg-master-latest-linux64-gpl/bin --audio-format wav  -o lecun.wav -- https://www.youtube.com/watch?v=KzGzgSKrnZw
```
this Code is to be used to dynamically load by title and and link
    to Maintain structure a dummy data with _done_ will be created in its location
