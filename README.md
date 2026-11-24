# Hush

Interrupt barking, reward quiet. Hush is a home-screen web app for iPhone. It listens through the microphone, plays a cue when your dog barks, and tells you when to give a treat for staying quiet.

**Try it:** https://hybridnoise.github.io/hush/. In Safari, tap Share → Add to Home Screen.

- Runs entirely in the browser. Audio is processed on the device and never uploaded.
- Works offline once installed (service worker + web app manifest).
- Plain HTML and JavaScript with no build step: `index.html`, `sw.js` and `manifest.webmanifest`.
