# Changes to be made

1. On line 15 of `index.html` you hard coded a path to an image that exists only on your system. Either include the image in the `.img` folder or you a link to the image.

**Change this...**

```html
<img
  src="C:/Users/Arcel/OneDrive/Desktop/music-player/img/jacinto-1.jpg"
  alt="Album Art"
/>
```

With something like this:

```html
<img src="./img/jacinto-1.jpg" alt="Album Art" />
```

2. Put a separator in between the `span` tag with the id of `current-time` and `duration`; preferably a /.

3. Make sure the album art is bound to the div `img-container`.
4. Let's make this work: Use event listeners applied to the player controls so that users can cycle through the songs available. We also need the artist, title, duration and current-time to all be working with the user experience.

You've done well with designing this music player and creating a nice simple aesthetic reminiscent of spotify. Keep up the work!

Happy Coding.
