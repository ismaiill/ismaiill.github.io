---
title: Attention mechanism 
description: This article explains the attention mechanism in a simple way.
lead: This article explains the attention mechanism in a simple way.
date: 2022-01-24T14:00:00.000Z
tags:
  - "New Post"
authorbox: false
sidebar: false
pager: false
draft: true
---
Image you want to translate the following sentence from English to French: The world is amazing. In this day and age, you have two options. Either you take a one semester course in French, learn how to say baguette and croissant and try to translate the above sentene. More likely than not, you will fail, in which case you will open an LLM terminal and ask an AI do it for you. In this blog, I will not give you French lessons. We will try to understand what the LLM did for you, step by step. We will follow what happens exactly inside the attention mechanism, and along the way we will explain in details each component and its role. Let's start wit the very step, tokenization.  

## Tokenization
Conputers don't understand words, they can only read binaries, a series of electric signals inside the billions of transitors that make up modern computers (if you are using an Apple M2, there are about 13 billions of them).  So the job a tokenizer is to transform out inital sentence into a series numbers readable by the computer. There are many way to construct a tokenizer. The most natural one is to encode each character of the English language and voila. The issue with this idea is that it creates really long sequences of numbers and that is computatinally inefficent: we want to minimaze the number of computations and having a really long sequence of numbers to process won't help! So we need to think of something else.


## Attention

## Self-Attention

## Multi-Head Attention