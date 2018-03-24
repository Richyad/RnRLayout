# RnRLayout
A sample layout that might appear in an app where users like images of their interests. This interface features a background image from Mega Man Star Force and a "Like" button at the bottom of the Activity.

<!-- 1. Create a layout -->
I had the idea for this layout after completing the first lesson of Google's Android Basics course on Udacity. I already covered the basics of building interfaces via an XML file. I used a RelativeLayout ViewGroup since it has attributes that enable positioning Button Views in an Activity.

<!-- Use a RelativeLayout to position the button later -->

For the background, I selected an image from my personal Mega Man wallpaper gallery. I cropped the portion of the image containing Mega Man. The new tall, vertical image would fit nicely on the screen of an Android phone in Portrait mode.
<!-- 2. Add an image from the series as the background -->

<!-- 6. Use a TextView as the title describing the layout -->
Despite my original concept, I added a brief description of my work in a TextView View at the top of the Activity. I felt it would be interesting to add a sentence or two about why I started this project.

<!-- 3. Add a button at the bottom of the layout that says "like" -->
<!-- Set the Button id, width/height, padding, and weight-->
<!-- Use layout_alignParentBottom xml attribute and assign value "true"-->

<!-- 4. The button must wrap -->
<!-- 5. Use a custom size for the button -->
The button wasn't meant to be anything too flasy. I felt it would take away from the overall art of the background. I wanted the width to wrap to the size of the screen. A height tall enough that users could reach it with the thumb of the hand holding the phone, or use their other index finger if they so choose.


<!-- 7. Customize the background color of the button -->
<!-- 8. Customize the text color of the button -->
The background colors were chosen based on the overall color scheme of Mega Man in this image. I chose colors from compatible color swatches I found in the Color section of Google's Material Design website https://material.io/guidelines/style/color.html#

There are a lot of colors displayed in the background, but the focus is on him. Choosing colors close to Mega Man further emphasizes the focus and remains visually appealing. 
Interestingly enough, my idea for the TextView View did not come to me until after adding the button. Once I added it in and saw it with default colors, I had to adjust the colors.

After setting the same light blue/green text and blue background as I used in the Like button, I found the TextView View now blocked parts of Mega Man's helmet and hair. I did some research and found it's possible to adjust the opacity of a color by adding a value from 0 to 100 to the start of its hexadecimal value. After doing some experimenting, 75

    <Button
        android:background="#03A9F4"
        android:id="@+id/like_button"
        android:layout_width="fill_parent"
        android:layout_height="100dp"
        android:padding="10dp"
        android:layout_alignParentBottom="true"
        android:text="Like"
        android:textAllCaps="false"
        android:textColor= "#84FFFF"
        android:textSize="20sp"
        />

</RelativeLayout>



<!--

    <TextView
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="Choose a celebrity, see a quote!"
        android:padding="10dp"
        />
    <Button
        android:id="@+id/RevX"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="Reverend X"
        android:background="@color/colorAccent"/>
    <Button
        android:id="@+id/Shannon"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="Shannon Sharpe"
        android:background="@color/testBlue"
        android:textColor="@color/colorAccent"/>
    <Button
        android:id="@+id/Yeezy"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="Kanye West"
        android:background="@color/colorAccent"/>

    <Button
        android:id="@+id/Homer"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/testBlue"
        android:text="Homer Simpson"
        android:textColor="@color/colorAccent" />
--> 
