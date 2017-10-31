---
id: slider
title: Slider
category: Components
permalink: docs/slider.html
---
<div><div><p>A component used to select a single value from a range of values.</p></div><h3><a class="anchor" name="props"></a>Props <a class="hash-link" href="docs/slider.html#props">#</a></h3><div class="props"><div class="prop"><h4 class="propTitle"><a class="anchor" name="viewproptypes"></a><a href="docs/viewproptypes.html#props">ViewPropTypes props...</a> <a class="hash-link" href="docs/slider.html#viewproptypes">#</a></h4></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="disabled"></a>disabled?: <span class="propType">bool</span> <a class="hash-link" href="docs/slider.html#disabled">#</a></h4><div><p>If true the user won't be able to move the slider.
Default value is false.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="maximumtracktintcolor"></a>maximumTrackTintColor?: <span class="propType"><a href="docs/colors.html">color</a></span> <a class="hash-link" href="docs/slider.html#maximumtracktintcolor">#</a></h4><div><p>The color used for the track to the right of the button.
Overrides the default blue gradient image on iOS.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="maximumvalue"></a>maximumValue?: <span class="propType">number</span> <a class="hash-link" href="docs/slider.html#maximumvalue">#</a></h4><div><p>Initial maximum value of the slider. Default value is 1.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="minimumtracktintcolor"></a>minimumTrackTintColor?: <span class="propType"><a href="docs/colors.html">color</a></span> <a class="hash-link" href="docs/slider.html#minimumtracktintcolor">#</a></h4><div><p>The color used for the track to the left of the button.
Overrides the default blue gradient image on iOS.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="minimumvalue"></a>minimumValue?: <span class="propType">number</span> <a class="hash-link" href="docs/slider.html#minimumvalue">#</a></h4><div><p>Initial minimum value of the slider. Default value is 0.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="onslidingcomplete"></a>onSlidingComplete?: <span class="propType">function</span> <a class="hash-link" href="docs/slider.html#onslidingcomplete">#</a></h4><div><p>Callback that is called when the user releases the slider,
regardless if the value has changed. The current value is passed
as an argument to the callback handler.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="onvaluechange"></a>onValueChange?: <span class="propType">function</span> <a class="hash-link" href="docs/slider.html#onvaluechange">#</a></h4><div><p>Callback continuously called while the user is dragging the slider.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="step"></a>step?: <span class="propType">number</span> <a class="hash-link" href="docs/slider.html#step">#</a></h4><div><p>Step value of the slider. The value should be
between 0 and (maximumValue - minimumValue).
Default value is 0.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="style"></a>style?: <span class="propType">ViewPropTypes.style</span> <a class="hash-link" href="docs/slider.html#style">#</a></h4><div><p>Used to style and layout the <code>Slider</code>.  See <code>StyleSheet.js</code> and
<code>ViewStylePropTypes.js</code> for more info.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="testid"></a>testID?: <span class="propType">string</span> <a class="hash-link" href="docs/slider.html#testid">#</a></h4><div><p>Used to locate this view in UI automation tests.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="value"></a>value?: <span class="propType">number</span> <a class="hash-link" href="docs/slider.html#value">#</a></h4><div><p>Initial value of the slider. The value should be between minimumValue
and maximumValue, which default to 0 and 1 respectively.
Default value is 0.</p><p><em>This is not a controlled component</em>, you don't need to update the
value during dragging.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="thumbtintcolor"></a><span class="platform">android</span>thumbTintColor?: <span class="propType"><a href="docs/colors.html">color</a></span> <a class="hash-link" href="docs/slider.html#thumbtintcolor">#</a></h4><div><p>Color of the foreground switch grip.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="maximumtrackimage"></a><span class="platform">ios</span>maximumTrackImage?: <span class="propType">Image.propTypes.source</span> <a class="hash-link" href="docs/slider.html#maximumtrackimage">#</a></h4><div><p>Assigns a maximum track image. Only static images are supported. The
leftmost pixel of the image will be stretched to fill the track.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="minimumtrackimage"></a><span class="platform">ios</span>minimumTrackImage?: <span class="propType">Image.propTypes.source</span> <a class="hash-link" href="docs/slider.html#minimumtrackimage">#</a></h4><div><p>Assigns a minimum track image. Only static images are supported. The
rightmost pixel of the image will be stretched to fill the track.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="thumbimage"></a><span class="platform">ios</span>thumbImage?: <span class="propType">Image.propTypes.source</span> <a class="hash-link" href="docs/slider.html#thumbimage">#</a></h4><div><p>Sets an image for the thumb. Only static images are supported.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="trackimage"></a><span class="platform">ios</span>trackImage?: <span class="propType">Image.propTypes.source</span> <a class="hash-link" href="docs/slider.html#trackimage">#</a></h4><div><p>Assigns a single image for the track. Only static images are supported.
The center pixel of the image will be stretched to fill the track.</p></div></div></div></div>