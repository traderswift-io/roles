# Security reviewer

## What it is

Signer is a threshold-signing chain for agent orders. No single machine holds a whole key; shares are split and orders are signed together. It's been live since 12 November 2026.

So far it's been reviewed by software. We want a human read.

## What you own

- **How Signer holds and splits keys.** Say where it's weak.
- **Key ceremonies.** How keys are made, split and moved. Is each step sound?
- **Admin powers.** Who can change what, and what happens if that power is misused.
- **Each accepted risk.** You judge whether each risk we've chosen to carry is acceptable for now.
- **Scoping a paid audit.** What an outside audit should cover, and what a good one looks like.

## What you don't

Code changes, trading, money, live keys, hiring. You never need a key to do this work. Product decisions stay with the founder.

## Your week

About 4 hours.

- **1 hour doing:** write up one finding, or one section of the audit scope.
- **3 hours thinking:** read one part of the design or code, follow how a key moves through it, and decide what could go wrong.

## Who it suits

Someone who has reviewed key management, MPC or threshold signing, or custody systems. You'd rather find the problem now than read about it later.

## How to say you're interested

Reply to whoever sent you this, or open an issue in this repo.
