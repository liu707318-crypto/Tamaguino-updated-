Tamaguino-updated-
Tamaguino Lite Based on Tamaguino by Alojz Jakob https://github.com/alojzjakob/Tamaguino  A memory-optimized version for Arduino Pro Mini. 
# Removed
- splash1 and splash2 bitmaps — no splash screen art
- mountains bitmap — no background mountains
- trees bitmap — no trees in scenery
- cloud2 bitmap — no moving cloud
- eating1/2/3 bitmaps and eating[] array — no eating animation
- apple and steak bitmaps — no food art
- poop bitmap — poop is now a plain filled rectangle
- dinoWalk2 through dinoWalk5 — reduced to 2 walk frames instead of 6
- treesXPos variable and all tree scrolling logic
- couldsXPos and cloud1XPos — no cloud movement
- cloud1Width variable

# Modified
- Button cooldown added (180ms) — prevents button spam
- freeMemory() function added with Serial output every 10 seconds for RAM debugging
- Eating animation replaced with simple text ("YUM APPLE", "GLUG GLUG") and smiley face
- Splash screen is plain text instead of bitmap logo
- Display contrast explicitly set via ssd1306_command
- Serial.begin(9600) added
