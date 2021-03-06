#  Audio, Video, Images  
---
## Video and Audio APIs 

 The \<video> and \<audio> elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:   
``` 

<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```
You can review what all the HTML features do in the article linked above; for our purposes here, the most interesting attribute is controls, which enables the default set of playback controls. If you don't specify this, you get no playback controls.   


his is not as immediately useful for video playback, but it does have advantages. One big issue with the native browser controls is that they are different in each browser — not very good for cross-browser support! Another big issue is that the native controls in most browsers aren't very keyboard-accessible.You can solve both these problems by hiding the native controls (by removing the controls attribute), and programming your own with HTML, CSS, and JavaScript. 


* The HTMLMediaElement API  
Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both \<audio> and \<video> elements, as the features you'll want to implement are nearly identical.  

* Exploring the HTML  
1. The whole player is wrapped in a \<div> element, so it can all be styled as one unit if needed.
2. he \<video> element contains two \<source> elements so that different formats can be loaded depending on the browser viewing the site.
3. The controls HTML is probably the most interesting: 
   * We have four \<button>s — play/pause, stop, rewind, and fast forward.
   * Each \<button> has a class name, a data-icon attribute for defining what icon should be shown on each button (we'll show how this works in the below section), and an aria-label attribute to provide an understandable description of each button, since we're not providing a human-readable label inside the tags. The contents of aria-label attributes are read out by screenreaders when their users focus on the elements that contain them.
   * There is also a timer \<div>, which will report the elapsed time when the video is playing. Just for fun, we are providing two reporting mechanisms — a \<span> containing the elapsed time in minutes and seconds, and an extra \<div> that we will use to create a horizontal indicator bar that gets longer as the time elapses.


```
<div class="player">
  <video controls>
    <source src="video/sintel-short.mp4" type="video/mp4">
    <source src="video/sintel-short.webm" type="video/webm">
    <!-- fallback content here -->
  </video>
  <div class="controls">
    <button class="play" data-icon="P" aria-label="play pause toggle"></button>
    <button class="stop" data-icon="S" aria-label="stop"></button>
    <div class="timer">
      <div></div>
      <span aria-label="timer">00:00</span>
    </div>
    <button class="rwd" data-icon="B" aria-label="rewind"></button>
    <button class="fwd" data-icon="F" aria-label="fast forward"></button>
  </div>
</div>
``` 
* Exploring the CSS
```
.controls {
  visibility: hidden;
  opacity: 0.5;
  width: 400px;
  border-radius: 10px;
  position: absolute;
  bottom: 20px;
  left: 50%;
  margin-left: -200px;
  background-color: black;
  box-shadow: 3px 3px 5px black;
  transition: 1s all;
  display: flex;
}

.player:hover .controls, player:focus .controls {
  opacity: 1;
}
```

1. We start off with the visibility of the custom controls set to hidden. In our JavaScript later on, we will set the controls to visible, and remove the controls attribute from the \<video> element. This is so that, if the JavaScript doesn't load for some reason, users can still use the video with the native controls.
2. We give the controls an opacity of 0.5 by default, so that they are less distracting when you are trying to watch the video. Only when you are hovering/focusing over the player do the controls appear at full opacity.
3. We lay out the buttons inside the control bar using Flexbox (display: flex), to make things easier.

---

## Images 

* Controlling sizes of images in CSS  
```
img.large { 
width: 500px; 
height: 500px;} 
img.medium { 
width: 250px; 
height: 250px;}
img.small { 
width: 100px; 
height: 100px;}
```

* ALIGHING IMAGES USING CSS  
```
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}
``` 
* Centering images Using CSS  
```
img.align-center { 
display: block; 
margin: 0px auto;} 
img.medium { 
width: 250px; 
height: 250px;}
```
* Background Images  
```
body {
background-image: url("images/pattern.gif");}
```
