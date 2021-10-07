# Conforming a Sequence

This section uses images and an EDL provided in:

conform/

Conforming a Sequence

This chapter will teach you about conforming from an AAF EDL \(Edit Decision List\) file. Methods you learn will work almost identically with other EDLs like CMX or XML.

The EDL Import Window

1. 1  From the Job Manager, select the camera\_test job \(you will have created this in the first section of this guide.\)
2. 2  From Scene column, use the action button and choose New Scene.
3. 3  The New Scene window prompts you for information.

Remember that when you create a scene, you have to know the frame rate of the material you are using. You can see the frame rate of the material in FLUX Manage.

For today’s exercise, the frame rate is 25fps and we will use an HD1920x1080 resolution.

You will also need to set a working colour space. As before, choose a wide-gamut colour space such as ARRI Log-C, ACES or FilmLight T-Log E Gamut.

4 Enter the required information and click Done.

When the scene has been created, you will see the name of the job and scene on the top right corner of the Baselight user interface.

Image 108. Top right corner of the Baselight user interface.

You will now open the EDL Import window from the Views menu. 5 Go to the Views menu and select EDL Import.  
Remember, a conform can only happen if a scene is open.

Image 109. Open Views menu. EDL Import is selected.

Image 110. The EDL Import window when first opened. The red arrow points to the button that allows us to browse for the EDL file.

With the EDL Import window open, the first thing you will need to do is to navigate to the folder where you have stored the EDL file. In this example, we are using an AAF file. You will also need to tell Baselight where to look for the images.

1. 6  Select the icon resembling a piece of paper to browse for the AAF file.
2. 7  Navigate to /images1/conform and select BaselightSTUDENT\_Conform\_Tutorial.aaf.

Baselight will extract the proper frame rate from the EDL. You will note that you cannot change this field. The EDL you are using is 25fps to match the 25fps media that you are about to conform.

Also, once you have selected an EDL, Baselight will display the raw EDL in a tab at the bottom of the EDL Import window. It is always useful to check the raw EDL as it will tell you what ‘events’ will be required for Baselight to rebuild the edit.

Image 111. The EDL Import window after the AAF file path has been chosen. At this point no other options have been selected. The red arrow points to the Raw EDL tab.

The next thing you need to do is tell Baselight where to look for the images. You set the path to the images in the Search Directory field.

Image 112. The EDL import window after both the AAF file and Search Directory paths have been chosen.

8 Click the Search Directory field and navigate to /images1/conform.

At the most basic level, you need to know the locations of your EDL file and the relevant media. You will notice on the EDL Import window there are lots of options you can manually set, but sometimes it’s easiest to simply tell Baselight to try all options and let it try to complete the conform.

The Try All Options method has pros and cons. Often the editing may take place elsewhere and you may not know a lot about the EDL or the data it links to. Try All gives you a quick method of trying the most likely conform possibilities. You will definitely conform something.

However, Baselight really will try all options and so it will present you with many possible versions of the conform. Each version is presented to you in a different tab. You could quite easily end up with 20 versions of the conform. It’s up to you to choose the one that the editor intended.

9 Go on, give it a go. Press Start Conform without setting any other further information and let Baselight run for a few moments.

You will end with a number of tabs. Each one of these tabs represents a different version of the conform. As you click through the tabs, you will see that the options in the EDL Import window will change. Each version is a variation on these options.

As a general rule when you do conform, you would use Try All Options when you know nothing about the media or the EDL. But sometimes you will know how the EDL is meant be conformed \(from source rather than record timecode, for example\). When this is the case, you can manually set options to speed up the conform and have fewer conform versions to choose from when the process is complete.

Image 113. The EDL Import window with no conform options set and Try All Options enabled.

A couple of tips for achieving accurate conforms: Look at the clips’ metadata and also try to understand how the clips are laid out on disk. You’ll recall that we can view a clip’s metadata in FLUX Manage.

Let’s quickly open one of the browsing tools and have a look at the metadata. Think of metadata as information about the clip and keep in mind that it is typically stored in file header of a clip.

10 Open FLUX Manage and select one of the clips that will form part of the conform. If you look to the right of the window with a clip selected you should see certain information relating to the clip including resolution, timecode and filename.

Even with just a small amount of information such as timecode, we can ensure the conform is more efficient. Remember the more accurate you can be with the conform options, the quicker the conform will

be. While you may not notice much of a change in this small tutorial example, you would definitely notice if you were conforming from a couple of terabytes worth of material.

Image 114. FLUX Manage with a clip is selected. Metadata from the selected clip is displayed on the right of the window. The long red arrow points to the clip’s timecode.

You will also notice in the clip’s metadata that we can see mention of a tape name and a clip name.

Metadata such as timecode, clip name and tape name allows us to give Baselight certain information that it can use to complete the conform more quickly and accurately. The more information we have, the quicker and more accurate a conform will be.

Now let’s turn our attention to the image file path. If we look at any of the clips in the conform directory, we see something like:

/images1/conform/Day03A020LV01.5125A5125A1A9.mxf

Let’s try and fill in some of the options in the EDL Window. We at least know we can tell Baselight to use timecode as one of the options because we have seen timecode in the clips’ metadata.

1. 11  Set the Search Order field to Timecode.
2. 12  Set the Timecode Location to Header.
3. 13  Now click Start Conform again. You will see fewer conform variations presented because you have limited the possibilities to only those involving timecode.

The next option in the EDL Import window is Overwrite Tape Name. We have seen how the clips are laid out on disk and there is no tape name mentioned in the path.

14 Click the Overwrite Tape Name drop-down menu and choose With Filename.

Image 115. The EDL Import window showing the first set of conform options selected. We can see conform variations will be limited to those involving timecode.

1. 15  Also select Match Events by Filename.
2. 16  Now click Start Conform again. You should end up with a single conform \(if you end up with 100% and a 0% conform, just make sure the 100% is selected\).
3. 17  Click Done.

Image 116. The EDL Import window showing completed conform limited by several options discussed.

Once you have selected Done, the EDL Import window will close and you are ready to apply a grade to your shots.

If you wish to experiment further, try adding a single layer to each event/shot by using the P shortcut and practice applying a primary grade using Video Grade or the tool of your choice.

Remember to save your scene before closing.

