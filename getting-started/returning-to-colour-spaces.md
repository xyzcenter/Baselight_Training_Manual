# Returning to Colour Spaces

Returning to Colour Spaces 1 Look for the ‘Colour Space’ section on the UI. The ‘Input’ Colour Space for the first selected clip - the C300 sequence - should be set to **From Metadata**. You should see something similar to the image below.

![ Image 11. Colour Space section with Input Colour Space set to From Metadata.](../.gitbook/assets/image%20%2819%29.png)

Image 11. Colour Space section with Input Colour Space set to From Metadata.

When you select a clip in the timeline before any colour correction layers have been applied, only information relating to the characteristics of the source is shown. This information is referred to as **Layer** **0**. For example, in **Layer 0** you will see the file path to the sequence on disk, its resolution and its Colour Space.

2 Now move to the second clip in the timeline \(**Alt+X** or drag the cursor\). If this is the file from the Epic camera you will see that the ICS is set to Automatic.

{% hint style="info" %}
Remember if the source images are in a raw format from manufacturers such as Red or Arri, Baselight will automatically decode the files into the correct colour space.
{% endhint %}

![ Image 12. Colour Space section with Input Colour Space set to Automatic.](../.gitbook/assets/image%20%2813%29.png)

Image 12. Colour Space section with Input Colour Space set to Automatic.

Let’s have a quick recap of what you have done so far. You have created a HD scene and you have chosen a Working Colour Space of either Arri Log C Wide Gamut or FilmLight T-Log E Gamut.

You have now imported 4 sequences from different cameras. You have seen that if a source sequence is in a raw format, the Input Colour Space will be set to **Automatic**; if the source image is not a raw format but has colour information set in the header file the Colour Space will be set to **From Metadata**.

Now your Scene is set up, we must set a third Colour Space. This is the **Viewing Colour Space** that we also sometimes call the Cursor Colour Space. We set a Viewing Colour Space so that our images are viewed correctly. When we set the Viewing Colour Space we match it to the Colour Space of our viewing device. On monitors this is often Rec 709 \(Rec 1886 2.4 gamma rec 709\). And if we are using Baselight STUDENT on a Mac laptop, then this would probably be sRGB.

3 Set the Colour Space that is appropriate to your viewing device. Remember you need to know the Viewing Colour Space of your monitor – and if working on a laptop with no SDI out, the Colour Space will typically be sRGB.



![](../.gitbook/assets/image%20%2820%29.png)

Image 13. Options on the Viewing Colour Space menu.

{% hint style="info" %}
Note the ‘Use these cursor settings...’ options in the Actions menu within the Cursors section of the UI; this means you can avoid having to set the Viewing Colour Space every time you open the scene again.
{% endhint %}

Why do I have to set up Colour Spaces in so many different places – why can’t I keep everything the same all the way through?

Well, if you really wanted to you could. You could tag everything with one Colour Space – work in the same Colour Space and output in one Colour Space – but this is not a modern workflow and will probably limit the range within which you are able to apply grades.

By distinguishing between Input, Working and Viewing Colour Spaces, you can more easily mix different types of material in a project and the images should look correct when you start grading. So, if you have set up a scene with a Working Colour Space as Arri Log C wide gamut because most of your material is Arri – but then a producer asks you to also insert some Rec 709 stock footage - it’s all fine! Remember you just need to make sure that the Input Colour Space is tagged correctly or you let Baselight do the work and set the inputs to read From Metadata or Automatic.

If you set up your scene correctly by properly identifying...   
• Working Colour Space   
• Input Colour Space   
• Viewing Colour Space 

...you can then render to any Colour Space that is required for the project. So yes, you could deliver for cinema, TV or even Youtube without having to do a regrade.

{% hint style="info" %}
If you want to check out this process, the **Colour Space Journey** window is useful. This provides an overview of what is happening on a shot by shot basis to the images in the timeline. 

To open the **Colour Space Journey** go to the menu bar at the top of the UI. Select Views and choose Colour Space Journey or press **Shift+Ctrl+J** on the keyboard \(Or **Shift+Cmd+J**\)
{% endhint %}



![ Image 14. Colour Space Journey option.](../.gitbook/assets/image%20%2815%29.png)

Image 14. Colour Space Journey option.

{% hint style="info" %}
The Colour Space Journey is useful because it shows you the following:

* The Input Colour Space of the selected clip.
* The Working Colour Space of the scene.
* The Viewing Colour Space of the scene.

  It also provides you with hints and warnings if it doesn’t think what you are doing is correct.
{% endhint %}

![ Image 15. Warnings in the Colour Space Journey.](../.gitbook/assets/image%20%2822%29.png)

Image 15. Warnings in the Colour Space Journey.

Usually the DOP will ask to see the images without a grade. You would then be asked to match the shots as each different camera has its own characteristics. Normally this will just involve changing brightness and possibly saturation. After this process is done you can begin Grading.

