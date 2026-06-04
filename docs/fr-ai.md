# Prompt: FAIRE OU JOUER ? 🇫🇷

## Modern Web-Based French Learning Mini Game

Create a stunning modern web-based French learning mini game for secondary school students called:

# “FAIRE OU JOUER ? 🇫🇷”

The game should teach students when to use **“faire”** and when to use **“jouer”** with sports, hobbies, instruments, games, and activities.

---

## 1. Overall Style

Design the app like a premium educational iPad game.

Use:

* ultra-polished UI
* bright modern gradients
* large rounded cards
* soft shadows
* smooth animations
* big typography
* huge 3D-style emojis
* glassmorphism panels
* clean Gen-Z educational aesthetic
* mobile-first responsive layout
* touch-friendly controls
* fun but professional school presentation look

The visual style should feel like:

> Duolingo meets Apple meets a modern classroom game.

---

## 2. Background / Atmosphere

Use a blue/purple gradient background with subtle floating particles.

Add tiny French-learning accents such as:

* 🇫🇷
* ✨
* ⭐
* 📚

Use rounded corners everywhere, smooth transitions, and a playful but clean educational vibe.

---

## 3. Main Menu

Create a beautiful main menu with **5 difficulty levels**.

Each level should be shown as a large rounded card with:

* level number
* difficulty name
* short description
* progress status
* badge status

The 5 levels are:

1. **Niveau 1 — Facile**
2. **Niveau 2 — Standard**
3. **Niveau 3 — Moyen**
4. **Niveau 4 — Difficile**
5. **Niveau 5 — Expert**

Each level contains its own set of emoji/activity cards.

---

## 4. Badge System

After completing a level, the level card in the main menu must show a badge.

Badge logic:

* 🥉 **Bronze badge** = level completed
* 🥈 **Silver badge** = at least 6 correct answers
* 🥇 **Gold badge** = all answers correct

Each badge should be clearly visible on the level card in the main menu after completion.

Store progress locally using **localStorage** so that completed levels and badges remain visible after refreshing the page.

---

## 5. Gameplay

The player chooses a level from the main menu.

During the game, the player sees:

* one huge emoji in the center
* the French sport, hobby, instrument, game, or activity below it

Example:

```text
🏊‍♂️
la natation
```

The player must drag the card:

```text
⬅️ LEFT  = FAIRE
➡️ RIGHT = JOUER
```

---

## 6. Rules

* Correct answers increase the score.
* Wrong answers do not increase the score.
* After each answer, show feedback and continue to the next card.
* At the end of the level, show the final score and the earned badge.

---

## 7. Correct Answer Feedback

Correct answers trigger:

* green glow
* confetti burst
* smooth success animation
* message: **“✅ Bravo !”**

---

## 8. Wrong Answer Feedback

Wrong answers trigger:

* red flash
* shake/wiggle animation
* subtle vibration effect on supported devices
* message: **“❌ Essaie encore !”**

Wrong answers should feel playful, not punishing.

---

## 9. Animations

Include:

* smooth drag physics
* snap effect when dropped
* hover scaling
* button bounce
* shake animation on wrong answer
* celebration animation on correct answer
* smooth screen transitions
* animated badge reveal at the end of each level
* subtle floating particles in the background
* progress bar filling smoothly
* confetti on correct answers and level completion

---

## 10. UI Details

The game screen should include:

* top progress bar
* score counter with star icon
* current level indicator
* large draggable card
* left drop zone labeled **FAIRE**
* right drop zone labeled **JOUER**
* back-to-menu button
* replay level button on the result screen

The drop zones must be large and easy to use on mobile devices.

---

## 11. Content

Create **5 difficulty levels** with **8 cards each**.

---

# LEVEL 1 — FACILE

Mostly common sports and simple activities.

| Emoji | French Activity | Correct Answer |
| ----- | --------------- | -------------- |
| 🏊‍♂️ | la natation     | faire          |
| ⚽     | le football     | jouer          |
| 🎾    | le tennis       | jouer          |
| 🤸    | la gymnastique  | faire          |
| 🥋    | le judo         | faire          |
| 🏀    | le basket       | jouer          |
| 🚴‍♀️ | le vélo         | faire          |
| 🎮    | les jeux vidéo  | jouer          |

---

# LEVEL 2 — STANDARD

