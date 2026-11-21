# Reef Hunter VR

A spearfishing game for Meta Quest 3 that runs in the browser (WebXR).

Spear invasive lionfish and reef fish, stuff them into your containment tube, get them sized by Sal at the Weigh Station, and sell them at the Bait & Gear shop for upgrades.

## The ocean
A big bounded area with seven zones: Home Reef, Kelp Forest, Coral Garden, The Drop-off, the Shipwreck, Seagrass Meadow and Rocky Pinnacles. Most reef fish live around rocks and hide behind them when you get close.

## Sea life
You can spear: Lionfish (invasive), Blue Tang, Snapper, Parrotfish, Grouper, Clownfish, Pufferfish, Flounder (lies flat on the sand), Moray Eel (lurks at the base of rocks) and Mandarinfish (Coral Garden only, rare).
Protected, can't be speared: Seahorses in the Seagrass Meadow.
Just passing by: Hammerhead sharks and a Manta ray.

## Spearguns
After a shot the spear stays out on its rope: pull it in (hold A, or grab the rope with your left hand and pull).
Then reload: grab the front of the gun with your left hand and pull the bands back (or hold A).

## Gear (Bait & Gear shop)
Pole spears: Fiberglass (free), Aluminum (150), Carbon (500), Pro Carbon (1200).
Spearguns: Reef Speargun (3000), Pneumatic Speargun (7500), Carbon Railgun (15000).

## Play on Quest 3
Open the GitHub Pages link in the **Quest Browser** and press **ENTER VR**.

## Play / test on a PC
Run `node serve.js` and open http://localhost:8080. Without a headset you get the desktop test mode with a draggable 2D controller rig.

## Controls (VR)
- Right trigger: hold to pull the pole spear back, let go to shoot / click menus
- Push a speared fish into the containment tube in your left hand
- Left menu button (≡) or B (computer: Esc or M): menu, shown on your left hand in VR. In a dive it pauses: resume, settings, view & spear (field of view, height, spear hand, spear length, glove colour), or surface (asks "are you sure?" first). Swimming up to the surface asks too.
- Left-handed mode (View & Spear → Spear hand: Left): the spear goes in your left hand and the tube in your right; all buttons swap with them
- Left stick: walk / swim
- Right stick: turn, up / down
- Left trigger: lionfish sonar
- X: dive light
- Left grip: let go of the containment tube / grab it again (any way you hold it, it stays that way)
- Y: call the tube back to your hand

## Credits
Arms model: `models/arms_low_poly.fbx` (low poly rigged arms).
Underwater ambience: `sounds/underwater-ambience.mp3` (freesound_community, "underwater ambience").
Fish models: `models/fish/` from the 3D Fish Pack by polyy.ai (CC0), made lighter for the Quest with `tools/shrink-fish.html`.
