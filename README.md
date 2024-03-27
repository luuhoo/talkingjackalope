This *is* my first mod ever, for anything ever - please be patient with me. Any feedback, constructive or otherwise, is more than welcome!


An Inscryption mod that adds a talking Jackalope card into Act 1 and Kaycee's Mod.
She can be found randomly via. random card draws or trader's inventories. I'd like to add her as a static encounter, like the other talking cards, but until I learn how that is unavaliable.

Jackalope has unique lore, animated portraits, a unique voice pitch, and unique dialogue for nearly every in-game situational (excluding between-cards conversations, e.g. Stoat and Stinkbug talking to each other)



## CHANGELOG
- V1 - Initial Release.
- V2, Unpublished - Fixed the portraits glitching, fixed(?) the starter decks not appearing properly.
- V2.5 - Added TONS of new dialogue, changed ~~Astrella~~ Jackalope's relationship with Leshy to be a bit more friendly (lore reasons.)

In addition, this mod also adds 2 starter decks:
| Name           | Cards                                            |
|----------------|--------------------------------------------------|
| Creation	 | Jackalope (Talking), Elk, Wolf, Stoat, Cockroach |
| Moon's Embrace | Jackalope (Talking), Raven, Grizzly Bear, Cat    |


# Installation
This mod’s dependencies are BepInEx, the InscryptionAPI, JSONCardLoader and TalkingCardAPI.

The Jackalope Mod was made using KellyBetty's Talking Possum Mod (https://inscryption.thunderstore.io/package/KellyBetty/Talking_Possum/) as a base and TalkingCardAPI (https://inscryption.thunderstore.io/package/KellyBetty/TalkingCardAPI/).
I don't believe I'd be able to help you with any bugs that came up on behalf of either mod - due to KellyBetty having not been active in a year.*
*subject to change


### KNOWN ISSUES
- Antlers and ears clip the edges of the card's borders. Unfixable until further notice (as in, until I find the correct aspect ratio.)
- 'Laughter' emotion may still show an emission sprite despite her eyes being closed - under investigation.
- I am 90% sure this mod DOES NOT function with Orochi_Umbra's amazing NodeBane mod, unfortunately.


To copy directly from KellyBetty's Talking Opossum README:
-----------------------------------------------------------------
There are two ways of installing this mod: with the help of a mod manager (like r2modman or the Thunderstore Mod Manager) or manually.

#### Installation (Mod Manager)
1. Download and install [r2modman](https://thunderstore.io/package/ebkr/r2modman/) or the [Thunderstore Mod Manager](https://www.overwolf.com/app/Thunderstore-Thunderstore_Mod_Manager).
2. Install this mod and all of its dependencies with the help of the mod manager! 

#### Installation (Manual)
1. Download and install BepInEx.
    1. If you're downloading it from [its Github page](https://github.com/BepInEx/BepInEx/releases), follow [this installation guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html#where-to-download-bepinex).
    2. If you're downloading ["BepInExPack Inscryption" from Thunderstore](https://inscryption.thunderstore.io/package/BepInEx/BepInExPack_Inscryption/), follow the manual installation guide on the Thunderstore page itself. This one comes with a preconfigured `BepInEx.cfg` file, so it's advised.
3. Download and install the [Inscryption API mod](https://inscryption.thunderstore.io/package/API_dev/API/) following its manual installation guide. You need version 2.9.1+ of the API to run this mod.
4. Download and install the [JSONCardLoader mod](https://inscryption.thunderstore.io/package/MADH95Mods/JSONCardLoader/) following its manual installation guide. You need version 2.3.0 of JSONCardLoader to run this mod.
6. Find the `BepInEx > plugins` folder.
7. Place the contents of **"TalkingJackalope.zip"** in a new folder within the plugins folder.
