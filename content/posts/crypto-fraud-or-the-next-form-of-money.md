---
title: "Crypto: Fraud or the Next Form of Money?"
description: "Why pyramid scheme and the future of finance are both lazy answers"
tags:
  - money
  - crypto
  - technology
date: 2026-10-19
---

*Or: why "pyramid scheme" and "the future of finance" are both lazy answers*

In the last text I followed the money trail and ended up with an uncomfortable realization: the space where people can hold and move their own wealth without asking permission has been shrinking for decades. Cash is losing ground, and accounts can be closed. The obvious next question is whether anything can bring that space back. The usual answer is crypto, and it is usually met with a shrug or a sneer.

Ask around and you will hear two loud verdicts. One camp says it is a bubble, a fraud, a pyramid scheme. The other says it is the inevitable future of finance. The two camps rarely hear each other, because they mix up three different things: the history of money, the technology of blockchains, and the casino of the market. This text tries to pull them apart. It is not investment advice. It is an attempt to understand.

## What actually stands behind money?

A popular argument goes like this: the euro or the dollar is backed by something solid, such as gold or the real economy, while crypto is backed by nothing. History tells a different story.

The gold standard faded gradually during the 20th century. The turning point came on 15 August 1971, the so-called Nixon Shock, when President Richard Nixon ended the dollar's convertibility into gold at a fixed rate. Since then, none of the leading world currencies (dollar, euro, pound, yen) has been backed by gold or other precious metals.

What we use instead is called fiat money, from the Latin for "let it be done". A 100-euro note, or a digital number in a bank account, is worth nothing in itself. Its value rests on three things:

1. **Legal decree.** The state declares it legal tender, which must be accepted as payment for debts.
2. **Taxes.** Citizens and companies must pay taxes in the national currency, which creates constant demand for it.
3. **Trust and the network effect.** It works because everyone believes that someone else will accept it tomorrow.

Money, at its root, is a social technology and an accounting record of value.

When that trust breaks, history is blunt. In Weimar Germany in 1923, prices doubled every few days, and banknotes were used as fuel for stoves. In Yugoslavia between 1992 and 1994, prices were doubling roughly every 34 hours at the peak, according to the Hanke-Krus table of world hyperinflations, with a monthly inflation rate of about 313 million percent. Banknotes worth up to 500 billion dinars were printed, and people abandoned the dinar for the German mark. Zimbabwe in November 2008 saw an estimated 79.6 billion percent inflation in a single month, according to economist Steve Hanke. In Venezuela, from late 2016 to 2019, hyperinflation pushed people toward dollars, barter and crypto.

None of this proves that crypto is sound. It does end the idea that state money is automatically safe.

## The technology is not the scam

Much of the confusion comes from treating blockchain and every shady project built on it as one and the same. A blockchain is a public, shared, tamper-resistant ledger kept by thousands of computers, with no bank, card processor or state in the middle. It is infrastructure, as neutral as HTTP or TCP/IP are for the internet.

The dot-com bubble is a useful comparison. In the late 1990s, thousands of internet companies, Pets.com among them, raised enormous sums without a workable business model. Many collapsed, and there was plenty of outright fraud. Yet the crash did not destroy the internet. Email, the web and data transfer kept carrying the global economy. In the same way, fake tokens, pyramid schemes and illegal activity on the crypto market do not disprove the mathematics of the underlying protocols.

The real breakthrough was a problem computer scientists had struggled with for decades: double spending. A digital file is easy to copy, so how do you stop a digital coin from being sent to two places at once without a central server checking? In 2008, Satoshi Nakamoto's white paper solved it by combining cryptography with a network of computers, using a mechanism called Proof-of-Work and a chronological chain of blocks.

In simple terms, it works like this. A hash function called SHA-256 turns any input into a fingerprint of 64 characters. The process is one-way: you cannot recover the input from the fingerprint, and changing a single character of the input changes the whole fingerprint. Computers in the network, the miners, race to find a fingerprint for a new block that begins with a required number of zeros. Because it cannot be guessed, they keep changing a number in the block (the nonce) and trying again, over and over. The first one to succeed adds the block to the chain and is rewarded. Estimates for the whole network in 2026 are around a sextillion guesses per second.

