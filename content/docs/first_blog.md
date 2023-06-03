---
title: "Fast and Secure: Unveiling zkHub's Cutting-Edge Proof Generation Technique"
date: 2023-06-03T11:32:29+05:30
draft: false
---

Hello World!

We're thrilled to bring to you the inaugural blog post for zkHub - the future of proof generation that champions privacy above all else. It's highly likely that you've stumbled upon zero-knowledge proofs if you've had any engagement with the world of cryptocurrency. 

Zero-knowledge proofs are the art of convincing without giving away the secret. It's like performing a magic trick where you demonstrate your knowledge, but the audience, though convinced of your knowledge, remains baffled about how you did it!

This takes cryptography to an entirely different level. Traditional cryptography techniques serve two primary functions in the digital realm:

Firstly, they can help to maintain the confidentiality of information that only you know. For example, your private key in the blockchain network is known only to you and cryptography helps to keep it safe from other participants.

Secondly, these techniques enable you to prove that you possess something that everyone is aware of. In a blockchain network, you can use your private key to generate a signature, proving that you are the owner of a specific public key or a set of digital coins without revealing your private key.
However, these traditional methods have limitations. Specifically, you can't simultaneously keep something private (i.e., withhold the actual information) while also publicly proving that you own it, because that would require revealing the very information you're trying to keep secret.

With zk-proofs, you can do both at the same time!

This enables different kinds of use cases - 

**Composable Identity Solutions**

Social Media users can anonymously prove their age, personal information, and the authenticity of their profiles without revealing sensitive personal data. 

DeFi users can prove their creditworthiness without revealing any personal data 

 ****************Multiplayer Games that stay forever****************

Typically, “blockchain games" store only a specific part of the game’s mechanics on-chain (in-game items as NFTs). The state and logic of these games still reside on traditional servers. 

With advancements in the scalability and speed of blockchains, there are engines like [MUD](https://mud.dev) that enable the building of games whose state and logic reside on the blockchain too! 

Not only this but multiplayer games can now be built on the blockchain too! 

Traditionally, multiplayer games are NOT peer-to-peer because a server is responsible for keeping checks on dishonest players and to maintain the same state of the game for all the players. With zero-knowledge proofs, games can verify that the player is not cheating, and the blockchain can maintain the same state for all players, negating the need for servers altogether! 

Games like [dark forest](https://blog.zkga.me) already have thousands of players demonstrating that this is possible and scalable.

## This is amazing, what's the catch? 

Powerful as they are, zk proofs come with their own limitations.

Zero-knowledge proofs are expensive to generate (both in terms of memory and computation)

The creation of proofs is often slowed down by the need for numerous complex mathematical operations.

As the complexity of the computational problem increases, the memory, computation, and time required to generate the zk proof also increases.

A single zk proof can take hours to generate. Proof generation on the phone is next to impossible.

![Waiting for proofs to generate](/images/waiting.png "Waiting for proof generation without zkHub")

Developers have been searching on the web to find solutions to this problem. Here is a chat from the iden3 telegram group - 

```
Son Pin - "How do I speed up the proof generation?"
Jan - "Get more cores"
Son Pin - "Really? 😭 Is there no other way?"
```

There is now, Mr. Son Pin! zkHub is just for you!

## zkHub

zkHub lets entities with idle computation (or specialized hardware) at their hands plug into its network and connects them with entities who want to generate zk proofs.

You might have concerns about sharing your confidential witness data with us. It is understandable that such information is highly sensitive and requires careful handling to maintain its privacy and security. 

The goal of zkHub is to **outsource proof generation while maintaining privacy**.

zkHub takes away the overheads of proof generation for companies. It provides the infrastructure required to generate proofs **quickly**, and **without the need to expose the sensitive data** required for proof generation, hence maintaining privacy.

Instead of sharing the data required for proof generation with a single authority, zkHub uses MPC to split up the secret inputs into multiple chunks during a pre-processing phase (all on the client side) and then distributes the proof generation task to multiple nodes, hence resulting in faster proof generation. 

The proof generator nodes communicate with each other to generate the proof in such a way that each individual prover is obfuscated to the secret input of the other provers. There are computationally-inexpensive checks done here as well to ensure that each prover is generating its part of the proof honestly.

This approach guarantees that the secret data remains unknown to any individual node in the network.

![MPC nodes in zkHub network](/images/spidernodes.png "Nodes in the zkHub network")

Using this novel technique to generate zk-proofs, zkHub enables

- Up to **40x** increase in **proof generation times** compared to generation times on mobile phones.
- Build up to **250x** larger circuits in terms of size and complexity.

All of this without sacrificing privacy!

And there you have it, folks! The world of proof generation is set to undergo a major transformation with zkHub. We're setting the stage for a future where privacy doesn't have to be compromised for proof generation, and where complex problems can be solved faster, without burning out your hardware. Isn't that exciting?

We truly believe in the potential of zkHub to revolutionize how we handle computation in the digital realm. However, this journey is just beginning and we want you to be a part of it. From sharing ideas to exchanging thoughts on developments, we're eager to connect with you.

We'd love for you to join us on this exciting journey. If you're intrigued by the potential of zkHub or simply want to stay updated on our progress, why not give us a follow on [Twitter](https://twitter.com/zkHubHQ)?

Furthermore, if you're interested in what we're building and would like to contribute, or simply have a chat about the endless possibilities, we'd be delighted to hear from you. Drop us a direct message on Twitter if you want to reach out. We’re always looking for like-minded individuals to join our community.

Until next time!
