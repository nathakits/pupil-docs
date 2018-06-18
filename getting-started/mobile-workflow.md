+++
date = "2018-06-18T12:24:57+07:00"
title = "mobile workflow"
section_weight = 1
page_weight = 3
+++

## Mobile Workflow

Pupil Mobile is an Android app used with the Pupil Headset. The app reads the video streams coming in from the world camera and the eye camera. Pupil Mobile uses the video streams to detect your pupil, track your gaze, record video and events, and stream data in realtime.

Pupil Mobile is a companion app to Pupil Capture and Pupil Service. It is currently in public beta.

### 1. Get app

The app is free. You can download it in the [Google Play Store](https://play.google.com/store/apps/details?id=com.pupillabs.pupilmobile).

### 2. Connect Pupil Headset

Connect your Pupil Headset with your Android device via the USB-C cable provided.

### 4. Record

> {{< webp-img figure-class="img-s" src="/images/pupil-mobile/pupil_mobile.webp" alt="Pupil Mobile Home Screen" >}}

You can record and save the recording locally on your device. Press the circular icon at the bottom of the screen to start recording.

<aside class="notice">
Note - You may need to <strong>enable</strong> USB OTG on some devices in order to allow data transfer and power to your device
</aside>

### 5. Check local recording

> {{< webp-img figure-class="img-s" src="/images/pupil-mobile/local_recording.webp" alt="Pupil Mobile Local Recordings Screen" >}}

Swipe right from the Home screen to see all your recordings on your device.

### 6. Post-Hoc Analysis

Perform pupil detection, gaze estimation, calibration - post-hoc with Pupil Player.

Move your file onto your machine and drag the dataset folder onto Pupil Player to start anaylsis.

#### Offline Pupil Detector

> <h5 align='center'>Offline pupil detection and gaze mapping<h5>
> {{< video-youtube embed-url="https://www.youtube.com/embed/lPtwAkjNT2Q" >}}

This plugin is especially relevant for recordings made with Pupil Mobile, because Pupil Mobile does not perform any pupil detection or gaze estimation on the Android device.

The plugin tries to load the eye0.mp4 and eye1.mp4 videos, and runs the pupil detection algorithm in separate processes.

#### Offline Calibration

> <h5 align='center'>Offline gaze mapping with natural features<h5>
> {{< video-youtube embed-url="https://www.youtube.com/embed/wVOqJWel0K0" >}}

This plugin enables you to (re)calibrate, set calibration sections, and (re)map pupil to gaze positions.

The plugin tries to load the eye0.mp4 and eye1.mp4 videos, and runs the pupil detection algorithm in separate processes.