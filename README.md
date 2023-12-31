# ZK Card Game Implementation Based on Mental Poker

## Project Overview

This project presents a Zero-Knowledge (ZK) implementation of card games rooted in the principles of Mental Poker.

## Features

### Atomic Card Operations:

#### For a Single Card:
- **Creation**: Produce a single card.
- **Mask**: Encrypt a card to hide its identity from some playrs.
- **Unmask**: Decrypt a masked card to reveal its identity to some players.
- **Remask**: Apply multiple layers of encryption to a card from some players.

#### For a Deck of Cards:
- **Shuffle Deck**: Randomize the order of cards in a deck, some/all players may participate in the shuffling and it provide zkp for each shuffle.
- **Split Deck**: Divide a deck into two or more parts, similar as above, some/all players may participate in this operation.
- **Draw**: Take a card from the deck.
- **Reveal to Arbitrary Number of Players**: Allow any number of users to see a specific card.

### Zero-Knowledge Proofs:

All operations are enhanced with zero-knowledge proof with ZK Snark, ensuring transparency and fairness. Every game function generates a corresponding Zero-Knowledge Proof (zkp) to guarantee the process's fairness and transparency.

## License

This project is licensed under the MIT License.