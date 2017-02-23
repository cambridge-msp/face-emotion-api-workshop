# Face and Emotion API Workshop

This is a simple app designed to showcase the capabilities of the Microsoft Cognitive Services Face and
Emotion APIs. It is being used as part of the Cambridge University Microsoft Student Partners' workshop on
the Cognitive Services Face APIs.

## Prerequisites

If you just want to watch how to build an app with Cognitive Services just come along! If you want to follow along with the coding then make sure you have the following.

1. Proficiency in Java. Understanding of the Observer deisgn pattern desirable.
2. A working installation of [Android Studio](https://developer.android.com/studio/index.html).
3. Some way to run Android apps. A physical Android device connected over USB is desirable (_don't forget your USB cable!_), otherwise an emulator will do.

Windows, Mac OS and Linux are all acceptable.

## Preparing for the Workshop

If you just want to watch how to build an app with Cognitive Services just come along!

If you want to follow along with the coding then make sure you have the following. __It is highly recommended you do this before coming along.__

1. Make sure you have Git installed. If not, follow instructions [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
2. Clone this repository by typing this command: `git clone https://github.com/cambridge-msp/face-emotion-api-workshop.git`.
3. Navigate to the project directory: `cd face-emotion-api-workshop`.
4. Open Android Studio. Open this project - it is in the directory mentioned in point 3. It is likely that Android Studio will complain that the correct SDK version is not installed: _install the SDK_ by following the instructions if so.
5. It is likely Android Studio will say the project requires a Gradle Sync. Follow the instructions to sync the project.
6. Checkout the workshop branch: `git checkout workshop`.

If you don't want the "workshop version" but would rather see the complete version, do `git checkout master` at any point. To return to the workshop version, do `git checkout workshop`. (See below for details on the "workshop version").

## Workshop Version

This repository contains two branches.

### `master`

This branch contains a fully working implementation of the app.  This is a very thoroughly documented and stable
version of the app following Android good programming practices. It is good for looking over to see how a
complete implementation works.

### `workshop`

This branch contains gaps in the code which are suitable for being filled in during a workshop
to demonstrate how easy it is to integrate Emotion API into apps. It is deliberately designed to ensure
that it requires no knowledge of Android specific APIs by ensuring the Android specific parts are already
implemented.

Note that it does __not__ build!

## Slides

Slides and a recording of the workshop will be added after it is run.

## About the Presnetation

The original presentation is being given by Henry Thompson and David Adeboye on Friday February 24th 2017.
