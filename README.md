# video-data-transmit
 encodes any given base64 data into a video or decodes a video into a base64 string

## Encoding
1. create a text file with a base64 string inside
2. open cmd/terminal and run the following command:
```python encode.py -f <file_name.txt>```
3. wait
4. be happy
5. upload the video to youtube for easy "cloud" storage

## Decoding
1. open cmd/terminal and run the following command: ```python decode.py -f <file_name.mp4>``` or ```python decode.py -l <youtube_video_link>```
2. will create a text file with the base64 string called either <file_name.txt> or <whatever_the_youtube_video_was_called.txt>