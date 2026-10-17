# Magical Pets

A single-player browser game designed by Mira, made with love by Daddy. Magical pets choose you, and they grow by being loved, not by fighting.

The whole game is one file: `index.html`. No build step, no dependencies (it only loads Google Fonts).

## Play locally
Open `index.html` in a browser.

## Deploy with GitHub Pages
1. Push `index.html` (and this README) to a GitHub repository.
2. In the repo go to Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

## Worlds and travel
There are 25 worlds on a universe map. Tap "All worlds" to see them and pan or zoom around. When you go through a cave, a short animation shows you and your pets flying along the route on the universe map and through the portal.

The last 10 worlds are grim and magical, each with its own land shape (ring, crescent, islands, star, ridge, spiral, flower, peanut, comet, claw), its own music, and tougher guards.

## Danger
Each grim world has a danger rating: Low, Medium or Deadly. The rating shows under the cave name, on the universe map, and in the top bar.
- Glowing rune circles on the ground are cursed. A pet that steps on one shrinks back one level (a level 1 pet loses its progress).
- One pet type per world is safe on the curse. The game tells you which one.
- In Deadly worlds the circles are hidden until you get close.
- Tapping to walk steers around circles you can already see. Walking with the keyboard does not.
- A Ward Charm (a tool found at level 5 and above) protects your pets for 90 seconds.

## Your home world, your look, your Petdex
- At the start you choose Female or Male for the pet owner, with hair styles and outfits for each.
- After the first egg hatches you choose your home world from six looks (Sunny Meadow, Frosty Isle, Dune Isle, Coral Cove, Starlight Garden, Moonlit Glade). Every home has the lab, the sunny hill, berries, a pond and the caves.
- The Petdex lists every kind of pet you have seen, hatched or grown to level 2 or 3. Unknown pets show as dark silhouettes and fill in as you discover them.

## Pets found in each world
Every world lists the kinds of pets that live there: tap a world on the universe map (open worlds show their types, unexplored ones show `?`), tap **Pets here** in the top bar while exploring, or look at the **Found in** line under each type in the Petdex.

## Flying
A fully grown (level 3) Fairy, or any fully grown bird, bat or owl, can fly when it is **first in your team line**. Press **Fly**, then tap anywhere (or on the bird's-eye map) to soar there fast. While flying, the whole team is safe from cursed rune ground. You cannot land on a glowing rune. If a flyer is in your team but not at the front, Professor Bolt offers to move it to the front, and the pet's page has a **Put in front to fly** button.

## Hunger
Pets get hungrier as they walk (and fly, a little less). Each pet has a Tummy meter on its page, and its name tag in the world says *hungry* or *starving*. A starving pet slows the whole team down. Feed pets from the bag (**Feed pets**) or at a berry bush to fill their tummies. Fully grown pets eat too.

## Controls
- **Right pad** (or arrow keys / WASD): moves your player. **Left pad** (or I, J, K, L): looks around the world. Tap the centre of the left pad (or press C) to snap the view back to you.
- You can also tap the ground to walk there, drag pets, pinch or +/- to zoom.
- The pad button in the top bar (or the P key) hides and shows both pads.

## The top bar
Everything is grouped into four buttons. Tap one to see its details: **World** (pets found here, danger), **Level** (abilities, unicorn rescues), **Bag** (coins, food, balls, stones, tools) and **Team** (every pet's tummy, speed). Warnings such as danger, shields or a hungry pet appear next to them.

## Powers
Every fully grown (level 3) pet has a special power that depends on its type, shown on the **Powers** button: Pixie Dust (fairy), Torch Light (fire), Bubble Shield (water), Bloom (grass), Frost Calm (ice), Dig Treasure (earth) and Rainbow Heal (unicorn). Each recharges on its own.

**Scouts:** fully grown wind, psychic, electric and shadow pets (Sky Scout, Far Sight, Lightning Runner, Shadow Scout) can be sent out to find a pet type that a guard needs and you do not have yet. They are away for 1.5 to 3 minutes of real time (you can close the game) and come back with a new friend of that type. You must keep at least one other pet with you.

Moving fast is handled by flying, so no power overlaps with it.

## World Jump
Above level 10, once every pet is fully grown, you can jump to a world 2 or 3 caves away and skip the worlds in between (only worlds you have already opened). After a jump it recharges while you walk.

## Unicorn spirits
At level 10, 15, 20 and 25, a unicorn spirit starts roaming the world that you just opened (you can see it drifting near that world on the universe map). It runs and blinks around. Make it happy and use a Happy Stone to rescue it. A shimmering, echoing chime plays when it is near, when it blinks to a new spot, and when you open the universe map while one is roaming.

## Weather and meteors
Every world has its own weather: snow, rain with lightning, falling leaves, floating embers, bubbles, fireflies, ash and more. Meteors fly across the universe map. Everything is turned off for players who ask their device to reduce motion.

## Prizes and tools
Beating a guard (after the very first one) gives a prize: pick coins, colorful balls or Happy Stones. From player level 5, worlds also hide a few sparkles that give small strategy tools (Joy Chime, Lucky Clover, Focus Charm, Ward Charm). Hold up to 3 of each.

## Sound
Every world has its own generated background music and ambient sounds (made live with the browser's Web Audio, no audio files). The speaker button in the top bar, or the M key, mutes it; the choice is remembered. Browsers only allow sound after a tap, so music starts when the player taps Explore the world. Turning sound on plays a short chime so you hear it at once. If the browser has not allowed sound yet, the speaker button glows with a gold ring until the first tap. On iPhone the sound uses the playback channel, so the silent switch does not block it. The little top-bar sheets (World, Level, Bag, Team) only lower the music a little.

## Phones
On Android, tapping Explore the world goes full screen and turns the phone sideways. On iPhone Safari the browser does not allow that, so use Share > Add to Home Screen: the installed app opens full screen in landscape.

Progress is saved in the player's own browser (localStorage), so each device keeps its own save.
