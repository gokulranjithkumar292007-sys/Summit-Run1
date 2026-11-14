# Summit-Run1
An endless 3D runner on a mountain trail. You play a hero from a mountain tribe, a troop of monkeys chases you, and the speed keeps rising as your dollars grow.

Play: https://claude.ai/artifact/8STFYkWQPgrRatzJAtE2dZ

Gameplay
Run down a three-lane trail through snowy peaks and pine forest.
Each $ coin is a point, and speed rises as you collect them.
Hitting an obstacle lets the monkeys close in, and a second hit before they fall back ends the run.
The monkeys slowly drop back if you run cleanly.
Controls
Action	Keyboard	Touch
Move left / right	← → or A / D	Swipe, or ◀ ▶ buttons
Jump	↑, W or Space	Swipe up, tap, or ▲ button
Slide	↓ or S	Swipe down, or ▼ button

Pressing jump just before landing still counts as a jump.

Obstacles
Rocks: jump over them.
Low logs: slide under them.
Boulders: change lanes.
Screens
Home: your $ balance and the Play, Characters, Shop and Settings buttons.
Characters: pick a hero you own and preview it in 3D.
Shop: buy new heroes with $, with a confirmation popup and a “not enough $” message.
Settings: graphics, particles, shadows and audio (see below).
Game over: your run total, best score, completed missions and new balance.
Heroes
Hero	Price
Kaito	Free
Asha	$100
Bhim	$250
Tenzin	$400
Nuna	$650
Zephyr	$1,200

Each hero has its own look and running style.

Economy
Your run’s coins are added to your balance when the run ends.
Six one-time missions pay bonus dollars. They include collecting $25, $60 or $120 in one run, surviving 45 seconds or 2 minutes, and dodging 20 obstacles.
Each mission can be completed once, so there is no unlimited free currency, and the balance can never go negative.
Settings
Graphics quality: Low, Medium or High.
Particles: On or Off.
Shadows: On or Off.
Music: On or Off, with a volume slider.
Sound effects: On or Off, with a volume slider.

Everything is saved on your device.

Tech
A single HTML file with no build step.
3D rendering with three.js r128, loaded from cdnjs.
All music and sound effects are generated in the browser with the Web Audio API, so there are no audio files.
Progress, purchases, balance and settings are saved in the browser’s local storage.
Troubleshooting
Blank page: check your internet connection and reload, because the 3D library loads from a CDN. An error message appears at the bottom of the screen if something fails.
No sound: browsers only allow audio after a click, so press Play. Also check the music and effects switches in Settings.
Slow on an older phone: set Graphics to Low and turn off Particles and Shadows.
Lost progress: it is stored per browser, so clearing site data or using private mode resets it
