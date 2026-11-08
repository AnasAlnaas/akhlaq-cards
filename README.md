# بطاقات الأخلاق — Akhlaq Cards

A group card game for classrooms and study circles on the hadiths of good character (أحاديث الأخلاق), from al-Bukhari, Muslim and the Sunan. The teacher puts it on a screen and up to six players take turns opening cards.

Live: https://akhlaq-cards.netlify.app

## How it plays
- 2–8 stages, three difficulty levels (or a rising ramp), optional timer.
- Each player has one 50:50 help for the whole game.
- **Steal:** if a player answers wrong, the next player may try — right is **+½**, wrong is **−1**.
- After each answer the full hadith, its source number and its grading (متفق عليه / البخاري / مسلم / صحيح / حسن) are shown.
- **Review round:** after the match, every question missed on a player's own turn can be replayed without a timer or score.

## Files
- `questions.js` — the question bank (`QS`). Correct answer first; the game shuffles. `g` is the grading badge.
- `game.js` — game engine (shared lineage with Sirah Cards and Athkar Cards).
- `index.html` — page and styles. `og.png` — share image.

Numbering: al-Bukhari per Fath al-Bari, Muslim per Muhammad Fu'ad Abd al-Baqi; Sunan gradings per al-Albani.

Pushing to `main` deploys to Netlify automatically.
