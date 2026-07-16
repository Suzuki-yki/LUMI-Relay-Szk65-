# Week 2 | AI-assisted Dev Plan

## What is the minimum feature I want to build?

**LUMI Relay** lets a user change one trait of a base LUMI character—hair, outfit, or palette—and create a Remix. With a wallet, they can publish it as an NFT on Monad testnet and link it to its parent character.

## Who will use it?

People who do not understand blockchain but enjoy dress-up games, avatar creation, and sharing. It also targets Monad Builder Camp participants.

## What is one action the user completes?

The user clicks **“Continue this LUMI,”** changes one trait, and clicks **“Publish my Remix.”**

## Which 1–3 documents do I need to read?

1. Monad testnet network information.
2. Monad Remix deployment guide.
3. OpenZeppelin ERC-721 documentation.

## What will I actually implement this week? What can be mocked?

### I will actually implement

- A LUMI preview page with selectable traits.
- Wallet connection and a minimal ERC-721 contract.
- A `createRemix` function that stores the parent ID and traits.
- Monad testnet deployment and one published Remix NFT.

### I can mock

- Fixed 2D character assets.
- Local mock data for the gallery.
- Custom asset uploads, AI moderation, marketplace, voting, and rewards.

## How will I prove that it is built?

I will provide a GitHub repository, frontend screenshots or recording, the Monad contract address, a Remix transaction hash, and a short demo: **choose → connect → publish**.
