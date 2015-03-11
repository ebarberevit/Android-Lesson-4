# Hack101: Android - Lesson 4 #

### Intro And Setting Up 

Hello, and welcome to the 4th Android Hack 101. We will be covering the basics of designing a UI in Android.

Today will be a bit different from previous Hack101 tutorials. I'm not a strong believer in the lecture format for a variety of reasons. As a result, this will be a lecture-lite sort of Hack101. Additionally, this Hack101 will be slightly different from previous Hack101s in that it focuses on design rather than programming. We will be covering the absolute basics of designing a UI in Android Studio - so if any of you  have any experience doing this, then chances are you will not get much out of the lecture part of this tutorial.

I say lecture part, because this tutorial is actually divided into two parts. The lecture part, which we will go over as fast as possible, and a competition with a prize for the winner.

But more on that later.

### Android Studio ###

Let us start.  Don't worry about keeping notes or anything. Just try to follow along as best as you can - a lot of this stuff is common sense, and if you have any experience with HTML or Photoshop I am sure this will all be second nature to you.


Today we will be working on a ________. Previous Tutorials by Amiel covered intents, listeners, and generally everything you would require to make an actual interactive app. Today will be putting on our designer cap and will not be worrying about any of those things. 

So. First we are going to start up Android Studio. Click new project. Name the Application __________, enter a new location if you are so inclined. Click next.

Choose Phone and Tablet, and make API 15 the minimum SDK. A lower SDK means it will be compatible with more devices, since new devices are backwards compatible with older versions of Android, but not vice-versa since that might violate our idea of causality. 

Here, we are presented with a list of activities.

At its core, an Android App is a collection of connected classes called Activities. Each Activity has a life cycle when it is created, resumed, paused, stopped, and killed. Only one Activity is running at one time, and we can freely switch between them using classes called Intents. Activities and Intents were covered in the second tutorial. You won't need to worry about them too much at the moment, because we are focusing on a set of objects that come from the View class.




![Activity Life Cycle](http://www.vogella.com/tutorials/AndroidLifeCycle/images/xactivity_lifecycle10.png.pagespeed.ic.fPEkTDwujN.png)



Sources:

http://www.vogella.com/tutorials/AndroidLifeCycle/article.html#managingapplicationlifecyle

http://developer.android.com/guide/components/activities.html