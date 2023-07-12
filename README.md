# The Clearing of Wretchhold

***A web game made for [Dungeon Jam 2023](https://itch.io/jam/dcjam2023)***

## Try it out

Play it on itch: https://deathray.itch.io/the-clearing-of-wretchhold


## Design Goals

1. Create a game along side a web/Javascript framework that is easily extendable
2. Satisfy the Definition of a "Dungeon Crawler", aka. DRPG, as outlined here: https://www.dungeoncrawlers.org/definition/
	- First-person exploration
	- Grid-based
		- Instant step movement
		- 90 degree turns
	- Stats
	- At least one character (perferrably allow for a "blob")
	- An end-of-game mechanic, such as a death condition
	- Combat or a similar mechanic for determining outcomes


## Run it Locally

1. Download the repo or git clone it
2. `npm i`
3. `npm run serve`
4. Open in your browser (e.g., `http://192.168.1.162:8080/`)
5. If you're making code changes, then build with `npm run watch` or `npm run build`

## Credits

The Clearing of Wretchhold:

* Sound Design - Bann
* Writing, Game Design - Charley Rand
* Music - Griffin d'Audiffret
* Level Design - Frankee
* Voice Acting - Langi Tuifua
* Programming, UI, Level Design - Luke
* Art - Dungeon Crawl Stone Soup (https://opengameart.org/content/dungeon-crawl-32x32-tiles-supplemental (https://github.com/crawl/tiles))
* Sound Effects - NEXTALE Sound Effects Library

The [Dungeon Boots engine v1.0.0](https://github.com/rocket-boots/dungeon-boots/releases/tag/v1.0.0) was made by Luke, and utilizes the following dependencies:
- Three js
- Howler js
- Rocket Utility Belt (https://github.com/rocket-boots/rocket-utility-belt)
- rocket-boots-three-toolbox (https://github.com/rocket-boots/rocket-boots-three-toolbox)

![Screenshot of The Clearing of Wretchhhold](https://rocket-boots.github.io/dungeon-boots/images/screenshot2.PNG)
