# Big Hand, Little Hand

A clock-reading game for kids, built for iPad and live at **https://time.bunnyworld.dev**.

Each round has 10 questions that alternate between two kinds:

- **Read the clock**: an analog clock is shown; pick the matching time from four choices.
- **Set the clock**: a time is shown; drag the hands to match it, then tap **Check my clock**.

## Levels

| Level | Name      | Times used                         |
|-------|-----------|------------------------------------|
| 1     | O'clock   | Full hours (3:00)                  |
| 2     | Half past | Hours and half hours (6:30)        |
| 3     | Quarters  | Quarter hours (9:15, 2:45)         |
| 4     | Any time  | Any minute (10:52)                 |

## How it teaches

- Blue always means hours (little hand, hour numerals). Orange always means minutes (big hand, minute numbers).
- The hour hand moves realistically between numbers, so 2:45 shows the little hand almost at 3.
- Wrong answers get a hint matched to the mistake: swapped hands, reading the next hour too early, reading the big hand's number as minutes, and so on. After the answer, a line explains how to read it ("Count by fives: 5, 10, 15").
- The minute-number ring (0, 5, 10 … 55) can be switched off as he gets better.
- Stars per round: 3 for 9+ right on the first try, 2 for 6+, 1 otherwise. Best stars per level are saved in the browser.

## Development

Everything is in `index.html`: no build step, no dependencies beyond Google Fonts. Open the file in a browser to run it locally. Pushing to `main` redeploys GitHub Pages.

On iPad, Safari → Share → **Add to Home Screen** launches it full-screen like an app.
