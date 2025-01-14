# Forked ver. of Taiga, specifically to get Crunchyroll Beta to function

[![](https://img.shields.io/github/license/erengy/taiga)](https://github.com/erengy/taiga/blob/master/LICENSE)
[![](https://img.shields.io/discord/423475967051169813?logo=discord)](https://discord.gg/yeGNktZ)

**UPDATE: I've tried using the application but this fork isn't a complete solution for CR Beta and there may be unintended bugs. E.g. Crunchyroll's instant episode system where it goes to the next episode immediately - I'm not sure if Taiga likes it. So yea, it is a little bit of a fiddle.**

This fork dedicates itself to getting Crunchyroll Beta to function. Thanks to Ryban for the Tampermonkey script otherwise me making this wouldn't have been possible. 

I've tested this on multiple browsers and I can conclude ...it's been confirmed and working that this works on Chromium-based browsers (so Chrome, MSEdge will work). It has also been tested on Firefox, and it works on there as well (yay). 

# Installation instructions
To install this, you'll need to install the [Tampermonkey extension](https://www.tampermonkey.net/) and you'll need to add the [Crunchyroll Beta Taiga Title Fix script](https://gist.github.com/ryban/d5d66b51618a98d242d4519ebc1e3b3e) (PS: If that link doesn't work, try [here](https://github.com/nicholasyoannou/taiga/releases/download/crunchyrollbeta-custombuild/cr_beta.userscript.js)). 

To add the script, go to the Tampermonkey Dashboard (click on the extension in the extensions menu > dashboard). Hit the '+' button in the menu left of 'Installed Userscripts'. Paste the script there and then in the editor menu hit file > save. 

Once it's added, you can then install the forked version of Taiga. Go to the [Releases](https://github.com/nicholasyoannou/taiga/releases/) and download and install TaigaSetup.exe. PS: I've added some stuff in there about what the userscript does, etc, if you want to know. 

# Footnote
And, that's it! If anyone knows how to make it so the script is built in to the Taiga application, well that would be great!
The aim of this build is to generally get Crunchyroll Beta to work, and the interface to me is quite nice. Some may be forced to use it, but eh, everyones opinions will vary.


For now, Sayōnara!
Oh yea, if anyone wants to ask me about this fork, I'm available on Discord janeberru#4594. 

________________________________________________________________________________________________
# About Taiga
Taiga is an open-source desktop application for Windows. It automatically detects the anime videos you watch on your computer and synchronizes your progress with [AniList](https://anilist.co), [Kitsu](https://kitsu.io) or [MyAnimeList](https://myanimelist.net). It helps you manage your anime library, discover new series, share watched episodes and download new ones.

Visit the [home page](https://taiga.moe) for more information. See the [guidelines](https://github.com/erengy/taiga/wiki/Guidelines) if you'd like to contribute. Here's [how to compile](https://github.com/erengy/taiga/wiki/How-to-Compile).

## Related projects

- [Anime relations](https://github.com/erengy/anime-relations): Episode redirections
- [Anisthesia](https://github.com/erengy/anisthesia): Media detection library
- [Anitomy](https://github.com/erengy/anitomy): Anime video filename parser
- [taiga.moe](https://github.com/erengy/taiga-moe): Home page of Taiga

## License

Taiga is licensed under [GNU General Public License v3](https://www.gnu.org/licenses/gpl-3.0.html).
