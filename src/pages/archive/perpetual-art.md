---
layout: ../../layouts/PostLayout.astro
title: Perpetual Art
date: '2023-07-18'
tags: ['NFTs', 'Art', 'Perpetual Storage']
Summary: Even NFTs need maintenance.
images: []
---
Some say that only a few decades after Leonardo da Vinci finished The Last Supper, the piece of art was starting to come apart. But regardless of its initial state, it's certain that Napoleon's troops didn't improve it a few hundred years later during a campaign in Milan when they used the mural for target practice. The Allies didn't help either by bombing Santa Maria delle Grazie in 1943, the church where it's located.

Since much new art is digital, it's a lot harder to drop bombs on it these days. The only war this art will lose is against time, ending up lost or forgotten. Either that or against an army of remixers who drown an original in fakes.

To prevent both of these things from happening, some new art is stored as NFTs on a blockchain. But it can still be lost - not only as in being forgotten but as in disappearing. The current architecture of most NFTs doesn't ensure permanence, largely because it's too expensive to store art directly on the blockchain. Instead, creators insert a URI in the NFT that usually points to IPFS or Arweave. But there are problems with both of these systems.

IPFS doesn't guarantee decentralized permanent storage, because storage happens outside of it. IPFS only facilitates file transfer, like with torrents. The link is persistent but there's no inherent guarantee of storage. The perishability will become evident over time, disappointing owners of NFTs not so well-versed in their technical intricacies who counted on their collection to be permanent and weren't storing it properly themselves.

Arweave, a blockchain built specifically for file storage, tries to fix this. The current issue with Arweave is that the URI, permanently stored in the NFT, that points from the NFT to the file containing the art, isn't decentralized - it nearly always points to arweave.net, a centralized domain that may shut down.

While most who know something about NFTs probably see these issues, there's still reason to believe that NFTs are viable for long-term art storage. Even though NFTs aren't currently perfect, they're better than any alternative. They're also improving and the existing problems are solvable.

The problem with IPFS, for instance, might be solved by pinning IPFS art to a decentralized service that ensures that it's hosted on a IPFS node. There are efforts on this, by using Arweave as a way to pin IPFS files, but there's still some way to go. And if arweave.net shuts down, developers will probably figure out ways to restore the URI's functionality, for instance through a smart contract that burns or stores the NFT in return for a new one that circumvents the current domain.

More generally, I don't think there will ever be a static system that guarantees permanent intactness. It's the goal but we will never arrive. Important objects and information survive only because people take care of them. That's why it's a mistake to believe that the system is useless until it's perfect, because it never will be. Even if it were economically possible to store art directly on Ethereum, eventually Ethereum itself will break unless someone works to prevent that.

The Last Supper is roughly 530 years old, a long time for something that started to fall apart only years after being created. It remains because art conservators make an effort to preserve a piece that would otherwise have crumbled centuries ago. Similarly, digital art on the blockchain might survive, but only because modern-day art conservators work to ensure that.
