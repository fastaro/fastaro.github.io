---
layout: post
title:      "Key Take aways from CNNs"
date:       2019-12-13 20:23:42 +0000
permalink:  key_take_aways_from_cnns
---

Convolutional Nueral Networks are useful for classifying objects that can be defined by their topology.  The reults arent very interpretable  but they are powerful.  CNNs use convolution to detect lines and edges.  One issue with CNNs is that they require a tensor thats a fixed size.  This makes them good at dealing with images but not with time series information.
Audio does have topological properties.  Sound produces pressure waves at various frequencies.  With a fourier transform - these can be visualized geometrically.  Ok, but now we have another problem - audio samples come in different amounts of time.  The way to make it interpretable to a CNN is to either - take the sample amount of time of each sample - or - you can average the amplitude of the frequencies - so every imported sample is a single array value of frequncies.
This is what I did categorize drum samples.  Because drum samples are shorter - there is less room for errors via averaging over a long time period.  I got an overall weighted average of 98%.
For my next project it will be cool to try the same thing but with LSTMs.
