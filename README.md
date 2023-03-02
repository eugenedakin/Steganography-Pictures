# Steganography-Pictures
Add and remove a picture-in-a-picture with steganography

Steganography is the ability to hide another image, or other data that is a secret into another that is not a secret. 

- Compatible OS's: All
- Xojo IDE: 2022 r1.1
- Xojo API: API 2
- Level: Advanced

Code for this example is in the following methods: 1) HidePicture, and 2) RetrievePicture

Screen Grab:

![](https://github.com/eugenedakin/Steganography-Pictures/blob/main/SteganographyArticlePreview.png)

Instructions:

Run the program in Xojo 2022 r1.1
- Press the Load Original button and load 300bx300b-72dpi.png picture
- Press the Load Secret button and load Secret75x75-72dpi.png picture
- Press Create Blended Pic button to create and then save the steganographic picture

- To decrypt the picture, run the RetrievePhoto program 
- Press the Load Blended Pic button and load the BlendPic.PNG picture
- Press the Retrieve Picture button to show and save the hiddlen picture

An article was written in xDev (xdevmag.com) Issue 20.4 (July/August 2022) and Issue 20.5 (Sept/Oct 2022) that describes the Xojo code. This is a great journey using pictures to hide and retrieve pictures using steganography.
