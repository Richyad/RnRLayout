# RnRLayout
A sample layout that might appear in an app where users like images of their interests. This interface features a background image from Mega Man Star Force and a "Like" button at the bottom of the Activity.

I had the idea for this layout after completing the first lesson of Google's Android Basics course on Udacity. I already covered the basics of building interfaces via an XML file. I used a RelativeLayout ViewGroup since it has attributes that enable positioning Button Views in an Activity.

For the background, I selected an image from my personal Mega Man wallpaper gallery. I cropped the portion of the image containing Mega Man. The new tall, vertical image would fit nicely on the screen of an Android phone in Portrait mode.

Despite my original concept, I added a brief description of my work in a TextView View at the top of the Activity. I felt it would be interesting to add a sentence or two about why I started this project.

The button wasn't meant to be anything too flasy. I felt it would take away from the overall art of the background. I wanted the width to wrap to the size of the screen. A height tall enough that users could reach it with the thumb of the hand holding the phone, or use their other index finger if they so choose.

The background colors were chosen based on the overall color scheme of Mega Man in this image. I chose colors from compatible color swatches I found in the Color section of Google's Material Design website https://material.io/guidelines/style/color.html#

There are a lot of colors displayed in the background, but the focus is on him. Choosing colors close to Mega Man further emphasizes the focus and remains visually appealing. 
Interestingly enough, my idea for the TextView View did not come to me until after adding the button. Once I added it in and saw it with default colors, I had to adjust the colors.

After setting the same light blue/green text and blue background as I used in the Like button, I found the TextView View now blocked parts of Mega Man's helmet and hair. I did some research and found it's possible to adjust the opacity of a color by adding a value from 0 to 100 to the start of its hexadecimal value. After doing some experimenting, 75 seemed the ideal value to provide enough visibility for both the background and my description.

Though the idea seemed simple, the research and development that went into this app took me a few hours. It was worth it 100%. I learned a few tricks of the trade through my mistakes and got some new skills under my belt. I'm looking forward to all the challenges on my road to Android Development!
