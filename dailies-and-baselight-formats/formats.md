# Formats

Formats allow the user to tell the system how many pixels are in the image, in terms of width and height, along with information about pixel aspect ratio. They also allow us to set up Masks and Burnins. And, very importantly, they contain information explaining how an image in one format should be geometrically mapped to another format. We would, for example, modify a format to allow us to handle a file shot in 4K but display it in HD 1920x1080.

A format contains the following information:

* Pixel aspect ratio
* Vertical and horizontal resolutions
* Proxy resolutions
* Masks
* Mappings to other formats
* Burnins

We will now open the Formats window.  
1. Select the Baselight menu and then Formats.  
The first column of the Baselight window displays a list of formats names.

Image 96. First column of the Formats window.

Look at the next column to the right. It should contain three tabs: Masks, Mapping and Burnins.

Image 97. First two columns of the Formats window. If you click on different formats, different Masks become available to you. The red arrow points to the tabs for Masks, Mapping and Burnins. In this screengrab we see the Masks associated with the HD 1920x1080 format.

Today as you create the dailies files \(our “deliverable”\), you will also apply a Mask and a Burnin via these tabs.

By default, a number of Masks and mappings are pre-built into the software. Let’s look at the Masks in the HD 1920x1080 format.

2. Click on the HD 1920x1080 format and select the Masks tab.

Can you see the Masks available? Click on one of the masks to select it. The purple box represents the active part of an image when a Mask \(also called blanking\) is applied to an image.



Image 98. The Formats window. The Masks associated with this format are visible in the Masks tab.

3. Click on the Burnins tab associated with the HD 1920x1080 format. Look towards the middle of the window and you will see two entries, one called Film Dailies and the other called Data Dailies.

Image 99. The red arrow points to the Burnins entries associated with the HD 1920x1080 Format.

These settings won’t really make sense unless you can see them in relation to the image. You will now view your scene in an HD 1920x1080 format. For this reason, we will need to change the Viewing Format of your scene. Hopefully your day\_1 scene is open.

4.  Move the Formats window away from the image area. You can do this by grabbing the top of the Formats window with your mouse.
5.  Make sure that the camera test scene/day\_1 is open. You will use this scene to render files with a Burnin and Mask applied. Ensure that you can see the image and also that you can access the Viewing Format menu in the Cursors section of the Baselight user interface.

The options that are associated with the Viewing Format, such as Masks and Burnins, are activated in the Baselight interface, but they are actually created in the Formats window.

6. You will now make sure that you are viewing the day\_1 scene in an HD 1920x1080 format. Click on the Viewing Format list. Choose the HD 1920x1080 format.

You might be wondering, “Didn’t we create the scene in 2048x1556?” Yes, we did. However, now we are viewing it inside a HD 1920x1080 frame. The image should appear identical.

Now that you are viewing via the above format, you have access to the Masks and Burnins associated with that format. You will now activate a Mask and Burnin.

Image 100. Viewing Format changed to HD1920x1080, with a Burnin and Mask activated.

7. Click on the Mask drop-down menu and choose 3.0.1.

If you look at your image display, the image should now have black strips at the top and bottom of the image. Sometimes this Mask effect is called letter boxing.

8. Click on the Burnin drop-down menu and choose Data Dailies. Text should now appear over the masked areas.

In this example, you are simply learning how to activate the Burnin, but in reality, you might be asked to modify an existing Burnin or make a completely new one to suit the particular requirements of the production.

Remember we are viewing the image in the HD 1920x1080 format and we are seeing the Mask and Burnin that is associated with this format. We will now return to the Format Window just to show how to modify a Burnin.

9.  If the Formats Window isn’t still open, re-open it, then locate the HD 1920x1080 format. Make sure it is selected.
10.  Click on the Burnin tab. You should be able to see two sets of Burnins: Film and Data.
11. Select Data because this corresponds to the Burnin that you added when you changed the Viewing

   Format.

Reminder: At this point your Viewing Format should be HD 1920x1080 and the Data Dailies Burnin should be active.

Image 101. Viewing Format changed to HD 1920x1080 and the Formats Window with HD 1920x1080 selected.

You will now modify the Data Dailies Burnin slightly by removing one of the grey borders and you will see the change reflected on the image.

12.  From the Formats Window, make sure HD 1920x1080 and Data Dailies is still selected.
13. Select the path to image text \(the path to image relates to the text that is displayed at the top of the

   image\). Change the Border setting from Lozenge to none.

   Image 102. The path to image with the lozenge border.

The path to the image should now be displayed without a border.

