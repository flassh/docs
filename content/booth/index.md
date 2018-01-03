---
date: 2016-05-04T21:13:53Z
title: Flassh Booth
---

## System requirements

* Windows touch-screen tablet running a full version of Windows 10. Windows RT-based tablets are not supported.
* 2GB RAM

## Download and install

### Flassh Connect

Flassh Connect is bridge software between your Canon DSLR camera and the Flassh Booth software. It handles all interactions with the camera hardware. [Download now](https://www.flassh.co/download/connect/windows/latest)

### Flassh Booth

Flassh Booth is the Windows-based application where your photo booth runs. It is the interface that guests interact with when taking photos at your event. [Download now](https://www.flassh.co/download/booth/windows/latest)

#### Why do I need to download two apps?

We know it's not ideal to need both, and we're looking into the possibility of combining them into a single application. In the meantime, you'll need both to run an event. Sorry!

## Sign in

In order to use Flassh Booth, you must sign into your account. If you don't already have an account [create one here](https://www.flassh.co/signup). When you open Flassh Booth for the first time, a login form will pop up. Enter your email address and password to login. Forgot your password? [Reset it here](https://www.flassh.co/passwords/new).

## Supported Cameras

At this time, we **only** support the following Canon and Nikon DSLRs. Sony and other camera brands/models are **not supported**.

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
* EOS-1D X Mark II / EOS 80D / EOS Rebel T6 / EOS 1300D / EOS Kiss X80
* EOS 5D Mark IV
* EOS Kiss X9i / EOS Rebel T7i / EOS 800D / EOS 9000D / EOS 77D
* EOS 6D Mark II / EOS Kiss X9 / EOS Rebel SL2 / EOS 200D

### Supported Nikon camera models

* D3
* D3S
* D3X
* D4
* D4S
* D5
* D90
* D300
* D300S
* D500
* D600
* D610
* D700
* D750
* D800
* D810
* D810A
* D5100
* D5200
* D5300
* D5500
* D5600
* D7000
* D7100
* D7200

## Connection troubleshooting

### Ensure you're using a supported camera

We support [a variety of Canon and Nikon DSLRs](#supported-cameras) connected over USB.

### If you're using a USB adapter, make sure it's an OTG adapter

If your tablet doesn't have a full-size USB port, you're probably using an adapter to convert the full-size USB connector to a mini, micro, or USB-C connector. Ensure you're using an On-The-Go (OTG) cable/adapter, as this type of adapter ensures the signal is properly converted. Adapters that are not explicitly labeled as OTG may not work. [Here's an example adapter cable](https://www.amazon.com/dp/B00LN3LQKQ/) that is known to work well.

### Disable auto-play

Windows has a built-in feature that is often configured to auto-open its Photos (or another) application. This hijacks Flassh's ability to control the camera when it is connected.

The easiest approach is to disable auto-play entirely, which you can see how to do [here](http://www.thewindowsclub.com/set-autoplay-defaults-windows-10).

### Disable WiFi on WiFi-enabled cameras

The WiFi setting on cameras that have WiFi capability (such as the Canon 80D) _must_ be disabled. Canon disables USB functionality entirely when WiFi is enabled on the camera. WiFi can be disabled from the camera's on-screen menu. Once WiFi is disabled, connect the camera to the tablet via USB and it should be detected.

## Camera configuration

We've found that to best way to run a photo booth is to use a flash. With a flash, you can achieve a more consistent image during the day or night. We recommend a small aperture (higher F stop), which will create a larger depth of field, making as much of the photo in focus as possible. Choose a shutter speed close to the sync speed of your flash (usually 1/160 of a second) to keep the image sharp when people are moving and will also minimize the amount of ambient light in the photos. For the flash settings, we recommend using a high-power setting to achieve a proper exposure since your image with out the flash will most likely be completely black. This method will also give you more consistent color and look whether inside or outside, day or night.

Example values to use as a starting point with the use of a flash:

* Aperture: F16
* Shutter Speed: 1/160
* ISO: 400
* Flash set on the higher end (more powerful)

For some situations, a flash might not be available, no problem! In this case you will need to change the camera settings to allow more available light in. You should set a larger aperture (lower F stop), and you may want to turn up your ISO (800-1600) for indoor events. Keep in mind that the higher the F stop, the larger the area that will be in focus in the image. the lower the F stop, the more blurring you'll see when objects move out of your in-focus point.

Ambient Light (indoor) Example Settings:

* Aperture: F4
* Shutter: 1/100
* ISO: 800-1600

Ambient Light (outdoor) Example Settings:

* Aperture: F10
* Shutter: 1/200
* ISO: 200

For photo quality, we support any JPEG-only setting. We do not support RAW capture and you must not choose a JPEG+RAW setting. You may notice that the larger the JPEG setting, the longer it takes to fetch the image from the camera to display the preview. Choose a size that makes the most sense for you and your clients.

We highly recommend you **do not rely on auto-focus during your event**. Use auto or manual focus to get things in focus before the event begins, then **switch it to manual focus**. If you use auto-focus for each photo taken (especially when using a high-powered flash), there may not be enough light for the camera to auto-focus at all, which will cause the capture to timeout and an error to display on-screen. Even if it is able to focus successfully, it can take up to a second to do so, which will throw off the timing of the booth countdown.

**Note: when Flassh fetches photos from the camera, photos are resized to 2560px wide prior to upload to our servers. This ensures fast, consistent upload and photo processing speeds with a high enough resolution for most uses. If you need higher resolution images, they are always available on the SD card in the camera.**

### Camera date and time

Make sure your camera's date and time are correct and that the time matches the current time in your organization's timezone. Mismatched organization timezone and camera settings can cause odd behavior as we rely on the date/time in each photo's EXIF metadata. [Learn more about changing your account's timezone]({{< relref "web/index.md#change-timezone" >}})

If you're using multiple booths (multiple cameras) in a single event, make sure the cameras are synced as close to the second as possible. If they're not the same (or very close), photos will not appear in their expected sequence in the app and online galleries.

## Connect your camera

With Flassh Connect open in the background, Flassh Booth open in the foreground, and your [supported Canon DSLR](#supported-cameras) powered on and connected, you'll see camera info at the top of your screen (vendor, model, as well as aperture, shutter speed, and ISO). If you've gotten to this point, you're ready to run an event!

## Create New Event

Before you can run the booth, you must create an event. An event is a named and dated collection of photos that you own in your account. Your account can contain an unlimited number of events.

To create a new event, tap the "+ Create new event" button at the top of the screen. An event name and date are required, all other fields are optional. [Learn more about event settings]({{< relref "events/index.md#event-settings" >}})

## Run an event

To start your event, ensure the event you want to run is selected in the left pane and tap the "RUN" button in the upper right. Unless your event is currently live, you're prompted to do one of two things "Convert To Live" or "Continue Testing".

Every event you create is a "Test" event by default. See our [pricing info](/#understanding-pricing) for more information about the difference between Test and Live events.

If you're ready to begin your live event and have a paid credit deducted from your account, choose "Convert To Live". Otherwise, tap "Continue Testing".

Regardless of your selection above, you'll be taken to the "Touch Screen To Begin" screen in full-screen mode. Tapping anywhere on the screen will initiate a 3-second countdown, which will trigger the camera, preview the photo, then start another countdown. By default, there are 3 photos taken (3 countdowns) per session. This number is [configurable in event settings]({{< relref "events/index.md#event-settings" >}}).

As photos are taken, they're automatically uploaded to our servers and made immediately available for viewing and sharing. Enjoy your event!

## Exit a running event

Once you're running an event, the tablet goes into full-screen mode and there is no obvious way to exit (this is by design). Guests shouldn't be able to exit, but you'll need to.

Each of the four corners of the screen accept a single-finger long-press gesture that will allow you to exit the event and return to your event management screen.

## Internet requirement

Flassh is a live, online, instant-sharing platform. **To run events effectively, an Internet connection is required**. Some features may work without an Internet connection, but most of our applications operate under the assumption that a stable connection is available.

If a WiFi or wired Internet connection is not available at your event's location, we recommend using a cellular hotspot (mifi) or the tethered data feature of your phone or tablet.

## Printing

We have built-in support for thousands of AirPrint-enabled printers, allowing you to [print from our iOS application]({{< relref "ios/index.md#printing" >}}).
