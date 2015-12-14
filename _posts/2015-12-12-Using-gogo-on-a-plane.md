---
layout: post
title: Using Gogo and wifi on a plane
author: Richard Sprague
tags:
- travel
categories: technology
---
After reading
[an excellent overview of inflight wifi](http://thepointsguy.com/2015/11/how-in-flight-wi-fi-works/),
I decided to try a few experiments on my flight this week to New
Orleans.

# Summary
T-Mobile free in-flight texting works great. It was quick and easy to set up on my iPhone, and everything worked just as I’d expect on the ground, including photos.  The experience was even better when logged in to the gogoinflight network, when I was able to use full internet (including VPN) on either my phone or laptop at speeds between 0.1 and 0.5 Mbps.

# Setup
I connected my iPhone 6S to the gogoinflight network within a few minutes after the plane had passed the magic 10,000 foot level and the announcer said it was okay. Because there were no instructions it took me some time to figure out that I need to launch my phone browser and try to open a page so it can automatically redirect to the Gogo inflight provisioning screen.

The main screen includes  “free” sign for the T-Mobile
messaging. Interestingly, you can buy a $5 messaging package for other
carriers, but they explicitly don’t allow photos (MMS). I tested
sending a photo with my T-Mobile account and it worked fine, both
ways. Speed wasn’t great — maybe five minutes? — but hey it’s not
always that fast on the ground either.

<a data-flickr-embed="true"
href="https://www.flickr.com/photos/sprague/23081366943/in/album-72157659312996283/"
title="Untitled"><img
src="https://farm6.staticflickr.com/5731/23081366943_c1d1b436b1_z.jpg"
width="360" height="640" alt="Untitled"></a><script async
src="//embedr.flickr.com/assets/client-code.js"
charset="utf-8"></script>

Connecting to Gogo Inflight was pretty easy too. I needed to set up an
account including a username/password, but it was all quick and easy.

# Speed
I tested the Gogo service several times at different parts of the flight. It wasn’t fantastic, but definitely usable for basic surfing purposes.

* Downloads were reasonable: 0.5Mbs.
* Upload was very slow: 20kps or so.
* Ping time (latency) was between 300 and 600ms.  Not great, but usable.

Here it is over my VPN, ironically slightly faster than the naked
connection, although that was probably due to the big variation in
speeds at different parts of the flight.

<a data-flickr-embed="true"
href="https://www.flickr.com/photos/sprague/23340489919/in/album-72157659312996283/"
title="Untitled"><img
src="https://farm1.staticflickr.com/692/23340489919_c65df75ee3_z.jpg"
width="360" height="640" alt="Untitled"></a><script async
src="//embedr.flickr.com/assets/client-code.js"
charset="utf-8"></script>

Here it is on my laptop:

<<<<<<< HEAD
![gogo wifi speed on a laptop]({{ site.url }}/assets/151212gogospeedlaptop.png)
=======
![gogo wifi speed on a laptop]({ {site.url }}/assets/151212gogospeedlaptop.png)
>>>>>>> 9a2ee88cec3ae31227f1012ccf0c15554a67ed87

Phonecalls: even after I had paid for the full Gogo service, and even through a VPN, it wouldn’t let me make wifi calls. I’m not sure how they prevent this, because with VPN the Gogo people don’t even know that I’m trying a phonecall. It might be something on my phone, maybe, that prevents calls unless the wifi speed is greater than something.

#Messaging

Tweeting works: I had no trouble sending an SMS to Twitter, where it was reposted to my Twitter account. Nice!

Speed was nearly instantaneous: I could send SMS and get a reply within seconds.

MMS worked too: I was able to send photos, though it was somewhat unreliable.  I had to send twice in once case.

#Where’s the Internet coming from?

At first I thought maybe this was a cellular-based air-to-ground
system, instead of something requiring a satellite
connection. Throughout the flight it showed my IP address and location
as something in Kansas:

<a data-flickr-embed="true"
href="https://www.flickr.com/photos/sprague/23687613956/" title="gogo
upload map"><img
src="https://farm6.staticflickr.com/5680/23687613956_fa833cf566_z.jpg"
width="640" height="553" alt="gogo upload map"></a><script async
src="//embedr.flickr.com/assets/client-code.js"
charset="utf-8"></script>

If it had been cellular, I would have expected the location to change throughout the flight but it didn’t. So I guess it’s something satellite-based (Gogo uses satellite systems).

#Entertainment
Alaska Airlines doesn’t bother with inflight video displays. You either bring your own screen or you rent one for $10 (a fairly rugged Windows-labeled tablet they’ve had on the planes since January). The “Flight Amenities” guide in the seat pocket gives instructions for how to log in for free to the gogoinflight network. (nothing on there about free text messaging, though).

I forgot to test whether and how they block access to video services like Netflix or even Youtube. Due to the slow and variable speeds, I bet the experience isn’t very good even if it can technically connect.

#Customer Support
I couldn’t figure out how to swap the internet service from my phone to my laptop, so I opened the customer support chat window on a browser. Response was pretty quick: less than a minute or two.  The representative told me that my pass was valid only on a smart phone, and that I would have to pay the difference to use it on a laptop.  But she was super-nice about it and offered me a free pass so I could switch. The new pass let me log into either my phone or the laptop (but not both) and was good for the rest of the flight (but not the entire day).
