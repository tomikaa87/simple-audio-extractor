# Simple Audio Extractor

Easy to use tool to extract the audio track from a video file. The application is based on the well known [ffmpeg](https://www.ffmpeg.org) and uses its standalone executable to convert the audio track of popular video formats like MPEG4 and WEBM.

# Screenshots

![sae-1](https://github.com/tomikaa87/simple-audio-extractor/blob/master/images/sae-1.png)
![sae-2](https://github.com/tomikaa87/simple-audio-extractor/blob/master/images/sae-2.png)

# Getting started

Currently there are no pre-build binaries, you have to compile the app for yourself. In order to do that you should follow these steps:

- Make sure you have Visual Studio (2017 is preferred) installed with the .NET development package
- Clone the repository: `git clone https://github.com/tomikaa87/simple-audio-extractor.git`
- Open `AudioExtractor.sln` in Visual Studio (I recommend VS 2017)
- Hit "Build"

The application needs `ffmpeg.exe` placed into the `3rdparty` folder next to `AudioExtractor.exe`. I suggest using the standalone static binary which can be downloaded from https://ffmpeg.zeranoe.com/builds. Choose the build suitable for your Windows.

If everything is in place, start the app, drag and drop the video files you want to convert, select the target folder with the "Browse" button and hit "Start". In the current version you should see a bunch of ffmpeg console windows with the conversion status in them but at the end they will disappear.
