+++
Description = "As promised last time, we talk about the two blog-post of Tyler Akidau, in which he explains the concepts behind 'streaming' and why you should call it different."
aliases = ["/##"]
author = "Hagen"
categories = []
date = "2016-08-31T10:00:00+02:00"
episode = "9"
explicit = "false"
friendly = "ib9"
draft = true
guests = []
images = ["http://qnib.org/insert-buzzword/episode/img/ib9.png"]
news_keywords = []
podcast = "http://qnib.org/insert-buzzword/episode/audio/ib9.m4a"
podcast_duration = ""
sponsors = []
tags = []
title = "[9] - The world beyond batch"

+++

# The World beyond batch
The links to the two blog post we are talking about. The second is quite nice, as it has some video visualisation embedded.

- [The world beyond batch: Streaming 101](https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-101)
- [The world beyond batch: Streaming 102](https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-102)

# Sum-up
As we go through the blog posts, you could just read it. :) For those willing to follow along while listening, we provide a bullet-point-ish outline here.

## Part (01)1


### Background
First we make clear that we have to be precise about the terminology and the capabilities, as well as the time-domains.

### Streaming? WTF

Streaming is a mouthful, and Tyler points out the terminology should be way clearer:

- **Unbounded Data**, which are an ever growing, infinite set of data
- **Unbounded Data Processing**, the way to continuously deal with the aforementioned unbounded data...
- **Low-latency, approximate, and/or speculative results**: **DUNNO!**

### Limit of Streaming

How unbounded data and batches could work together by using the Lambda Architecture, but within the same sentence why this is a sub-optimal idea.

Segwaying somehow into, why tools for reasoning about time and correct results are much cooler and how to put this together using something like Kafka...

### Event vs. Processing Time

Yeah, this topic was touched in our very first (and very german) podcast and it will be talked about here as well.

### Data processing Patterns
#### Bounded Data
#### Unbounded Data - batch
#### Fixed Windows
#### Session
#### Unbounded Data - streaming
#### Time agnostic
#### Filtering
#### Inner-Joins
#### Approximation Algorithms

#### Windowing
##### Fixed Windows
##### Sliding Windows
##### Sessions

#### Windowing by Processing Time
#### Windowing by Event Time
##### Buffering / Completness


## Part (01)2

...




