# Grime After Time: downloads

**Grime After Time** (working title) is a first-person, cooperative cleanup game for Windows PC. You are part of a cleaning crew that turns up after a wild party. Clean the mess, put the furniture back where it was, and get paid by an owner who is not in a good mood.

This repository only holds playable builds. Download the latest zip from the [Releases](../../releases) page, unzip it, and run `GrimeAfterTime.exe`. The zip is password-protected and uses AES-256 encryption, so unzip it with [7-Zip](https://www.7-zip.org/) or WinRAR (Windows Explorer cannot open it). Whoever sent you the build has the password. Every release lists everything that changed since the one before it.

## Screenshots

![The main menu, over the HQ](screenshots/01-main-menu.jpg)
*The main menu, over the HQ*

![The HQ: van, contract board, toys and lockers](screenshots/02-hq.jpg)
*The HQ: van, contract board, toys and lockers*

![Lockers: pick your suit colours](screenshots/03-locker.jpg)
*Lockers: pick your suit colours and suit art*

![The crew shop](screenshots/04-crew-shop.jpg)
*The crew shop*

![The HUD: time and clean bars, and the hint bubble](screenshots/05-grab-and-hud.jpg)
*The HUD: time and clean bars at the top left (taken before the hint moved to a small card in the top right)*

![The vacuum and the power washer](screenshots/06-vacuum-and-washer.jpg)
*The vacuum and the power washer*

![A random party house, after the party](screenshots/07-party-house.jpg)
*A random party house, after the party*

![Bigger jobs: two-storey houses](screenshots/08-two-storey-house.jpg)
*Bigger jobs: two-storey houses*

![Rewind: the party through a drunk guest's eyes](screenshots/09-rewind-party.jpg)
*Rewind: the party through a drunk guest's eyes*

![The owner's inspection](screenshots/10-owner.jpg)
*The owner's inspection*

![Job complete](screenshots/11-job-complete.jpg)
*Job complete: stars and how clean, the pay, and the crew with their awards*

![The super glue gun and its goo](screenshots/12-glue-gun.jpg)
*The super glue gun: a bead of glittering goo on the carpet*

## Features

> This list is kept complete: it describes everything the game can do as of the latest release.

### The job
- Every round is a **different random party**: a new floor plan, kitchen corner, interior walls, furniture, stains, trash and guests, so no two jobs look the same.
- **Clean up**: wash away stains, bin the trash, and carry furniture and ornaments back to where they stood before the party.
- **Wall pieces to glue back**: every round some wall decoration (a painting, a poster, a clock and so on) has come off its wall and lies on the floor. It only counts as put back once it hangs on its wall again, and only the glue gun can put it there. Bigger houses have more of them.
- Your **pay** depends on how clean the house is and how close each piece is to its original spot. Finish early for a bonus; the owner arrives at the 10-minute mark and takes a cut for the wait.
- A **1 to 3 star rating** for each job (pass, 80%, 95% before the owner arrives), with your best stars and fastest pass kept for every level.
- **Style bonuses** for trick shots into the bin, bin streaks and clutch saves of falling items, with on-screen call-outs.
- **Job modifiers** you can add for extra pay: Blackout, Rush, No rewind, Fragile house, Butterfingers and Drunk crew.
- A **daily job** with its own seed and level, the same for everyone that day.
- Levels scale with difficulty: small one-room jobs up to big multi-room, two-storey houses with stairs. Harder levels have more furniture, trash and stains, and fewer rewinds.

### Time travel
- A **rewind gadget** sends you back into the party to watch what happened from the guests' own eyes and see where things belonged. Switch between guests, and watch the party lights sweep the dance floor and the music play.
- The past is drunk and dark: double vision, moving-head lights and no furniture moving, so you can learn the original layout. Others on your crew see you as a clay ball while you are away.
- Your crew can talk to you across time: **proximity voice chat** with a ghostly effect between the past and the present.

### Cleaning and chaos
- Tools: a **power washer** with an 8 m hose, a **vacuum** that sucks up any small loose thing (you can see the air rushing in; empty it into the bin, or dump it on the floor when full), a leaf blower, the **super glue gun** and the house bin (plus trash bags you can buy).
- The **super glue gun** lies next to the washer on every level. It shoots a bead of glittering goo up to 30 m at anything: a wall, the floor, furniture, trash, even a crewmate. The first loose piece (or player) that touches a bead is stuck to whatever the bead sits on. A piece you are carrying sticks too: it leaves your hands and stays on the goo. Stuck things are pressed right against each other, with only a thin layer of squashed goo between them. Glue gets in the way but is not trash and is not scored. Only the power washer removes it (about 10 seconds per bead), and a player stuck in glue cannot wash themselves free. Glue more than 5 things together and the whole group is stuck for good until you wash a bead off. You start each job with 5 shots; the shop's Glue tank gives more. The goo flies out of the muzzle in a spray of sparks, lands flat, bounces and settles into a sphere.
- **Grab** things with a stretchy clay rope, throw them, and bonk trash off your crew.
- The chaos is part of the game: washer knockback, wet floors that make you slip, the hose tripping you, clay flops, banana peels, dragging a crewmate by the rope and even **binning them**.
- At the end of the job the crew is lined up for the **owner's inspection**: one of ten mean owners walks every room, then slaps a random player if the house is below the pass mark, and hands over the cash.
- A **front door** you hold for 5 seconds to finish the job: a thin ring round your crosshair fills from green to red while you hold. It swings open for the owner, with a blinding white light outside, and an invoice that blames players for broken items.
- A **job-complete screen** with your star rating, how clean the house is, the pay split into icon lines (base, time, broken, rare, modifiers, style) and a picture frame for each crew member with their helmet, name and award. Hold Tab for the long text (invoice, level, daily best, owner review).

### Co-op
- Play **solo or with up to 4 players online**. One player hosts and shares a join code; there is no port forwarding.
- Pay goes into a shared crew bank. Everyone shares the job clock, the mess and the score.

### The HQ
A walk-around hangout between jobs:
- The **van** you all walk into to start a job, and a contract board with the job cards and modifiers.
- **Crew shop**: crew-wide upgrades in three tiers each: the power washer, sprint and carry strength, extra time, the trash bag, the rewind gadget, the vacuum, the leaf blower, another washer and the glue tank (more shots for the glue gun).
- Boards for money, local records and achievements; a **trophy shelf**; **20 achievements** with crew ranks shown on your name tag; and the owners' reviews of your work.
- Six **practice rooms** upstairs (the second floor now has a ceiling with lamps): the washer range, a furniture placing drill, a trash toss, and one room each for the **vacuum**, the **leaf blower** and the **glue gun**, with score boards and a reset post. The rooms are furnished with clay workbenches, wooden crates and a framed painting to glue back. The tools work there before you buy them.
- Toys: a basketball hoop, a jukebox, a punch bag and a vending machine.
- **Lockers and a mirror** to change how you look.

### Your look
- Everyone wears a clay cleaning suit with a dark visor. Choose three colours (suit, trim, gloves and boots) from ten swatches, type your own nickname (up to 15 letters), and decorate the suit with **preset art**: ten patterns (stripes, hazard, checker, dots, camo, stars, zigzag, waves, grid) and an ink colour for each of the helmet, torso, arms and legs.

### The HUD
- A small beige card at the top left shows two bars: **time left** (a clock) and **how clean the house is** (a sparkle). The time bar turns red in the last minute.
- **Hold Tab** (gamepad: Back / View) to open the card with the numbers and your crew list.
- A **small card in the top right corner** names what you are looking at ("Furniture: Dining Chair | Durability: 3/3"). The crosshair turns **yellow on furniture and red on trash**, also while you carry it.

### Sound and look
- A handcrafted **clay look** for the characters and props, and a clay-style menu and HUD.
- Sound effects, menu music, a different party track in each past, and lo-fi music while you clean. The settings screen has Music and Sound effects sliders.
- Keyboard and mouse, or a gamepad.

## Playing
- Windows 64-bit PC. Unzip first; do not run it from inside the zip.
- Play solo with **Play solo**. To play with friends, one person picks **Host online (up to 4)** and shares the code; the others type it under **Join a crew** and press **Join**. Your saved game (levels, money, upgrades, trophies) is kept between sessions.
- Found a bug or have an idea? Tell whoever sent you the build.
