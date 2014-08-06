# FetchVideo #
### Example Python 3 script that shows how to use [pytube](https://github.com/NFicano/pytube"pytube") ###

This is a simple python 3 script that shows how to use [pytube](https://github.com/NFicano/pytube "pytube") from the command line. Usage is quite simple:

1. You can either start the script and supply it with a Youtube URL:
    
     fetchVideo http://www.youtube.com/etc

2. Or: you may start it without any argument.

     fetchVideo

you are then asked to provide a url, name of the file that will be saved, and the
video format from a provided list of video formats (depending on the original video format).
Below is a sample run:

     prompt:> fetchVideo.py
     Video URL:> http://www.youtube.com/watch?v=E3zkIA7fIts
     Available Formats:
     1. Format: MPEG-4 Visual        || Extension: .3gp                  || Resolution:    144p   
     2. Format: MPEG-4 Visual        || Extension: .3gp                  || Resolution:    240p   
     3. Format: Sorenson H.263       || Extension: .flv                  || Resolution:    240p   
     4. Format: H.264                || Extension: .mp4                  || Resolution:    360p   
     5. Format: H.264                || Extension: .mp4                  || Resolution:    720p   
     6. Format: VP8                  || Extension: .webm                 || Resolution:    360p   
     Select the number of the video:> 5
     Save file as:> Zain2
     Download(yes-ok/no):> ok
     File szie: 11695557 bytes.
     Download Complete. Stored as /home/abdalla/Python/Zain2.mp4.


When prompted to *__Download__* you may enter __yes__ or __ok__, anything else is as good as a __no__.

------------
Abdalla S. Alothman      
GSM: +965-666-22595    
Kuwait, Aug 5, 2014.

