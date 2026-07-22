---
layout: default
title: Hewigkeyt's Projects
---

# Hewigkeyt's Projects

Welcome to my GitHub Pages site. This is the central hub for all my open-source projects, web apps, and personal creations. Everything here is built and maintained by me, and hosted for free thanks to GitHub Pages.

My main active project is **Anime Wordle**, a free daily browser game for anime fans. You can play it directly here:

👉 **[Play Anime Wordle](https://github.com/Hewigkeyt/hewigkeyt.github.io/blob/master/anime_wordle)**

---

## About Anime Wordle

Anime Wordle is a daily anime character guessing game inspired by the word-guessing genre popularized by Wordle, but built specifically for anime and manga fans. Instead of guessing a five-letter word, you guess a character, and each guess reveals clues — such as gender, hair color, first anime appearance, studio, and release year — that narrow down who the mystery character is.

The goal is simple: use deduction and your knowledge of anime to identify the character of the day in as few guesses as possible. It's designed to be quick to play (most rounds take two to five minutes) but hard to master, since the clue system rewards genuine familiarity with anime history rather than lucky guessing.

A new mystery character is released every day, so there's always a fresh challenge, and results reset at midnight UTC. Playing regularly is also a fun side effect: the clues expose you to a wide range of characters, seiyuus (voice actors), and animation studios, so daily players tend to pick up real knowledge about anime trivia over time, not just guessing skill.

### How to Play

1. Type an anime character's name into the search box to make your first guess.
2. After each guess, the game compares your character to the mystery character across several attributes and colors each tile:
   - **Green** — exact match.
   - **Orange** — partial match. For multi-value attributes (like hair color or studio) this means at least one value overlaps but not all of them; for numeric attributes (like release year) it means the guessed value is higher or lower than the target, shown with an arrow.
   - **Red** — no match at all.
3. Use the pattern of colors to narrow down your next guess.
4. Keep guessing until you find the correct character or run out of attempts.

### Character Database Rules

The game uses a specific, consistent set of rules to decide what counts as "correct," so that clues stay fair and predictable:

- **First appearance only:** a character's stats are based on their first major anime appearance, not later sequels or reboots. For example, Naruto Uzumaki is treated as the 12-year-old from *Naruto* (2002), not the older version from *Naruto: Shippuden* (2007).
- **Multi-value hair color:** characters can have more than one listed hair color (for example, if it changes across the series or is a gradient). A guess is orange if any of the guessed colors overlap with the target's colors, and green only if the full sets match.
- **Multi-value studio:** a character's anime can involve several animation studios (co-productions, sequels made by a different studio, etc.). As with hair color, this is scored as a set — orange for partial overlap, green for an exact match.
- **Age handling:** brief flashback or cameo appearances are ignored when determining age — for example, Eren Yeager is listed as 15, his age at the start of the series.
- **Unknown ages, sex, and height:** some characters have no officially confirmed age, sex, or height. In these cases the corresponding tile is treated as "undefined" and can only match another character that is also undefined for that attribute.

### Daily Leaderboard

Every day's puzzle has its own leaderboard, split into two categories:

- **No-hint** — for players who solve the puzzle without opening the hint panel.
- **Hints** — for players who used the hint panel to help narrow things down.

The game can be genuinely difficult, especially for characters from older or more obscure series, so the hint panel is there if you want it. Once you make your first guess, you can open it to see a full list of anime grouped by studio, plus which studios you haven't ruled out yet. Ties on the leaderboard are broken on a first-come, first-served basis.

### Monthly Leaderboard

In addition to the daily rankings, there's a monthly leaderboard that tracks consistency over the whole month rather than a single best day. It's ranked by your **average number of guesses** across the month's puzzles, with a couple of adjustments to keep it fair:

- **Hint penalty:** using the hint panel on a given day adds a penalty to that day's guess count before it's averaged in.
- **Skip penalty:** any day you don't play is counted as a penalty rather than simply excluded, so the monthly ranking rewards regular play, not just picking your best days.

### Unlimited Mode

Once you've finished the daily challenge, you can switch to **Unlimited Mode**, where a new character is picked at random every time. This mode has no leaderboard and no daily limit — it's there purely for players who want to keep practicing or just enjoy guessing characters without any time pressure.

### Feedback, Bug Reports & Suggestions

Anime Wordle is actively maintained, and community feedback directly shapes future updates. If you spot an error in the character database, run into a bug, or have an idea for a new feature (or a character you'd like added), please open a ticket:

- 🛠️ **[Submit a Bug Report or Feature Suggestion](https://github.com/Hewigkeyt/anime_wordle/issues)**

---

## Other Projects

**[Codenames Anime](https://github.com/Hewigkeyt/codenames-anime)** — A browser-based, anime-themed twist on the party game Codenames. Instead of word cards, players guess anime characters pulled live from AniList based on a chosen year range. One Spymaster per team can see which characters belong to Blue, Red, or Neutral, and games are synced live so friends can play together from a shared link.

👉 **[Play Codenames Anime](https://hewigkeyt.github.io/codenames-anime)**

A dotfiles repository for my Hyprland setup is also coming soon — it will cover my window manager config, theming, and general Linux desktop setup.

I also maintain a personal site at **[maetel.xyz](https://maetel.xyz/)**.

This site will also host additional small web apps and games as they're built. Check back for updates, or watch the repository on GitHub to be notified of new releases.

---

## Privacy Policy

Your privacy is important to us. This website uses Google AdSense to serve advertisements. Google and its partners use cookies to serve ads based on your prior visits to this website or other websites on the Internet.

Google's use of advertising cookies enables it and its partners to serve ads to you based on your visits to this site and/or other sites on the Internet. You may opt out of personalized advertising by visiting the Google Ads Settings page.

By continuing to use this website and playing Anime Wordle, you consent to the use of these cookies for advertising and analytics purposes.
