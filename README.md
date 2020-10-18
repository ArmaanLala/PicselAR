# PicselAR
![picselAR logo](https://github.com/ArmaanLala/Picsel/blob/master/media/logo.png)

## Warning
If using the github files instead of the AR links, beware that we have found a bug with SparkAR that auto resets some values to 0. In order to fix this, click on the backgroundPixel object in the scenes, and then click on properties. Set height and width to 100% Relative. We do not know why this bug occurs and have spoken with Facebook representatives but the filters will not work otherwise.

## Links
Please do not click on these unless you are staff. These links have limited uses as the filters have not been approved yet
Instagram : [Instagram Picsel AR](https://www.instagram.com/ar/348993453109146/?ch=Mjk4YmE5NWMwYTgyOTI5NGY1NTdlYzYyZTUwNjVkZGM%3D)
Facebook : [Facebook Picsel AR](https://www.facebook.com/fbcameraeffects/testit/724031258189625/NTJjNjllZDQ5OTZjMWE3ZjIzM2JiNmUzMTQ0M2MwZmI=/)

## Instructions
We made sure that when we developed the filter, it would be very simple to use. Because Facebook and Instagram have different capabilities, the filters for each platform have different options. When the filter opens, the user has options to chose which method of pixelation they want to use. The instructions for each specific method are below:

### Instagram
Audio Analysis - This method analyzes the data from a spectrum equalizer and automatically pixelates the background if a certain average frequence threshold is exceeded.

Slider - This method is also very intuitive. It just adds a slider on the right side of the screen that the user can modify to a wanted level.

World AR Block - This is the most interesting method of pixelation. This method allows you to an embed an emblem of our logo anywhere in the world. Our filter will remember the location of this object no matter where you look, or if you switch between front and back camera. The only thing you need to keep in mind for this option is that the father away the object, the more pixelated your background will become. 

### Facebook 
Hand Control - This method is both intuitive and fun to allow for creativity! If you put your hand towards the camera, it will further pixelate the background. If you put your hand away from the camera, it will unpixelate the background.
 
World AR Block - This is the most interesting method of pixelation. This method allows you to an embed an emblem of our logo anywhere in the world. Our filter will remember the location of this object no matter where you look, or if you switch between front and back camera. The only thing you need to keep in mind for this option is that the father away the object, the more pixelated your background will become. 


## Inspiration
COVID-19 wrought an onslaught of problems concerning privacy due to the increase in video calls where people are required to share their video. Through creating an initially simple pixelation AR filter, we realized that by adding additional customizations we enable users to utilize their own creativity in making skits specializing in reveals or hiding things.

## What it Does
PicselAR gives users a way to pixelate their background through various means (e.g., hand gesture/slider, distance to a virtual object, and audio level). It also gives rise to skit creation with Instagram Reels as demonstrated above.

#### Hand Gesture/Slider
![hand gesture demonstration gif](https://github.com/ArmaanLala/Picsel/blob/master/media/hand-gesture.gif)

This option grants users the most convenient degree of customization over how their background is perceived. It is most useful if one has no need to pixelate their background or it needs to be pixelated the entire time regardless of the context it is used in.

#### Virtual Object
![virtual object demonstration gif](https://github.com/ArmaanLala/Picsel/blob/master/media/block-effect.gif)

We believe this option to be the least useful in a professional setting but the one with the most potential for creativity. Users can place an object somewhere in a virtual 3D space and the camera's distance to it determines the background's pixelation. This feature could be used in creating short horror skits when paired with a dark environment or for creating skits that involve movement.

#### Audio Level
![audio level demonstration gif](https://github.com/ArmaanLala/Picsel/blob/master/media/sound.gif)

While it cannot be easily conveyed through a visual format, if the user's microphone picks up audio above a certain threshold, the background will be pixelated as much as possible. We envision this being used to prevent a person's home life being exposed in case someone begins yelling or barges in to their room. On the more light-hearted side of things, it could be used in a skit in which someone attempts to hide something from someone.

## How We Built it
We build PicselAR using Facebook's Spark AR software. Within Spark, we were able to use all of the different tools to isolate our background and then learned how to use Spark's specific patches to manipulate all of our data.

## Challenges We Ran Into
We realized that Spark AR has no way of saving values so we had to find a way to implement a finite-state machine into our patch editor to get around this issue. We also ran into various issues with regards to a new bug we discovered that reset some of our values every time we decided to run either of our projects.

## Accomplishments We're Proud of
We are extremely proud of being able to produce two seperate build of our applications. We were able to provide exclusive features to both platforms but still made them similar and were able to incorperate World AR into both of them.

## What We Learned
We learned all about how to use various aspects of Spark AR in order to isolate different objects and layers. Furthermore, making a filter required a lot of skills outside of actually programming, which is all we really expected to do be doing. For example, we had to use Blender and Asperite to make the assets for the project. We also learned how to work efficiently together with a project outside of our comfort level (which is all we could ask for)!

## What's Next For 【PicselAR】
We wish to continue to build out this idea so it's perfect for our friends to use. Furthermore, we would love to show off our filters to our followers and see what they can think up with it, afterall, that's the most important part of making a project like this.

Thank you for checking out our project!

