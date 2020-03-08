---
layout: post
title:      "AutoEncoders and Anomoly Detection"
date:       2020-03-08 01:28:22 +0000
permalink:  autoencoders_and_anomoly_detection
---


There's a new unsupervised learning technique in town and they're called AutoEncoders.  AutoEncoders are a strange mix of supervised and unsupervised learning - allow me to explain:  They work by training data only of a specific kind such hand writing images of the number '4' or regular air port travellers going about their buisness.  Their goal is to reduce the demensionality of the data and then reconstruct it with a minimum reconstruction error.  So why is this useful for anomoly detection?  Well, if you put the number '5' inside an algorithm that's only been trained on the number '4' - the reconstruction error will be HIGH.  This same principle could work to stop criminals and trafficers - by detecting patterns that we may not be aware of yet.  This is one new application of unspervised learning that will be very useful in the future.
