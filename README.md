# RnRLayout
A sample layout that might appear in an app where users like images of their interests. This interface features a background image from Mega Man Star Force and a "Like" button at the bottom of the Activity.

<!-- 1. Create a layout -->
I had the idea for this layout after completing the first lesson of Google's Android Basics course on Udacity. I already covered the basics of building interfaces via an XML file. I used a RelativeLayout ViewGroup since it has attributes that enable positioning Button Views in an Activity.

<!-- Use a RelativeLayout to position the button later -->


For the background, I selected an image from my personal Mega Man wallpaper gallery I felt would best 
<!-- 2. Add an image from the series as the background -->
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent"
    android:background="@drawable/battle_cards"
    >

<!-- 6. Use a TextView as the title describing the layout -->
	<TextView
		android:background="#7503A9F4"
		android:layout_height="wrap_content"
		android:layout_width="fill_parent"
		android:text="Just wanna flex my newly gained skills in creating User Interfaces and show my love for the Mega Man Star Force series. (What is dead may never die)"
		android:textColor="#84FFFF"
		android:textSize="16dp"
		android:padding="10dp"
	/>

<!-- 3. Add a button at the bottom of the layout that says "like" -->
<!-- Set the Button id, width/height, padding, and weight-->
<!-- Use layout_alignParentBottom xml attribute and assign value "true"-->

<!-- 4. The button must wrap -->
<!-- 5. Use a custom size for the button -->
<!-- 7. Customize the background color of the button -->
<!-- 8. Customize the text color of the button -->

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
