---
date: 2016-05-04T21:13:53Z
title: Flassh Web Galleries / Admin Area
---

## Change organization name

Your organization name is the name that is shown as the owner of your events and is visible to anyone browsing your galleries on the web or on their own devices. When someone shares one or more photos via email, the "From" name of that email will be the name you set here.

If you're a solo photographer, it may make sense for this to be your full name so people can find your events. If you are a company, you'll want to use your company's name here.

To change your account's timezone, go to the [Profile tab](https://flassh.co/account/profile) in your account. Find the "Organization Settings" section and tap the "Edit Organization" button. Enter your organization's name and tap the "Save Organization Info" button.

## Change name or email address

The name and email you use is private within your organization. We use them to communicate you for support tickets and billing, but no one else sees these, and they will never be shown in any event information. This lays the groundwork for allowing multiple users and logins within a single organization (which is not yet available).

To change your name or email, go to the [Profile tab](https://flassh.co/account/profile) in your account. Find the "My Info" section and tap the "Edit My Info" button. Modify your name and/or email and hit the "Save My Info" button. It's important that your email is valid, as this is how we contact you.

## Change password

Make sure you choose a strong password! Your email and password combination allow complete, read/write access to all events, photos, and settings in your account. You can change your password at any time.

If you have access to your account and need to change your password, go to the [Profile tab](https://flassh.co/account/profile) in your account. Find the "Password Settings" section and tap the "Change Password" button. Enter your old password and a new password (with a confirmation) and tap the "Update Password" button.

If you forgot your password, you can reset your password via email on our [password reset page](https://flassh.co/passwords/new). We'll email you a message containing a link that will allow you to reset your password.

**Note:** changing your password does not revoke access on your other signed in devices.

## Change timezone

It's important that your timezone lines up with the time you have set on your camera. If you travel, we recommend maintaining a consistent timezone in your account and always using that timezone's time when configuring the date/time on your camera.

To change your account's timezone, go to the [Profile tab](https://flassh.co/account/profile) in your account. Find the "Organization Settings" section and tap the "Edit Organization" button. Select your timezone and tap the "Save Organization Info" button.

## Configure a gallery subdomain

Each account is configured with a web gallery that contains all events owned by that organization. By default each account is assigned a random subdomain, one that is likely not memorable and is not representative of your organization's name or brand. To change it, go to the [Profile tab](https://flassh.co/account/profile) in your account. Find the "Public Gallery" section and tap the "Edit Gallery URL" button.

You're prompted to specify a subdomain. Choose a subdomain that is 6 characters or more, starts with a letter, and only contains numbers and letters. For example, specifying "photos" will give you a public gallery URL of https://photos.flassh.co.

Note, when you change this subdomain, any existing links to your web galleries will break, and the new URLs will take effect immediately.

Fully custom domains (photobooth.yourdomain.com) are not currently supported.

## Watermarking

Many events are associated with a one or more companies/brands you may want to promote in your photos. From the [Watermark tab](https://flassh.co/account/watermarks) you can upload an unlimited number of watermarks to your account for use in your events.

### Preparing watermarks

A watermark file is typically a mostly-transparent PNG except for the area of the image that you want to add the watermark. To prepare a watermark for Flassh, create a new file that is 5148px (wide) x 3456 (tall) with a transparent background.

We recommend dropping a photo (should also be 5148x3456px) in as a layer behind your watermark when preparing the watermark. Don't forget to hide the photo layer though before you export the PNG!

There are no limitations on how you can design your watermarks. Be careful though, you don't want to cover people's faces! It's best to stick to the bottom left and right edges. If the mark is small enough, you can get by putting them in the top left/right as well, but the top of people's heads may get covered.

#### Why the arbitrary file size?

This ensures we have a large enough version of your watermark to scale to any possible needed size. We're almost always scaling it down for shared photo versions, but want to make sure we're able to use the same watermark files now and well into the future (as image resolutions continue to increase).

### Uploading watermarks

Head to the [Watermark tab](https://flassh.co/account/watermarks) and either drag and drop your watermark file created above or tap the "+ Add New" button and browse to the properly-sized PNG file on your computer.

If you see a preview of your watermark, you're all set. If you receive an error message, check your file format (PNG) and image dimensions (5148x3456px).

### Previewing watermarks

On the [Watermark tab](https://flassh.co/account/watermarks) there are options for previewing your watermark on 3 different background types to help you visualize how it will look for your event.

Tap the "Dark" button (default) to see what the mark will look like on an event with a dark background, "Light" to see it on a bright, nearly-white background, and "Color" to see it on a vibrant, busy, colored background.

### Apply a watermark to an event

At this time, watermarks can only be applied or removed from an event from the [new/edit event screen on iOS](). We're working to bring this functionality to Flassh Booth and to the web admin area.

### Delete a watermark

At this time, it is not possible to delete watermarks. We're working on this and should have an interface for this in the coming weeks.

## Credit card & billing

Once you're ready to run live events, you'll need to enter your credit card information and purchase event credits. There's no pressure to do so and no expiration on your test events, so if you want to keep your free account and continue using test events, you're more than welcome to do so.

### Add credit card

To add a new credit card, go to the [Billing tab](https://flassh.co/account/billing) in your account and tap the "Add Your Card" button. If you already have a card on file, the "Add Your Card" button will not be available. Instead, you'll see a "Edit Card" button.

We accept Visa, MasterCard, American Express, JCB, Discover, and Diners Club cards.

A valid card number, expiration and the CVC (3-4 digits on the back of the card) are required. After you've entered your card info, tap the "Save Credit Card" button.

### Update credit card

To update your credit card or switch to a different one, go to the [Billing tab](https://flassh.co/account/billing) and tap the "Edit Card" button.

After you've entered your updated card info, tap the "Save Credit Card" button. All future charges will be made to this newly specified credit card.

### Credit card security

Any time you enter payment information (such as a credit card or debit card), it's sent over an encrypted connection from your web browser directly to [Stripe](https://stripe.com/) - one of the largest, most advanced payment processors in the world. They handle payment processing for services like Kickstarter, Lyft, Shopify, Pinterest, Twitter, Heroku, SurveyMonkey, and many other companies. Once Stripe receives valid payment information, they then issue us an encrypted "token." We use these tokens to create charges against those credit cards and bank accounts - even though we can't access the full details of those payment methods. We can only fetch the basic information such as the last 4 digits, they type of payment method, its expiration date, and the customer's name. The full account number or CVC number isn't released to us.

## Managing event credits

On the [Billing tab](https://flassh.co/account/billing) in your account, you can always see your current event credit balance. If you have one or more credits, you'll be able to convert events to live. If you have zero credits, you'll only be able to create test events.

**Note: credits must be pre-paid. You cannot convert an event to live without any credits in your account.** We highly recommend configuring billing and adding one or more credits to your account before you head out to your event.

### Buy event credits

You can purchase as many credits as you need from the [Billing tab](https://flassh.co/account/billing) in your account. [Learn more about pricing](/#understanding-pricing)

Before you can add credits, you must [add a credit card]({{< relref "web/index.md#credit-card-billing" >}}) to your account. Once you have a credit card on file, tap the "Add Credits" button.

You are prompted to enter the number of credits you would like to buy. Enter a number and tap the "Buy Now" button to continue, you'll be prompted once more to confirm your purchase. If your card is charged successfully, event credits are added to your account immediately.
