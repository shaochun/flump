# Intro

In this branch some flash example files are created for ui demonstration.

# Steps

1. [Install the latest version of Adobe AIR](http://get.adobe.com/air/).
1. [Install the Flump AIR app](https://bitbucket.org/tconkling/flump-binaries/downloads/flump-exporter.air).
2. Create a `.fla` in Flash CS 5, 5.5, or 6.
3. Create a new item in the library and draw a shape in its canvas. (**CHILD**)
4. Right-click on the item, select its properties, tick the `Export for ActionScript and Export in frame 1` checkboxes and change its base class to `flash.display.Sprite`.
5. Create a second item in the library (**PARENT**), and drag the first into it. 
   MAKE SURE YOU SET THIS **PARENT**’S PROPERTIES TO: `Export for ActionScript and Export in frame 1` & `flash.display.MovieClip` or the MOTION KEYS won’t get exported!!
6. Add additional frames in the second item, and create a classic tween moving the first item around
   in those frames.
7. Save the file and publish it as a swf.
8. Open the Flump app and change its import directory to the directory containing the `.fla` and
   `.swf` files. The `.fla` file should appear in the list of source files.
9. Select the `.fla` file and click 'Preview'. The tween you created in step 6 should start playing
   back in a preview window.
