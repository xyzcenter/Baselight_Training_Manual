# Importing Footage

So far, we have a scene but it has no images. Now, look at the Baselight timeline and you will see a vertical blue line. This is the cursor. You can have multiple cursors in one scene but for the moment we will just use one. So, what is a cursor? It’s just a position on the timeline – just like a play head.

Image 07. Cursor on the timeline.

For the Camera test you will insert 4 shots from 4 different cameras into the timeline. When you first created the scene, you chose a Working Colour Space; however, this isn’t the only place where the Colour Space is significant. There are three main areas where you need to set up the colour spaces in Baselight. • The Working Colour Space when you first set up a scene. This can also be accessed from Views -&gt; Scene Settings. • The Input Colour Space when clips are inserted into the timeline. • The Viewing Colour Space \(also known as the Display Colour Space\). The Working Colour Space could almost be considered as the size of the world that you want to work in. In most instances, grading in a large Colour Space is a good thing,

Every time you insert a new set of images into the scene it is essential to identify their correct Input Colour Space. Colour Spaces used by different camera manufacturers are usually different. Comparing the results of different cameras is the reason why film crews do camera tests – so you need to get the science right if you are setting up the scene. Fortunately, this process is simple in Baselight. Baselight will automatically identify the correct Input Colour Space by analysing the file providing the Input Colour Space Mode is set to automatic or ‘’from metadata’.

If your files are in a raw format, Baselight automatically decodes them into an appropriate Colour Space. Alternatively, if the source file is not a raw format and there is colour information in the file metadata, Baselight will read that information in the header and apply the correct Colour Space. If this is not the behavior that you experience, check the correct options are set in bl-setups. In the New Scenes tab check that "Prefer Automatic/From Metadata" is active or this won't work.

The Viewing Colour Space should match the colour space of your viewing device. By setting this correctly and ensuring the display is correctly calibrated we know we are viewing the images correctly.

If you’re using an external reference monitor, Rec. 1886: 2.4 Gamma / Rec.709 is the correct Colour Space. If you’re using a laptop with no external display then sRGB: ~2.2 Gamma.

Let’s recap. In our example you have four sets of images from four different cameras: C300 / Epic / F65 / Alexa. You will now insert them into the timeline. The images are inserted at the position of the cursor in the timeline. Move the cursor to the start of the timeline as this will be where the first shot is added.

1 Go to the ‘Views’ menu and select FLUX Manage. The FLUX Manage file browser is a standard Baselight browser using columns to display contents of directories and subdirectories – clicking on a directory will show its contents in the column on the right.

Take note of the volume selector button at the top left. This drop-down button provides a list of all the storage volumes available to this system. If you have saved the training media package to another drive, you will need to select the correct volume from this drop-down first.

2 Navigate to the Bar Scene directory and insert the four clips. You can insert multiple shots by holding down Cmd and clicking the shots you want to use. You may also select a range of shots by clicking the first thumbnail and then Shift-clicking on the last thumbnail. All the shots in-between these shots will be added along with the two you have clicked. Any selected shots will be highlighted in yellow.

Image 08. FLUX Manage option.

Image 09. FLUX Manage view. The large red arrow points to the volume selector.

3 When you have inserted the four, move the cursor to the first clip. This is a good opportunity to briefly introduce the timeline controls within the Baselight software.

