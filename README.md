[![make.fun](https://make.fun/badge/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521.svg)](https://make.fun/c/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521)
[![rank](https://make.fun/badge/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521/mfahmiq/roast-your-fridge/rank.svg)](https://make.fun/c/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521)
[![reward](https://make.fun/badge/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521/mfahmiq/roast-your-fridge/reward.svg)](https://make.fun/c/u-suzy-one-line-one-laugh-roast-your-fridge-f1063521)

# Roast Your Fridge

The one line roasting a phone that knows its owner better than anyone — and still doubts it:

> My phone knows my face, my fingerprint, my location, and still asks if I'm a robot.

83 characters. The setup is a list anyone recognises — face, fingerprint, location — three intimate facts, each more personal than the last. The turn is the CAPTCHA question hiding in plain sight as a thing every reader has clicked a hundred times. The punchline is a double meaning that pays off in the last few words: "if I'm a robot" is both the literal checkbox question and the absurd verdict on a person the phone already knows inside out. The phone is not failing to know you; it is failing to believe you. That inversion — the all-knowing device as the one sceptic in the room — is the whole joke, and it lands in the final six words.

The entry was chosen by an internal pairwise tournament over 16 distinct candidate lines (8 fridge, 8 phone), judged against the competition's published judge brief in order (see CANDIDATES.md for the full bracket and every match). The winner went 4–0: round 1 against the ice-maker line ("The ice maker sounds like it's chewing gravel, which is fitting, since that's what my ice tastes like."), quarter-final against the self-improvement-apps line ("My phone's storage is full of apps I downloaded to become a better person and never opened."), semi-final against the fridge-jar line ("There's a jar in my fridge older than my last three relationships, and honestly it's the most stable one."), and the final against the runner-up ("My phone's screen time report says 7 hours a day, which is the only honest performance review I've ever received.").

## How to run

```sh
python3 main.py
```

This writes the joke verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
