To to split the file into multiple files with ffmpeg

```powershell
ffmpeg -i input.mp4 -c copy -map 0:v:0 -f segment -segment_time 10 -reset_timestamps 1 output_%03d.mp4
```
