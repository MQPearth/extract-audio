## extract-audio

Extract audio from a specified segment of a video and export it.

> 从视频的指定片段中提取声音并导出

### run

```shell
./extract-audio -v /home/audio/test.mp4 -s 00:00:00:000 -e 00:02:00:000
```

### config.json

|       item        |                          mean                          |
|:-----------------:|:------------------------------------------------------:|
|  audio-save-path  |         Export path of audio file \| 音频文件的导出地址         |
| audio-file-format | The export file format for audio files \|  音频文件的导出文件格式 |
