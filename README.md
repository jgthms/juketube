JukeTube
========

A YouTube powered jukebox built with AngularJS.

[![JukeTube screenshot](https://raw.github.com/jgthms/juketube/master/juketube.png)](http://jt.ms/juketube)

## Demo

[http://jt.ms/juketube](http://jt.ms/juketube)

## Purpose

When I attend parties, YouTube is often used as the sole music provider. People in turn launch the video they want to hear. The process goes as follows:

* open a new tab
* browse to YouTube
* search for a video
* open and instantly pause it (to preload it)
* wait for the previous video to stop
* launch their video

Several problems arise from this process:

* need to wait for the current video to stop before launching a new one
* need to permanently have someone queuing and launching a new video
* no automatic play, so if the current video ends, there's no music
* time spent queuing a new video
* tons of tabs opened

## Features

JukeTube is an attempt to simplify this scenario.

* Single page app
* Ajax search
* Playlists (upcoming and archived videos)
* Automatic play (as soon as the current video ends)

## Requirements

You only need a valid YouTube Data API v3 key: [https://developers.google.com/youtube/v3/](https://developers.google.com/youtube/v3/) and paste it in **app.js**.

The Gotham font is used on the demo site but is not provided. Try [Google Fonts](http://www.google.com/fonts) for alternatives.

## Possible enhancements

* Play/Pause/Stop controls.
* Use the YouTube API to retrieve the titles using the ID. Right now, the preloaded video titles are hard-coded.
* Save the current playlist in LocalStorage or a cookie.
* Drag controls to reorder the playlist items.
* Search results pagination