Owning crypto means holding two linked codes, a bit like a mailbox. The **address** works like an IBAN or a mailbox slot: you can show it to anyone, and they can drop money in or look at the balance, but they cannot take anything out. The **private key** is the only key that opens the mailbox. Whoever has it controls the funds, so it must be kept strictly secret, and if it is lost, nobody can recover it for you. Wallet apps hide this complexity: they create the keys for you and let you back up the private key as a recovery phrase of 12 or 24 words. (Behind the scenes, the address is generated from a so-called public key, but you never need to deal with that.) Once the network is running, not even its creator can delete or alter the recorded blocks or change the rules, because those are decided by the consensus of thousands of independent computers around the world.

## Three layers, not one

To avoid generalizing, the crypto world should be viewed as three separate layers.

| Layer | What it does | Examples and traits |
| --- | --- | --- |
| Technology | The base infrastructure: a public, auditable, tamper-resistant database spread over thousands of computers | The Bitcoin and Ethereum networks, with no single point of failure |
| Monetary and functional | Core protocols and applications | Bitcoin has built-in scarcity, with at most 21 million coins. Ethereum adds smart contracts that execute agreements automatically |
| Speculative | The market of tokens and new projects | Very high risk: an enormous number of tokens, extreme volatility, little regulation and many worthless projects |

Judging all three as one is like judging the whole internet by its spam folder.

## What the technology improves

Traditional finance still relies on structures built in the last century. International bank transfers, for example over the SWIFT network, can take days, cost high fees and depend on bank working hours. Crypto networks bring a few concrete improvements.

- **Global access, 24/7.** Anyone with an internet connection can send or receive value anywhere on the planet in seconds to a few minutes, regardless of holidays, bank hours or borders.
- **Transparency.** Every transaction on a public blockchain is recorded permanently and visible to everyone. It is practically impossible to print new units or change balances in secret. This is also the flip side of the privacy point from the last text: public blockchains are traceable, not anonymous.
- **Programmable money.** Smart contracts on networks like Ethereum run financial agreements automatically once agreed conditions are met, which removes slow and expensive middlemen from many processes. A vending machine is the classic comparison: you insert the coin, press the button and the product drops, with no cashier involved. A smart contract can work the same way for money. Imagine one that says: "if a flight is delayed by more than two hours, send 50 euros to the passenger". Once official flight data shows the delay, the payment goes out automatically, with no claim form and no clerk. The word "programmable" also came up in the debate about central bank digital currencies, where it raised concerns. The difference is who writes the rules. With a smart contract, the people involved choose the code they agree to. In a central bank currency, the rules are set by the central bank and the government, so limits on spending would be imposed from above.
- **Censorship resistance.** No single authority can freeze a wallet on a decentralized network or reverse confirmed blocks. One caveat matters, though. Stablecoins such as USDT and USDC are issued by companies, and those companies can and do freeze addresses. In April 2026, for instance, Tether froze more than 344 million dollars in USDT in coordination with US authorities, after the funds were flagged as linked to illicit activity. It can do this because the token's code contains a blacklist that only the company controls. Exchanges that convert crypto into regular money also require identification. Resistance is real at the protocol level, but most people reach crypto through points that are not resistant. So crypto is not all decentralized: the networks are, but many of the products built on them are not.

## The honest limits

Any fair analysis has to name the weak spots. Crypto sits at different stages depending on what you measure. For everyday money it is still early: almost nobody is paid or shops in crypto, because it is too volatile and too technical. As an investment it is further along: Bitcoin is 17 years old, large institutions hold it, and US regulators approved Bitcoin exchange-traded funds in 2024. Either way, it faces real obstacles.

