# ChainZap Wallet Risk Taxonomy

Crypto transfers look simple.

Paste an address. Choose a network. Hit send.

The problem is that a lot can go wrong before or after that moment.

This repository is a public collection of wallet and transaction risks we think crypto users should understand before moving money.

Built by [ChainZap](https://chainzap.io).

## What we cover

We are starting with the risks we see most often around real crypto transfers:

- Address poisoning
- Fake tokens and fake USDT
- Sanctions exposure
- Suspicious services
- Counterparty risk
- Wallet behaviour
- Wrong network
- Memo / Tag mistakes
- Transaction verification

This is not a public version of ChainZap's internal risk engine.

It is a public knowledge layer around the problems we work on.

## Why this exists

Most crypto tools show you what happened on-chain.

That is useful.

But before sending money, people usually want answers to different questions:

- Is this really the right address?
- Is this token authentic?
- Does this wallet have suspicious history?
- Am I sending on the right network?
- Did the other side actually pay me?
- Is there anything here I should look at twice?

We want to make those risks easier to understand.

## Start here

Read the taxonomy:

[`/taxonomy`](./taxonomy)

Or start with our first research piece:

[`15 Ways a Crypto Transfer Can Go Wrong`](./research/15-ways-a-crypto-transfer-can-go-wrong.md)

## ChainZap

ChainZap is a crypto risk assistant built around one simple idea:

**check before you send, verify after payment.**

Current focus:

- Ethereum
- TRON
- TON

More networks will follow.

## What we do not publish here

Some parts of ChainZap stay private.

That includes:

- scoring logic
- risk weights
- internal detection rules
- provider configuration
- backend architecture
- private datasets
- anti-abuse systems

We want this repository to be useful without turning it into a blueprint of our internal engine.

## Contributing

See something missing?

Found a better public source?

Think one of our definitions is wrong?

Open an Issue or Pull Request.

We would rather improve the taxonomy than pretend the first version is perfect.

---

ChainZap provides information and risk signals, not guarantees.

A clean-looking wallet is not automatically safe.# wallet-risk-taxonomy
A public taxonomy of crypto wallet and transaction risks by ChainZap.
