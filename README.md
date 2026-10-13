<img width="3584" height="1076" alt="Gemini_Generated_Image_lg0bqrlg0bqrlg0b" src="https://github.com/user-attachments/assets/5a03ff0e-e2ea-427c-bd84-a1a61ca60d81" />

Play the game here:

https://be-ai-research.github.io/BE-BanditPet/


🦝 Jima-Gotchi: Virtual "Pet Terrorist"

Welcome to Jima-Gotchi, a retro-inspired, pocket-sized virtual pet game built entirely in a single HTML file. Raise Jimothy, a highly chaotic, trash-devouring raccoon. Keep his grease levels high, manage his destructive urges, and build a massive trash palace in both 2D and Augmented Reality!

✨ Features

Retro LCD Aesthetic: Fully customizable hardware! Change the device shape (Classic, Egg, Brick), shell color, and LCD backlight themes.

Tamagotchi-Style Needs: Manage Jimothy's Hunger (Trash), Chaos, Grease, and Energy.

Offline Progression: Jimothy's life continues even when you close the tab. He will get hungry, energetic, or feral while you are gone!

WebXR AR Mode: Spawn Jimothy into the real world! Tap to build a 3D trash palace that features Object Permanence (saves to your local storage so your physical room remains his domain).

Mini-Games: Risk getting caught by the neighbor's dog in Midnight Raid or burgle a house in Night Heist to earn shiny caps and loot.

Evolution System: Watch Jimothy mutate from a tiny Kit Bandit into a Feral Sewer Goblin, a Dumpster Emperor, or even a Cosmic Trash Deity based on how you raise him.

Zero Dependencies: The game runs entirely on vanilla HTML, Tailwind CSS (via CDN), and Vanilla JS. Three.js is imported dynamically for AR.

🎮 How to Play

The Vitals (Stats)

Jimothy is not a normal pet. His needs are... unique.

🗑️ TRASH (Hunger): Keep this high! Feed him soggy fries and floor pizza. If it drops to 0, he will start chewing your digital drywall.

🔥 CHAOS: Jimothy's destructive urge. It naturally rises over time. If it gets too high, he will go feral, throw objects at your screen, and crack your LCD.

🧦 GREASE: Jimothy's health and hygiene. Do not wash him. Use the "Lint" action to roll him in warm dryer lint to maintain his protective grime layer.

⚡ ENERGY: Depletes naturally and when playing mini-games. Put him to sleep (Nap) to restore it rapidly.

Controls

You can interact with Jimothy using the on-screen buttons, quick-action menus, or your keyboard!

D-Pad (Arrow Keys): Poke Jimothy (results may vary) or navigate the Inventory/Menu.

A Button (Key 'A' or '1'): Feed Jimothy a random piece of trash.

B Button (Key 'B' or '2'): Launch the Midnight Raid mini-game.

SELECT (Quick Menu 'Nap'): Toggle sleep mode to recover energy.

START (Quick Menu 'Lint'): Groom Jimothy with dryer lint to restore Grease.

≡ MENU: Open the main system menu to access your Inventory, trigger AI Foraging, or Reset your save.

🕹️ Mini-Games

Midnight Raid (Press B)

Sneak into the alley to tip trash cans.

A Button: Loot a bin! Earns you Trash, XP, and a chance for item drops.

B Button: Hide!

Watch out: The neighbor's dog is listening. If the dog's awareness reaches "BARKING!", you will be chased away and lose energy. Hide (B) to lower the dog's awareness. Don't get greedy!

Night Heist (Via Main Menu)

Only available at night (6 PM - 6 AM local time).
Break into a house for premium loot and shiny caps. Same controls as Midnight Raid, but the stakes (and rewards) are much higher. If you get busted, you might drop an item from your inventory!

🕶️ Augmented Reality (WebXR) Mode

Bring Jimothy into your living room! This feature requires a WebXR-compatible browser (like Chrome on an Android device) and ARCore.

Tap the 🕶️ (AR) icon in the top right corner of the device shell.

Slowly pan your camera around your floor or a flat table to allow the device to map the area.

Once a green targeting ring (reticle) appears, Tap the screen to summon Jimothy.

Tap again to spawn pieces of his Trash Palace.

Object Permanence: Every piece of trash you drop is saved locally. If you close AR and open it later, placing Jimothy will instantly rebuild his palace exactly as you left it!

🎒 Advanced Features

Google Chat Webhook: Click the 💬 icon to enter a Google Chat webhook URL. Jimothy will occasionally post messages to your team channel when he levels up, evolves, or goes feral.

Gemini AI Foraging: (Requires inserting your own API Key in the source code). Jimothy can use the Gemini AI API to dynamically generate bizarre, never-before-seen trash items with unique stats and descriptions!

🛠️ Setup & Installation

Because Jima-Gotchi is a single-file application, installation is effortless:

Clone this repository or download index.html.

Double-click index.html to open it in your browser.

Note for AR Mode: To use WebXR features, the page must be served over HTTPS or localhost. You can easily do this using a local server like VS Code's Live Server extension, Python's http.server, or by hosting it on GitHub Pages.

💾 Save Data

Your game is automatically saved to your browser's localStorage. If you want to start over, select RESET JIMOTHY from the Main Menu.

Created for the love of 90s digital pets and chaotic raccoons.
