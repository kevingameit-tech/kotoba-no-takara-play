# Kotoba no Takara: play the prototype

**Play:** https://kevingameit-tech.github.io/kotoba-no-takara-play/

Kotoba no Takara (言葉の宝, "the treasure of words") is a small JRPG for learning Japanese, made by a team of
four students. The interface is in Romanian and English. This repository only holds the playable browser prototype
(one file, `index.html`); the game itself, its data and its documentation live in
[kevingameit-tech/kotoba-no-takara](https://github.com/kevingameit-tech/kotoba-no-takara).

- Chapter 1, Tokyo: the 46 hiragana. Chapter 2, Kyoto: katakana, with ゛ ゜, ー and small ッャュョ.
  Chapter 3, Nara: a first taste of kanji (14 kanji, a prototype slice).
- It runs in any recent browser, on a computer or a phone. Progress is kept in the browser (localStorage).
- This is a prototype: the story, the texts and the ids may still change.

## Privacy

Nothing is sent anywhere. Before a new game, "Before you start" explains what the game can record for the team's
study (ids and numbers only, no names or e-mail) and lets the player turn it off. Whatever is recorded stays in the
page until the player saves the files and hands them to the team.

## Updating

GitHub Pages publishes the `gh-pages` branch; `main` holds the same files. Replace `index.html` with a new build
of the prototype (the built page wrapped in an HTML document) and push it to both branches; the site updates
within a minute or two.
