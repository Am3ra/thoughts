---
---


Tags: [[Deep Learning]]

This project is an attempt to use what I've learned from my deep learning classes.

Its purpose or goal is to not only cement the learnings, but also predict baseball games to a high degree of accuracy, in order to maybe even win some money.

- [Todo](#todo)
- [Architecture](#architecture)
	- [Inputs](#inputs)

## Todo

The most important thing to do right now is to figure out how to use the data I have. The most promising source that I have is retro sheet, as well as the lahman baseball database. I need to know how to make batches of input in order to process the data.

The idea is to incrementally build up my model, and measure the accuracy as I go.

## Architecture

I'm thinking of using a siamese architecture to encode the data input from both teams, and then a decoding network to take the encodings and assign the win probability to each team.

In terms of inputs, this is all very new to me, so my plan is to start slow and build my model up in order to build up my intuitions.

### Inputs

I'm using the python library: pybaseball2 in order to get my data at the moment, I'm considering using basic stats such as current record (W/L this season), as well as W/L for last 50 games, last 10, and last 5. Maybe even last 100.

