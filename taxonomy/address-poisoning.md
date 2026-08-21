# Address Poisoning

You send USDT to the same counterparty every week.

One day you open your transaction history, copy an address that looks familiar and send again.

Wrong address.

That is the basic idea behind address poisoning.

## What happens

An attacker creates or finds an address that visually resembles one you already use.

They then try to make that address appear in your transaction history.

The hope is simple:

you will recognize the first and last few characters, copy it and send money to the attacker.

## Why it works

Crypto addresses are not designed for humans.

Most people do not compare every character.

They compare something like:

`TXY4...8K2P`

If the poisoned address looks close enough, that shortcut becomes the attack surface.

## What to check

Before sending:

- compare more than the first and last few characters
- do not blindly copy from transaction history
- use saved counterparties when possible
- verify large transfers from the original source

## What this signal does not prove

Two similar addresses do not automatically mean an attack happened.

Similarity is a signal.

Context decides whether it matters.

## ChainZap view

Address poisoning is one of the reasons we think wallet checks should happen before the transfer, not only after something goes wrong.

