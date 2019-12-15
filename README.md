# inkstronomy-brb-screen

A [NodeCG](http://github.com/nodecg/nodecg) bundle made for Inkstronomy livestreams. A copy of [inkstronomy-brb-screen](https://github.com/randomoink/inkstronomy-overlays) with different styling and fewer features.

# Notice

**Inkstronomy, the community these graphics were built for, has been abandoned by it's core staff team as of December 13th, 2019. I do not condone joining Inkstronomy in it's current state.**

## Screenshots

* [Dashboard](https://i.imgur.com/ODbymgQ.png)
* [BRB Screen](https://i.imgur.com/NJ93QlS.png)

## Install

1. Install NodeCG and (optionally) [nodecg-cli](https://github.com/nodecg/nodecg-cli).
2. Clone inkstronomy-brb-screen to `nodecg/bundles/inkstronomy-brb-screen` or if you have nodecg-cli installed, run `nodecg install randomoink/inkstronomy-brb-screen` in NodeCG's install directory.
3. Install dependencies by running `npm install` and `bower install` in `nodecg/bundles/inkstronomy-brb-screen`. If you're installing using nodecg-cli, this is done automatically.
4. For last.fm integration to work, create the configuration file at `nodecg/cfg/inkstronomy-brb-screen.json`.
It should look something like this, just replace the placeholders with your own information:
```
{
	"lastfm": {
		"targetAccount": "Your last.fm account",
		"apiKey": "your API key",
		"secret": "your secret"
	}
}
```
5. Install the [Lemon/Milk](https://www.dafont.com/lemon-milk.font) font.

## Usage

Start NodeCG. By default, the dashboard can be accessed from `localhost:9090` in your browser.

From the dashboard, URLs to the graphics can be found from the graphics tab. To use them, they should be added as browser sources in a broadcast application such as OBS Studio. The graphics are made to run at a resolution of 1920x1080.

## Credits

Last.fm extension (extension/lastfm-playing.js) from [toth5-overlay.](https://github.com/TipoftheHats/toth5-overlay)
