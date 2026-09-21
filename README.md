# Block Buddies

A playful place-value number game for kids.

**Play it:** https://castilloworksai.github.io/block-buddies/

- **Park**: type a number and watch your block buddy build itself. Slide buddies together to add them, lift one to break it apart, and try fractions, decimals and π.
- **Run**: a runner game where you collect ones, tens and hundreds and dodge the grumps.
- **Quiz**: six quizzes that adjust to the child. Two right answers in a row moves up a level and a miss steps back down.
  - Which is bigger? · Read the blocks · Word wizard · Make ten · Number line · Skip counting
- **Book**: 29 stickers to earn, plus a new daily challenge each day.
- **Grown-up corner**: press and hold the button at the bottom of the Book to see play time, quiz levels and accuracy, and the questions your child missed most.

## Install and offline play

It works offline once it has loaded. On a phone or tablet, use **Add to Home Screen** (Safari) or **Install app** (Chrome) to open it like an app.

## Privacy

All progress is stored in the browser's local storage on that device. Nothing is sent anywhere.

## Development

The game is a single `index.html` with no build step and no dependencies. `sw.js` caches it for offline use, so bump `VERSION` in `sw.js` when you change the icons or other cached files.
