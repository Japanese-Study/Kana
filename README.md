# Kana

An installable study app for every hiragana and katakana character, including voiced kana, combinations (yōon), extended katakana for foreign sounds, small っ/ッ and the long-vowel mark ー.

For each character:

- animated stroke order with numbered strokes and a stroke-by-stroke strip
- a tracing pad to practise writing with a finger, stylus or mouse
- the character in textbook, sans-serif and serif styles, with notes on variant forms and look-alike characters
- up to five example words, each split into sounds with romaji, plus the English meaning

The **Drill** tab tests characters (sound ↔ kana) and words (reading and meaning), including extra vocabulary not shown on the cards. Missed items come back later in the round, and weaker characters appear more often. Progress is stored on the device.

It is a single static page with no build step. Once loaded, it works offline.

## Publish with GitHub Pages

1. Create a public repository, e.g. `kana`.
2. Upload all seven files to the top level (**Add file › Upload files**, select them all, **Commit changes**).
3. Open the repository's **Settings › Pages**. Set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute or two the app is live at `https://<your-username>.github.io/kana/`.

## Install on iPhone or iPad

Open the URL in **Safari**, tap **Share › Add to Home Screen**, then open the app once while online. After that it works offline.

## Updating

After changing `index.html`, change `VERSION` in `sw.js` (e.g. `kana-v2`) so installed copies fetch the update.

## Credits

Stroke-order data from [KanjiVG](https://kanjivg.tagaini.net) by Ulrich Apel, licensed [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Fonts: Klee One, Shippori Mincho and Zen Kaku Gothic New from Google Fonts.
