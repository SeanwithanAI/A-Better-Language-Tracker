# A Better Language Tracker

A study log and weekly quiz for any language, in a single HTML file. It runs on its own in any web browser, or inside [PageVault](https://github.com/SeanwithanAI/PageVault), where each person's data is saved on your server.

**Current version: 2026-11-14** · by SeanwithanAI

![Today](docs/screenshots/today.png) ![Quiz results](docs/screenshots/quiz.png)

## What it does

- **Any languages.** Start from a preset (Japanese, Korean, Mandarin, Tagalog, Spanish, French, German, Italian, Portuguese) or add your own. Each language has its own color, flag, notes and goal date.
- **Today screen.**
  - Today's plan, plus a "low-energy day" minimum.
  - Day streak, days studied this week, and minutes against your weekly goal.
  - A dot for each day of the week. Tap a dot to edit that day.
- **Daily log.** Minutes per language, with +10/+30 buttons. Check off what you did from your own list of activities, and add a note. You can go back and edit any past day.
- **Counts and goals.**
  - Track anything: words, kanji, characters, lessons, phrases.
  - Each count can have a total and a milestone with a date. The tracker shows how many per week you need to reach the milestone, and whether you're on pace based on your own updates.
  - Counts can be taken straight from your Words list.
- **Trip or goal countdowns** for each language.
- **Words & phrases list.**
  - Each entry has a reading, meaning and note.
  - Add many at once by pasting lines like `word = meaning`.
  - Searchable.
- **Weekly quiz, written by Claude.**
  1. The app builds a request from your levels, counts, recent words and your chosen question mix.
  2. Tap **Open Claude** (or copy the request into any AI chat).
  3. Paste the reply back in.
  4. You get a scored quiz with explanations, a skill ranking, and one skill to focus on next week.
  
  No account or API key is needed in the app.
- **Quick quiz from your words.** Instant, offline practice from your own list. It doesn't count toward your weekly ranking.
- **History.** Quiz results by week, recent study days, and how each count has changed.
- **Charts.** Minutes per week for the last 8 weeks, stacked by language.

## Quality of life

- Day / Dark / Auto theme.
- Works on phones.
- In PageVault, data is saved to your server, separately for each person who signs in.
- Outside PageVault, data is saved in your browser, with a reminder every 7 days to download a backup.
- **Download app + data (.zip)** puts this version of the app, your backup and a short note in one zip.
- Back up and restore with a JSON file.

## Using it

- **On its own:** download `A-Better-Language-Tracker-2026-11-14.html` and open it in a browser.
- **In PageVault:** upload the HTML file as an app.

Previous versions of these apps are at https://github.com/SeanwithanAI?tab=repositories.
