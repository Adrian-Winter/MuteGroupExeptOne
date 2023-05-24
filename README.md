# MuteAllExeptOne
## A Max for Live plugin that mutes all track in a group except one 🎹

![alt text](https://github.com/Adrian-Winter/MuteGroupExeptOne/blob/main/MuteGroupExeptOne.gif)

## Updates:
+ Now Multiple intances can be used in one set. (Before there was a problem with calculating the group size when having multiple groups in one set.) 
## Why did I create this device ? 😇
For my live setup I needed dynamically change the clips on one track. I created a group that contains my clips, kind of like a sample bank. 
By having all the clips in the group beeing triggered at the same time when launching the group scene, I needed to create a device that acts like a solo button for tracks that are contained in a group without muting track outside the group. 
So I made this device that mutes all tracks contained in a group exept one.

## Use cases:🤓
Here are some cool usecases that you could implement with this device😎: 

 ### Use a group as a __sample bank__.
 Load the samples onto diffrent audio tracks and then browse them using the dial.
 
  ### Use it as a __DJ slicer__
 When you launch the sceneclip of the group all the samples are beeing played, when you turn the dial while multiple tracks are playing you can create cool scratching/slicing effects.

### Use it as a __pitch shifter__
You can load the same clip onto multiple tracks, but pitch it up or down in the clip menue. Then you can use the dial to swap between the differently pitched samples. 

## How to use this application? ⚙️

 + Step one: Download the __MuteAllExeptOne.amxd__.
 + Step two: Drag and drop the __amxd file on an Group Track__ in Ableton.
 + Step three: Select the track that should be unmuted by turning the dial. 
 + Step four: __Optional:__ Midimap the dial to a midi controller (Press cmd-m)
 

## How did I make this device? 🧐
Max4Live offers a visual cooding IDE. 
Programming in M4L was a fun experience. Tbh I thought it would be much simpler programming in a visual cooding environment compared to a script based one, but I had to struggle to keep an overview here and there😅. Here is how the two modules that make up the device look like: 

![alt text](https://github.com/Adrian-Winter/MuteGroupExeptOne/blob/main/MuteGroupExeptOne.png)

## Feedback 
* Please feel free to let me know if you have trouble getting the results you are looking for. 
* Also what features could be added? 

### Hope this little device made your project a little bit easier! ☺️



