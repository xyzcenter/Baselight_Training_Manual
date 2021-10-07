# Setting up the Render View

You can now start to set up your render options. Your task is to export just the marked frames from the timeline. Remember when we talk about “rendering”, we really mean just exporting files from Baselight.

Are you ready? If not, just reread the section above. And if you are confident, let’s begin by choosing how many frames we want to render.

1. Deselect the All Frames button . We are deselecting All Frames because we want to render only the frames we have marked on the timeline.
2. Click the Select Frames button - this will open a submenu.

Image 88. Select Frames drop down menu.

1. Choose Timeline-Marked Frames. Another submenu opens.
2. Select All Marked Frames.

If you have followed the instructions from the previous sections, just two frame numbers will appear in the Frames To Render field. They don’t have to be the same frame numbers as shown in the screengrab, however you should see frame numbers separated by a comma. We need to see something similar to the example in the image below. So, remember the goal of the exercise is to render the frames we have marked in the timeline.

Image 89. Frames To Render field.

Now you can choose your file type. If you are using Baselight STUDENT, the only file type you can choose for stills is JPEG. If you are using a full version of Baselight, you will be able to choose other formats such as TIFF and DPX.

You will now add a Render Format and Colour Space for the files that you are rendering. 5 Click on the icon that looks like an upside-down arrow

A submenu will open.

Image 90. Render field drop-down menu.

1. Select Render Format and choose HD 1920x1080.
2. Now you can choose your Render Colour Space.

Perhaps you are wondering why you are seeing mention of the Colour Space again. It’s simple: When you render files \(export\) you need to know that they will look correct on the recipient’s display. Let’s say for this example that you intend to give the exported stills to the Director of Photography \(DOP\), and you know that she’ll be viewing them on her laptop, which has an sRGB display.

In Baselight, if you have set your scene up correctly, you can render to any colour space without the use of LUTs, including sRGB.

1. Click on the Render Colour Space drop-down menu and you will see a list of colour spaces. Choose sRGB: ~2.2 Gamma / Rec 709 in order to match the display type of the DOP’s laptop.

Image 91. Some of the colour spaces available to you when you click on the Render Colour Space option.

Here is a useful tip to help you understand colour spaces. When you see a camera icon beside the colour space name, it generally indicates a colour space in which the images were captured. The more technically-gifted people in the FilmLight crew will call this a “Scene-referred Colour Space”, but we don’t need to get too technical. Not just yet anyway.

If you see a small monitor beside the name of a colour space, this is generally a colour space that we use to view an image \(we also call these Display-referred Colour Spaces\). So, if when I set up my render, I know the image will be viewed on a laptop, I would set my output colour space to be a flavour of sRGB. If I knew the files would be broadcast on television, I would choose a flavour of Rec 709 \(ignoring for now the HDR televisions that are becoming available to consumers\).

To keep it simple, just remember: the camera icon indicates colour spaces used when capturing an image; the monitor icon indicates colour spaces used when viewing images.

Image 92. The output directory for your render.

The final step in this exercise is to understand where you are placing your images on disk. We have included another section in the Render panel screengrab above. You can see the Directory field - this is where your files will appear after you have finished your render. You also see the Container field.

The container is the root directory where you are keeping your files. We expand on this in longer courses but it is outside the scope of this shorter introductory version.

{% hint style="info" %}
If you are using Baselight STUDENT, your files will be written to a directory called /images1 which was created on your machine when you first installed Baselight. Images1 will be your Container. In Baselight, you also see the container represented with the substitution code %C.

If you are using the full version of Baselight, your container directory may vary.
{% endhint %}

You can see where your file will be written by looking for the First File entry.

Image 93. The Directory field. This shows us the template for where files will be written. If you want to see explicitly where the files are written, look at the First File entry. This is indicated on the screengrab with the red arrow.

No doubt you are wondering why we have some funny looking entries next to the Container label. It all makes sense really. REALLY.

Remember the First File entry on the Render Panel \(see above image\) will tell you the directory path where your files are being written.  
A quick word about those funny looking % codes.

Now let’s look at the meaning of %J and %S.

By default, these codes are added to the Render Panel unless you specifically change them.

%J means job name. %S mean scene name.

So, by default Baselight writes files into a folder that is the name of your job and then into another folder directory that is the name of your scene.

{% hint style="info" %}
If you are having a hard time grasping this, remember to check the First File field. This will show you the file path for your renders.
{% endhint %}

OK, now it’s time to Render.  
9. If your settings look correct, click Submit Render.

The Queue Monitor should open and hopefully you will quickly see the magic word Done. The Queue Monitor also logs previous render information, so if you are on a Baselight system that is used by other people, the Queue Monitor is likely to hold information about previous renders.

Image 94. Queue Monitor. This is where you can check the status of a render.

You may want to try and locate the rendered files. Remember the First File field of the render box shows you where frames are written to.

{% hint style="info" %}
If you are using Baselight STUDENT, renders should be sent to: /images1/camera\_test/day1/, depending on your job and scene name.
{% endhint %}

Rendering takes a little practice. Repeat this exercise a second time if required.

