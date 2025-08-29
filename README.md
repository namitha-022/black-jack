# black-jack

A turn-based, single-player console Blackjack where you (the Player) play against the Dealer using a standard 52-card deck. The goal is to get a hand total closer to 21 than the dealer without going over (busting). Face cards count 10, Aces count as 1 or 11.

Initial deal: Each gets 2 cards. Player sees both of theirs and (usually) one of the dealer’s (the “upcard”).
Player turn: Repeatedly choose Hit (take a card) or Stand (stop). If total > 21 → bust.
Dealer turn: Reveal hole card; dealer hits until total ≥ 17 (treat “soft 17” as hit or stand—pick one and be consistent).
Outcome: Compare totals if no one busted. Higher total wins; equal totals → push (tie).
Aces: Count as 11 when it doesn’t bust; otherwise 1.

<img width="731" height="738" alt="image" src="https://github.com/user-attachments/assets/ed161593-db17-49a5-912d-5ce32005e790" />
