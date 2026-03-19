# Blackjack

A fully playable browser-based Blackjack game built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies — just open and play.

## Live Demo

[Play it here](https://paulburakov.github.io/blackjack)

## Features

- **Betting system** — $5, $10, $25, $50, and $100 chips
- **Double down** — available on your first two cards
- **Dealer AI** — hits on 16 or below, stands on 17+
- **Blackjack payout** — 3:2 on a natural blackjack
- **Stats tracker** — tracks wins, losses, pushes, and net profit
- **Auto-reload** — reloads $500 if you go broke

## How to Play

1. Click chips to place your bet
2. Hit **Deal** to start the round
3. Choose **Hit**, **Stand**, or **Double** based on your hand
4. The dealer reveals their card and plays automatically
5. Closest to 21 without busting wins

## Card Values

| Card | Value |
|------|-------|
| 2–10 | Face value |
| J, Q, K | 10 |
| Ace | 11 (counts as 1 if busting) |

## Run Locally

No setup needed. Just clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/PaulBurakov/blackjack.git
cd blackjack
open index.html
```

## Built With

- HTML5
- CSS3
- Vanilla JavaScript

## Author

**Paul Burakov** — [GitHub](https://github.com/PaulBurakov) · [LinkedIn](https://www.linkedin.com/in/paul-burakov-645063293/)