Mix of sports, games, and instruments.

| Emoji | French Activity | Correct Answer |
| ----- | --------------- | -------------- |
| ♟️    | les échecs      | jouer          |
| 🎻    | le violon       | jouer          |
| 🎹    | le piano        | jouer          |
| 🏃‍♂️ | la course       | faire          |
| 🧘    | le yoga         | faire          |
| 🏐    | le volley       | jouer          |
| 🏓    | le ping-pong    | jouer          |
| ⛷️    | le ski          | faire          |

---

# LEVEL 3 — MOYEN

More variety and slightly less obvious examples.

| Emoji | French Activity     | Correct Answer |
| ----- | ------------------- | -------------- |
| 🥊    | la boxe             | faire          |
| 🧗    | l’escalade          | faire          |
| 🎸    | la guitare          | jouer          |
| 🥁    | la batterie         | jouer          |
| 🏉    | le rugby            | jouer          |
| 🛹    | le skateboard       | faire          |
| 🏇    | l’équitation        | faire          |
| 🎲    | les jeux de société | jouer          |

---

# LEVEL 4 — DIFFICILE

Activities where students must think more carefully.

| Emoji | French Activity | Correct Answer |
| ----- | --------------- | -------------- |
| 🏄    | le surf         | faire          |
| 🤿    | la plongée      | faire          |
| 🏸    | le badminton    | jouer          |
| 🏒    | le hockey       | jouer          |
| 🎺    | la trompette    | jouer          |
| 🎭    | le théâtre      | faire          |
| 🧩    | les puzzles     | faire          |
| 🪁    | du cerf-volant  | faire          |

---

# LEVEL 5 — EXPERT

More advanced and mixed expressions.

| Emoji | French Activity    | Correct Answer |
| ----- | ------------------ | -------------- |
| 🧪    | des expériences    | faire          |
| 📸    | de la photographie | faire          |
| 🎤    | du karaoké         | faire          |
| 🎷    | du saxophone       | jouer          |
| 🎯    | aux fléchettes     | jouer          |
| 🃏    | aux cartes         | jouer          |
| 🏋️   | de la musculation  | faire          |
| 🧊    | du patinage        | faire          |

---

## 12. Important Language Rule

Use **faire** for general activities, sports, and hobbies.

Use **jouer** for:

* games
* team ball sports
* musical instruments

For **jouer**, use correct French forms such as:

* jouer au football
* jouer aux échecs
* jouer du piano
* jouer de la guitare
* jouer aux cartes

---

## 13. Result Screen

At the end of each level, show:

```text
🎉 Excellent !
```

Also show:

* final score
* total correct answers
* earned badge
* motivational French message
* replay button
* return to main menu button

Badge logic:

* 🥉 Bronze: level completed
* 🥈 Silver: at least 6 correct answers
* 🥇 Gold: 8 correct answers

The badge reveal should be animated with sparkles.

---

## 14. Technical Requirements

Build the game as a single-page web app using only:

* HTML
* CSS
* JavaScript

No backend needed.
No external framework required.
The app must be ready for Vercel deployment.

It must work smoothly on:

* mobile phones
* tablets
* desktop browsers

---

## 15. Important Mobile Layout Requirement

Mobile first dynamisches Design.

Do **not** rely on fixed `100vh` heights.

Use dynamic viewport units such as:

* `100dvh`
* `100svh`
* safe-area insets
* flexible vertical layouts

The app must adapt correctly to mobile browser UI bars and avoid broken vertical layouts on phones when address bars appear or disappear.

The layout should always fit properly on mobile devices.

Mobile interactions are especially important:

* touch drag must feel smooth
* drop zones must be large
* buttons must be easy to tap
* content must not overflow vertically
* no important UI element should be hidden behind browser bars or safe areas

---

## 16. Extra Polish

Add tiny micro-interactions everywhere:

* buttons bounce slightly when tapped
* level cards animate on hover/touch
* badge reveal has sparkle animation
* progress bar fills smoothly
* confetti appears on correct answers and level completion
* wrong answers feel playful, not punishing
* transitions between menu, game, and result screen feel smooth

---

## 17. Final Goal

The final result should feel like a complete, polished educational mini game that a teacher could immediately present in class.

It should be visually impressive, easy to understand, mobile-first, and fun for secondary school students.
