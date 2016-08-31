# HoursWasted
Time tracking app for personal use

## Overview
HoursWasted is a simple Windows application that tracks how I use my time everyday. Let's say that I've allocated 8 hours of my time everyday dedicated to learning something new. I'd like to know how much time exactly did I use to actually doing the learning instead of wasting my time by procrastinating.

## Idea
The idea is simple. Say I want to read an ebook for 2 hours. I tell HoursWasted which pdf reader I'm using, for this example I'll use SumatraPDF. When HoursWasted starts tracking time, it will catch the foreground application and check whether or not it is SumatraPDF, if it is, time ticks, if not, time wasted will be accumulated. The rationale is, sometimes I tend to ALT+TAB to Google Chrome and surf Facebook. HoursWasted is designed to track those behavior to make guilt trip myself :P

## Features
1. Allows me to specify a task and an associated application name
2. Tracks productive time when the specified application is running on foreground
3. Tracks wasted time when the specified application is running on background
4. Dashboard of statistics (and possibly generate a report)

## Disclaimer
This project is just for fun because I'm bored and have nothing better to do. If there's any application out there that has the same concept, it is entirely coincidental. Although I must admit this is inspired by WakaTime.
