# Fake Tokens

A token can say `USDT`.

That does not mean it is USDT.

On-chain, anyone can create a token with a familiar name, ticker or logo.

The contract is what matters.

## The problem

A fake token may copy:

- name
- symbol
- icon
- decimals
- branding

To a user looking at a wallet screen, it can appear almost identical to the real asset.

## Typical scenario

Someone says they paid you 5,000 USDT.

Your wallet shows:

`5,000 USDT`

Looks good.

But the token contract is not the official USDT contract.

The payment is effectively worthless.

## What to check

Look at:

- token contract
- network
- issuer information
- trusted token registry
- whether the token has real market activity

Do not use the symbol alone as proof.

## Important distinction

Fake token and malicious wallet are different problems.

A normal wallet can hold a fake token.

A risky wallet can hold a legitimate token.

Those signals should not be mixed together.
