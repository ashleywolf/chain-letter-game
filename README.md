# CHAIN MAIL

A 90s chain letter simulator. Forward or delete? Keep the chain alive or face the consequences.

**[Play now](https://ashleywolf.github.io/chain-letter-game/)**

## About

Remember getting chain letters in your AOL inbox? The ones that threatened 7 years of bad luck if you didn't forward them to 10 friends in the next 24 hours? This is that, but as a game.

You navigate a fake 90s email client from 1995 to 1999, deciding which chain letters to forward and which to break. Your choices affect your curse meter, luck score, stamp supply, and whether your Tamagotchi survives.

Single HTML file. No dependencies. No build step. Just vibes and curses.

## Features

- 8 chain letter template types: luck, scam, virus hoax, wish, guilt trip, scary story, friendship, prayer chain
- AOL-era email client UI with Comic Sans, Win95 chrome, and a yellow marquee
- Curse/luck system with random events (your mixtape gets eaten, your GeoCities page goes viral, etc.)
- Buddy list that grows as you progress through the years (22 contacts total)
- Dial-up connection intro with modem sounds
- Sound effects throughout (Web Audio API, no external files): mail chime, cursor clicks, send whoosh, curse rumble, year fanfare
- Screen shake on bad luck, confetti on good luck
- Clippy shows up to offer unsolicited chain letter advice
- Konami code easter egg
- Title bar X button that refuses to let you leave
- Multiple endings based on your choices
- Saves progress to localStorage

## Tech

One `game.html` file, one `index.html` splash page. Everything is vanilla HTML/CSS/JS. Sound is generated procedurally with the Web Audio API. Hosted on GitHub Pages.

## License

MIT
