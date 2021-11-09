Media Player
https://www.javatpoint.com/kotlin-android-media-player
https://developer.android.com/guide/topics/media/mediaplayer
<h1>Media Player</h1>
<h2>Introduction</h2>
Media is a class that is used to control the playback of audio/vedio files and streams.

The android.media.MediaPlayer class is usd to control the audio or video files. It access the build-in media player services such as playing audio, video, etc. To use the MediaPlayer class, we have to call the create the instance of it by calling create() method of this class.

<div>
<h3>Methods of MediaPlayer class</h3>
<div>There are examples of MediaPlayer method:</div>
<img width="100%" src="images/method.PNG" />
</div>

<h3>Using MediaPlayer</h3>
One of the most important components of the media framework is the MediaPlayer class. An object of this class can fetch, decode, and play both audio and video with minimal setup. It supports several different media sources such as:
<h4>1. Local resources</h4>
<h4>2. Internal URIs, such as one you might obtain from a Content Resolver</h4>
<h4>3. External URLs (streaming)</h4>
For a list of media formats that Android supports, see the Supported Media Formats page.

Here is an example of how to play audio that's available as a local raw resource (saved in your application's res/raw/ directory):
<img width="100%" src="images/1.png" />
