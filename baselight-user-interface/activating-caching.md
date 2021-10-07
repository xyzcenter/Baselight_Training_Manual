# Activating Caching

If working on a Mac you may need to specify a directory to be used for the image cache. This can be done at the top of the ‘System’ page in the preference settings. A restart will be necessary to save any changes made.

Let’s open scene’s settings to check that caching is activated. 1 Go to the Views menu and Choose Scene Settings.


Baselight User Interface 56



Image 73. Open Views Menu. Scene Settings is highlighted in blue.


Image 74. Scene Settings Window. Caching is set to full.

2. Locate the Timeline Caching setting \(on the General Tab\).
3. Make sure that Timeline Caching is set to Full.
4. Close the window by pressing the small x in the top right corner.
5. Play the timeline \(use the keyboard Space bar or the transport controls on the Blackboard or Slate\).

When you play the timeline, you will see that Baselight displays the three-bar icon we’ve discussed at the top of the screen. Again, the bars depict whether images are being read from disk \(top\), processed \(middle\), or written to disk \(bottom\). The icon to the left of the playback status bars indicates the current caching mode – an arrow pointing into a red disk indicates that the cache is currently being written, an arrow pointing out of a green disk indicates that the cache is being read.

The timeline may also now feature a green stripe.



Image 75. Partially cached timeline.

If you see the green stripe on the timeline, we know that full caching has been activated in the Scene Settings window and that your cached images are ready to be played from disk.

If you don’t see anything, maybe you did not turn on caching in the Views -&gt; Scene Settings window. Or the background indicator has not been activated in the timeline. You can activate the Background Caching status by right clicking in the timeline and choosing the appropriate state




Image 76. Background Caching Status menu.

If you are still having issues activating caching please check that you have a cache directory set up in the Preferences \(activated from the Baselight drop-down menu\).




Image 77. Baselight with the Preferences window open. The System tab is selected and here we can check caching settings. Windows can be closed in Baselight by clicking the small x.

So, are you still wondering why caching can be useful?

If you have been given large images that require a lot of processing it will sometimes be important to cache these files to ensure real-time playback. Imagine for instance that your source images were loaded onto a facility’s shared network storage and that you were having to play them via the network. Imagine that for whatever reason the host network is slow. You would want to cache your files locally before your clients arrive so that you can ensure smooth playback regardless of load on the network or external volumes. In Baselight, all images are cached locally.

By setting our Cache to Full, all caches are enabled to give the best playback performance. Baselight also allows other caching options, including strip, which only caches strips when you explicitly flag them for caching.

{% hint style="info" %}
The essential difference between a layer and a strip is that a strip represents an individual operator such as a sequence, a grade, a filter or a reference selector; a layer represents the combined effect of operators contributing to a single ‘stage’ in the image processing pipeline.
{% endhint %}


This section does not elaborate further on Strip Caching. Suffice it to say for now that this option is activated by choosing Strip Caching in the Views -&gt; Scene Settings window. Then you select the strip you want to cache in the timeline and enable caching by clicking the cache icon in the user interface \(see below\).

Image 78. Strip caching icon.


