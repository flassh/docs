---
date: 2016-05-04T21:13:53Z
title: Flassh Booth
---

## System requirements

* Windows touch-screen tablet running Windows 8 or later (Windows 10 recommended)
* 2GB RAM

## Download and install

### Flassh Connect

Flassh Connect is bridge software between your Canon DSLR camera and the Flassh Booth software. It handles all interactions with the camera hardware. [Download now](https://flassh.co/download/connect/windows/latest)

### Flassh Booth

Flassh Booth is the Windows-based application where your photo booth runs. It is the interface that guests interact with when taking photos at your event. [Download now](https://flassh.co/download/booth/windows/latest)

#### Why do I need to download two apps?

We know it's not ideal to need both, and we're looking into the possibility of combining them into a single application. In the meantime, you'll need both to run an event. Sorry!

## Sign in

## Supported Cameras

At this time, we **only** support Canon DSLRs. Nikon, Sony, and other camera models are **not supported**.

### Supported Canon camera models

* EOS-1D Mark III
* EOS 40D
* EOS-1Ds Mark III
* EOS DIGITAL REBEL Xsi / 450D / Kiss X2 EOS DIGITAL REBEL XS / 1000D / KISS F EOS 50D
* EOS 5D Mark II
* EOS Kiss X3 / EOS REBEL T1i / EOS 500D
* EOS 7D
* EOS-1D Mark IV
* EOS Kiss X4 / EOS REBEL T2i / EOS 550D
* EOS 60D
* EOS Kiss X5 / EOS REBEL T3i / EOS 600D
* EOS Kiss X50 / EOS REBEL T3 / EOS 1100D
* EOS 5D Mark III
* EOS 1D X
* EOS Kiss X6i / EOS 650D / EOS REBEL T4i
* EOS 6D
* EOS-1D C
* EOS Kiss X7i / EOS 700D / EOS REBEL T5i
* EOS Kiss X7 / EOS 100D / EOS REBEL SL1
* EOS 70D
* EOS Kiss X70 / EOS 1200D / EOS REBEL T5 / EOS Hi
* EOS 5DS / EOS 5DS R / EOS REBEL T6s / EOS 760D / EOS 8000D / EOS REBEL T6i / EOS 750D / EOS Kiss

## Camera configuration

We recommend a small aperture and a fast shutter speed camera configuration with a high-powered flash. This keeps as much as possible in focus and ensures that changes in light (sunlight / event lighting) over time do not cause drastic changes in photo consistency.

Example values to use as a starting point:

* Aperture: F10
* Shutter Speed: 1/160
* ISO: 400

For photo quality, we support any JPEG-only setting. We do not support RAW capture and you must not choose a JPEG+RAW setting. You may notice that the larger the JPEG setting, the longer it takes to fetch the image from the camera to display the preview. Choose a size that makes the most sense for you and your clients.

**Note: when Flassh fetches photos from the camera, photos are resized to 2560px wide prior to upload to our servers. This ensures fast, consistent upload and photo processing speeds with a high enough resolution for most uses. If you need higher resolution images, they are always available on the SD card in the camera.**

### Camera date and time

Make sure your camera's date and time are correct and that the time matches the current time in your organization's timezone. Mismatched organization timezone and camera settings can cause odd behavior as we rely on the date/time in each photo's EXIF metadata. [Learn more about changing your account's timezone]({{< relref "web/index.md#change-timezone" >}})

If you're using multiple booths (multiple cameras) in a single event, make sure the cameras are synced as close to the second as possible. If they're not the same (or very close), photos will not appear in their expected sequence in the app and online galleries.

## Connect your camera

With Flassh Connect open in the background, Flassh Booth open in the foreground, and your [supported Canon DSLR](#supported-cameras) powered on and connected, you'll see camera info at the top of your screen (vendor, model, as well as aperture, shutter speed, and ISO). If you've gotten to this point, you're ready to run an event!

## Create New Event

Before you can run the booth, you must create an event. An event is a named and dated collection of photos that you own in your account. Your account can contain an unlimited number of events.

To create a new event, tap the "+ Create new event" button at the top of the screen. An event name and date are required, all other fields are optional. [Learn more about event settings]()

## Run an event

To start your event, ensure the event you want to run is selected in the left pane and tap the "RUN" button in the upper right. Unless your event is currently live, you're prompted to do one of two things "Convert To Live" or "Continue Testing".

Every event you create is a "Test" event by default. See our [pricing info](/#understanding-pricing) for more information about the difference between Test and Live events.

If you're ready to begin your live event and have a paid credit deducted from your account, choose "Convert To Live". Otherwise, tap "Continue Testing".

Regardless of your selection above, you'll be taken to the "Touch Screen To Party" screen in full-screen mode. Tapping anywhere on the screen will initiate a 3-second countdown, which will trigger the camera, preview the photo, then start another countdown. By default, there are 3 photos taken (3 countdowns) per session. This number is [configurable in event settings]().

## Exit a running event

Once you're running an event, the tablet goes into full-screen mode and there is no obvious way to exit. Each of the four corners of the screen accept a single-finger long-press gesture that will allow you to exit the event and return to your event management screen.
