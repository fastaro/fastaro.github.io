---
layout: post
title:      "Building a website with Flask"
date:       2019-12-13 22:26:49 +0000
permalink:  building_a_website_with_flask
---


The first part of making a website work with flask is pretty simple - you write your code, you run the command in the terminal and it works.  The part where it's uploaded on the internet can get complicated fast.  The tutorials on flask dont expcet you to be uploading anything with tensor flow.  So I had to dig deep to find the one thing flask tutorials dont mention,  Apt -Files.  This is what tells Heroku what software packages are required for the website to work.  Another thing that might go over looked is the Procfile.  The Procfile is a simple text file that tells heroku that youre making a web app.  Everything else was basically following the upload file format and only allowing .wav files in the file extensions.  https://intense-oasis-99800.herokuapp.com/
