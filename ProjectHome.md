Based on <a href='http://code.google.com/p/cs294/'>cs294</a> code, this tiny <a href='https://code.google.com/p/balloon-itemized-overlay/source/browse/trunk/src/com/discalis/android/maps/BalloonItemizedOverlay.java'><code>BalloonItemizedOverlay</code></a> version draws a dynamic balloon that grows or shrink depending on balloon's inner text size. Balloons are drawn on top of the markers image, dynamically considering image's size.

To give it a try just download the source code, compile and run it. It will draw an `OverlayItem` on the map, click on it to show the balloon. Change the text to see how the balloon is dinamically sized ;)

To use it in your own project, <a href='https://code.google.com/p/balloon-itemized-overlay/source/browse/trunk/src/com/discalis/android/maps/SampleBalloonItemizedOverlay.java'>extend <code>BalloonItemizedOverlay</code></a> and <a href='https://code.google.com/p/balloon-itemized-overlay/source/browse/trunk/src/com/discalis/android/maps/SampleMapActivity.java'>add that overlay to your <code>MapView</code></a>.

Remember to change Google Maps API key on layout/main.xml.

<img width='161' alt='Example with a short text' height='240' src='http://balloon-itemized-overlay.googlecode.com/svn/trunk/doc/short_text.png' />
<img width='161' alt='Example with a long text' height='240' src='http://balloon-itemized-overlay.googlecode.com/svn/trunk/doc/long_text.png' />
<img width='161' alt='Example with a large icon' height='240' src='http://balloon-itemized-overlay.googlecode.com/svn/trunk/doc/large_icon.png' />