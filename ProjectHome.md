PHPVideoToolkit has been updated to version 2.0.0.alpha to and the main repo and issue tracking can be found at Github https://github.com/buggedcom/phpvideotoolkit-v2


---


This class is a wrapper around the FFmpeg, FLVTools2 and Mencoder programs to allow PHP developers to manipulate and convert video files in any easy to use object oriented way. It also currently provides FFmpeg-PHP emulation in pure PHP so you wouldn't need to compile and install the module. Note, it isn't intended as a FFmpeg-PHP replacement, only an alternative solution and it is recommended that if you make heavy use of the FFmpeg-PHP functionality you should install the module as it is more efficient.

PHPVideoToolkit is pretty much the only video/audio class that you will need from now on. It performs several types of manipulation operations that include video format conversion, extract video frames into separate image files, assemble a video stream from a set of separate video images, extract audio from video, watermark videos and extracted frames. Several parameters can also be configured like the output video file format (which can be Flash video or any other supported by ffmpeg), video and audio bit rate and sample rate, video dimensions and aspect ratio. It can also retrieve information about the media file, such as duration, bitrate, framerate, format, dimensions, display aspect ratio, pixel aspect ratio, audio stereo, audio frequency and audio format, without any other additional library such as ffmpeg-php.

Note: This is now dual licensed under New BSD and GPLv2