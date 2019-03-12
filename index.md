---
layout: page
title: Hyyek
---

( Rough Draft )

Hyyek is a hard fork of Bitcoin Core. It allows users to spend to Drivechain scripts.

Unlike previous hard forks:

1. It does NOT compete on: development; usage; being listed on an exchange; or the "Bitcoin" name.
2. It doesn't actually change *any* consensus rules. It just resets the difficulty one time (in order to force a second network to appear). On *that* new network, Drivechain immediately activates as a soft fork.
3. It will be announced well in advance.

## FAQ

### 1. How many developers do you have? ### {#devs}

This project is not competing on development.

The non-Drivechain parts of the codebase will always be identical to Bitcoin Core. When/if future inventions are merged into Core (such as: sighash-noinput, Confidential Transactions, etc.), we will just click the merge button ourselves.

So, all Bitcoin Core developers are working on this project, whether they want to or not.

### 2. How many people, do you think, will use this software? ### {#users}

The project isn't competing on users, either.

The replay protection is [user-controlled opt-in](http://www.truthcoin.info/blog/garp/). So it is off by default which means that, if no one does anything, every single transaction in the next Bitcoin Core block, will be immediately replayed into the Hyyek mempool and end up in the next Hyyek block.

So, all BTC users are transacting on this blockchain, whether they want to or not.

### 3. How many exchanges do you think will list the coin? ### {#exchanges}

This project is not competing on "getting listed", either. If exchanges do not list the coin, you can simply replay attack them and acquire the coin for free.

So they will probably be forced to list the coin, whether they like it or not.

### 4. Won't Bitcoin Core just copy this idea if it is successful? (If so, then what is the value proposition of this coin?)

There is a good chance that the answer is no.

Drivechain's security assumptions would require Core to add it via a MASF (miner-activated soft fork). But Core miners would be unlikely to go along with this, because if they believe in Drivechain they could instead just switch to mining Hyyek. The PoW-algos are the same, and Hyyek will be more profitable to mine because its network difficulty will be lower. And Hyyek would be identical to Core, because its codebase would be exactly the same, and its userbase would also be the same -- the only exceptions being those users who intentionally split their coins in order to bet *against* Drivechain.

[More](http://www.truthcoin.info/blog/imex/).

### 5. If you want to leave BTC, then why not "build on top of" BCH (or BSV)?

BCH had a [clumsy launch](http://www.truthcoin.info/blog/garp/#ii-bitcoin-cash), has [fewer users](https://bitinfocharts.com/comparison/transactions-btc-bch.html#1y), a much smaller marketcap, and less R&D. Its software has been altered significantly, and unnecessarily. These qualities act to repel people who are strategic, sociable, sophisticated, technically-minded, and prudent. The decision to support larger blocks did *not* solve the scalability dispute -- it just picked one side over the other. The decision to hard fork, was anti-cooperative and set the stage for endless fracturing of the community (ie, BSV).

BSV has all of these problems, only worse.

### 6. How do you plan to succeed without partnering with Blockstream / Bitcoin.com / an eccentric Australian?

If the project is good, the right partners will find *it*.


<!--

### 5. Are Hard Forks Evil?

Opinions on them differ. [I've argued](http://www.truthcoin.info/blog/against-the-hard-fork/) that they set a horrible precendent. [Others](https://twitter.com/spencernoon/status/933135469520531456) have [different](https://www.youtube.com/watch?v=6-ms68Ircus) views.

-->

## Contact

<p><u>Email:</u> truthcoin /at/gmail/</p>
<p><u>PGP Key:</u> <a href="https://pgp.mit.edu/pks/lookup?op=get&search=0xAA4B3330F162C410">F162C410</a></p>
<p>I'm usually on <a href="https://twitter.com/Truthcoin">Twitter</a> 8-9 AM and 5-6 PM.</p>

