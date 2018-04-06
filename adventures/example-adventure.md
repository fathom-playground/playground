---
start-date: 2018-04-03
home: "https://github.com/chronaeon/beigepaper/"
address: 0x0123
adventurers: 1
---

# Learning about the EVM by re-writing the Yellowpaper

Many DApps built on Ethereum have had issues from the development layer bubble
up to the user layer, in the form of bugs, required flows, and strange
edge-cases. 

Below the development layer, which leverages Solidity and libraries like Web3,
is the protocol layer, consiting of the EVM and ethereum protocol. In order to
properly develop these applications it's important for developers to understand
this foundtational layer.

I've worked on building user-facing apps, both on the front-end and
smart-contract side, and feel that I have been limited by my lack of
understanding of EVM internals.

## Learning through re-construction
I want to build my own understanding of this layer, while making it easier for
others to do in the future. 

The [ethereum yellowpaper](https://github.com/ethereum/yellowpaper) is the
canonical source for the Ethereum protocol. It's extremely in-depth but has been
criticised for inaccessibility and a lack of clarity. Part of this is due to
it's reliance on mathematical notation. I beleive that a simple english (like
simple.wikipedia.org) rewriting of the yellowpaper, keeping the same structure
and contents, would be an incredibly useful resource for people encountering
Ethereum or the EVM for the first time.

For myself, explaining a concept in simpler terms is a challenge that drives
understanding. Starting from the original document gives me a clear structure to
work within, and a clear goal to work towards.

## What I will produce
Each week I will aim to rewrite 1-2 sections of the yellowpaper based on top level
headings.

By the end of the adventure I hope to have at minimum 70% of the yellowpaper complete.

## Measuring readibility and accuracy
In order to test my writing I plan to be actively sourcing feedback through the
writing process. 

### Process

1. For every section of the whitepaper I will get 2 participants, one familiar
   with the Ethereum protocol and one new to it. 
2. They'll both read the section (and preceding sections if neccessary) and
   seperately write down any questions they have
3. Then, they'll have a 20-40min conversation about the section, which will be
   recorded. 
   
All these steps will be done without my involvement. The goal is to get data on
how individuals interact with the documentation. I hope that this will be feed
back into my own learning as I can see how different parties interact with the
ideas. 

### Reproducibility
I hope that this process could be iterated on and become a driver for
documenttion in general. This is not an area I have a lot of knowledge in so if
other's have different frameworks or ideas that they could point me to, I'd love
to learn and build on them.
