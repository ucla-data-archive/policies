---
title: "Mapping with Leaflet"
date: 2018-10-28
author: ["Leigh Phan", "Tim Dennis"]
---

Leaflet is an open source tool for developing interactive maps on the web based on JavaScript.

## Setup

    Download Anaconda Python https://www.anaconda.com/download/ - Anaconda python distribution is a package of Python programming language with the most important data science tools. This also includes a web server we will use to run our Leaflet maps.
    Download and unzip Leaflet https://leafletjs.com/download.html. Put somewhere you can find easily (your desktop)
    Download the [project folder](https://programminghistorian.org/assets/using-javascript-to-create-maps/using-javascript-to-create-maps.zip) for the class

Instruction
    Using the `terminal` on Mac and `conda console` on windows, navigate to your working folder. You can do this by entering the command 'cd' followed by the path of your working folder.
    For example: `'cd /Users/YourName/Documents/using-javascript-to-create-maps'`
    Once in your working folder, run `python -m http.server`. This should start a local server to host a Leaflet map, so you will see the server start on the command line.
    During this process, the command line should display text that appears like: "Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ..."
      This command line window needs to remain open in order to host and display the map in the browser.
      
  ## First Map
    Now from your browser, open the file in your Leaflet directory 'index.html'
    
    Once open, 'index.html' displays our Leaflet map!
    How did we do this, and what is this map displaying? Let's explore the map.
      * [walk through displays on the map]
        * clusters of location points
        * pop-ups
        * what do the pop-ups lead to
        * displays on the sidebar

    Going through each folder in project directory