- **Scalability.** It is very hard to achieve maximum decentralization, top security and high speed at the same time, a problem known as the blockchain trilemma. Ethereum's base layer handles around 15 transactions per second. So-called Layer 2 solutions, built on top of it, are being developed to handle far more. Projections reach up to 100,000 transactions per second, but those remain projections.
- **Volatility.** Because the market is speculative and small compared with global finance, prices of coins like Bitcoin swing drastically. That makes them impractical for pricing everyday goods, which is why stablecoins pegged to the US dollar were created. They bring their own dependence on an issuer, as noted above.
- **User responsibility.** Looking after your own private keys takes technical skill. A mistyped address or a lost password can mean permanent loss of funds, with no customer support to call.
- **Energy.** Proof-of-Work uses a great deal of electricity by design, which is a standard criticism of Bitcoin. Ethereum moved from Proof-of-Work to Proof-of-Stake in September 2022, in an upgrade called the Merge. Instead of computers racing to solve puzzles, validators lock up their own coins as a deposit and are chosen to confirm blocks, and they lose part of the deposit if they cheat. Energy use fell by roughly 99.95 percent. For the future, this shows that crypto's electricity problem is not permanent: a network can change its rules to fix it. Bitcoin has stayed with Proof-of-Work, and critics of Proof-of-Stake argue that it favors those who already hold the most coins.

## Fiat money and crypto, side by side

|  | Fiat money (USD, EUR, RSD) | Bitcoin and leading cryptocurrencies |
| --- | --- | --- |
| Basis | State decree, legal tender, tax obligation | Cryptographic proof, code, distributed network |
| Supply | No fixed cap; central banks adjust it within their mandates | Set by the program and capped, for example Bitcoin at 21 million |
| Control | Centralized: central banks and finance ministries | Decentralized: consensus of thousands of independent computers |
| Speed | Fast locally; international transfers can take one to five business days | Fast globally: seconds to a few minutes |
| Transparency | Private bank ledgers; audits are periodic and closed | Open, publicly auditable ledger of transactions |

## So, fraud or evolution?

At its core, crypto is neither a fraud nor a pyramid scheme. It is a new technological and economic model for moving, storing and managing value in the digital age. Like every major technology in its early years, from the steam engine to the car to the internet, it comes with wild swings, failed experiments and people who exploit the confusion. The honest approach is to separate the mathematics from the froth on top of the market, and to judge each on its own merits.

Money has changed form whenever trust in the old form wore thin: from shells and salt to gold, from gold to paper, from paper to numbers on a screen. The question for our generation is who writes the rules of the next form, and whether the rest of us get a say.

*These are my own views, shaped by research I do in my free time on many different topics. This is one of them. I don't ask anyone to agree, only to look at the question with open eyes. Every form of money we take for granted was once a strange experiment. Whether crypto joins that list or fades into a footnote will be decided by what people build and what they choose to trust. So, will crypto become a lasting part of how the world moves and stores value, or stay at the margins? Tell me where you stand, and why.*

---

## Sources

- [Cato Institute: Hyperinflation, Mugabe versus Milosevic (Hanke)](https://www.cato.org/commentary/hyperinflation-mugabe-versus-milosevic)
- [Planet Banknote: Yugoslav hyperinflation](https://learn.planetbanknote.com/hyperinflation-yugoslavia/)
- [Johns Hopkins Magazine: What hyperinflation looks like (Hanke's Zimbabwe estimate)](https://magazine.jhu.edu/2009/08/27/what-hyperinflation-looks-like)
- [Hanke and Bushnell: Venezuela's hyperinflation (Johns Hopkins)](https://sites.krieger.jhu.edu/iae/files/2018/02/Hanke-Bushnell_Venezuela.pdf)
- [KuCoin: Bitcoin hashrate in 2026](https://kucoin.com/blog/in-bitcoin-hashrate-in-2026-latest-trends-mining-difficulty-network-security-analysis)
- [AMLBot: stablecoin freezes, USDT vs USDC](https://blog.amlbot.com/stablecoin-freezes-2023-2025-a-data-backed-analysis-of-usdt-usdc-by-amlbot/)
- [Decrypt: Tether freezes $344 million in USDT](https://decrypt.co/365278)
- [ethereum.org: The Merge](https://ethereum.org/roadmap/merge)
- [Zerocap: The Ethereum Merge](https://zerocap.com/the-ethereum-merge-updates-what-are-the-main-changes-in-the-ethereum-network/)

