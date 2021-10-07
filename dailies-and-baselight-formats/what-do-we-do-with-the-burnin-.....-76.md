# What do we do with the Burnin? ..... 76

Baselight v5 Training Manual

Burnins are rendered onto the image.

We are now going to quickly learn how to do this in the render panel. Remember in dailies you don’t always do much grading. You might match some takes and cameras but not necessarily. On some productions, you will simply be processing data, so let’s process this data.

1 Go to the Views menu and select Render.

You will render the Bar Scene image with the Mask and Data Dailies Burnin activated. You will also render these files as an H264 movie. Editorial have also requested that you render these files with the original file name and that they are rendered in a Rec 709 colour space.

1. 2  Make sure Frames to Render is set to All Frames.
2. 3  Select Movies – Video Only as we are rendering to a movie format with no audio.
3. 4  Ensure that the codec is set to H264. If you are using Baselight STUDENT, this will be the only option.

   Image 103. Render Panel with Output File Type parameters.

4. 5  Click on the upside-down triangle and enable the Masks and Burnins and Render Resolution options.

You are going to match the settings in the Render Panel to how you have been viewing your scene.

1. 6  Render Resolution should be HD 1920x1080. If we don’t choose the correct render resolution we won’t have access to the correct Burnin or Mask.
2. 7  Specify the following variables: Mask - 3.0.1; Burnin - Data Dailies; and Render Colour Space - Rec 1886 2.4 Gamma / Rec709.

Dailies and Baselight Formats 76

What do we do with the Burnin?

Image 104. Render Panel with Colour Space, Mask and Burnin selected.



Baselight v5 Training Manual

8 Remember that the editorial team also wants the files with the original name, so please select the Input File name checkbox.

Image 105. Render Panel. Input Filename is enabled for output.

Remember all files will be saved according to the path that is defined in the Directory field. The path to your files will start with the container directory. In Baselight STUDENT this will be images1. Remember the codes we mentioned previously?

%J means name of job and %S means name of scene. If you find this confusing, just look for the words First File at the bottom of the page. This will tell you where the rendered files can be found.

Image 106. Render Panel fully set up according to the instructions for this deliverable.

9 Select Verify.  
 You will see the message “These Frames should render correctly.” 10 Select Submit Render \(1 deliverable\).

The Queue Monitor will open and if you look at the progress bar you will see the text update, reflecting that the movies are being written.



Baselight v5 Training Manual

Image 107. Queue Monitor.

11 Once the render has finished you should check that the images seem correct by looking in FLUX Manage.

12 Go to the Views menu and choose FLUX Manage.  
 Navigate to the path where you rendered the files. If you are using Baselight STUDENT this will be in

/images1/%J/\_renders/%S.  
 Yes, we are checking that you understand the codes! So, the name of the job \(%J\) and the name of the

scene \(%S\).

A quick look in FLUX Manage will tell you if the render has worked. You don’t need to insert it into the timeline as you can see it in the preview area. With the rendered file selected, FLUX Manage shows the file details on the top right.

