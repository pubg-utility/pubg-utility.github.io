# PUBG Loadout Generator

A simple website that generates random, map specific, PUBG weapon loadouts.  
It was designed with **OBS integration in mind**, so you can use it as a **browser source overlay** while streaming.

<p align="center">
  <img width="447" height="810" alt="image" src="https://github.com/user-attachments/assets/657a4307-03ca-4267-8195-e7a13d3b4c1a" />
</p>

---

## Features
- Generate random, map specific, PUBG weapon loadouts.
- Lightweight website with clickable buttons that work in a standard web browser and inside of OBS in a browser source.
- Transparent background for easy overlay on streams.

---

## Using in OBS
1. Add a new Browser Source in OBS. Give the source a name and click Ok.
2. Set the URL to https://pubg-utility.github.io/pubg/loadout_generator/.
3. Set the width to 450px and height to 1080px (recommended).
4. Clear the contents of the Custom CSS box.
5. Click Ok

<p align="center">
  <img width="971" height="852" alt="image" src="https://github.com/user-attachments/assets/4d1ab806-19b4-45ee-8313-e832491f45d1" />
</p>

**NOTE:** You must disable **hardware acceleration** for browser sources in OBS, otherwise the browser source won’t be interactive.
- Go to File -> Settings -> Advanced -> Uncheck the *Enable Browser Source Hardware Acceleration*
- Restart OBS

To interact with the overlay directly in OBS, go to your sources panel, right click on the browser source, and click Interact. This will pop open a new window where you can select the map and click generate to generate a new loadout.

**SUGGESTION:** After adding the browser source overlay to your scene, generate a loadout to get an idea of where you want the overlay to be. We would suggest moving the overlay off the canvas so the map selection radio buttons and the generate loadout button are hidden from the stream.

---

## Ideas & Feedback
If you use this and think of features that would improve it, let me know!  
Contributions and suggestions are welcome.
