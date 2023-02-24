---
title: "What's up with IsaacScript?"
date: 2023-01-20
layout: post
tags: [tboi, informative]
---

## Table of contents

- [Introduction](#introduction)
  - [What is Isaacscript?](#what-is-isaacscript)
  - [Where is this going?](#where-is-this-going)
  - [The gist of it](#the-gist-of-it)
- [The good](#the-good)

## Introduction <a name="introduction"></a>


Before I start, I want to mention that this post is **not** about the creator of IsaacScript, Zamiel. I don't want to fuel the fire of drama involving him because it's quite pointless. A small amount of context on him is important to understand the rest of the article though, so I'm going to try and do my best to explain what IsaacScript is and why many people refuse to consider it as an option.

#### What is IsaacScript? <a name="what-is-isaacscript"></a>

Isaac mods are coded in Lua. Lua is an easily embeddable coding language that is used by many games written in C/C++ that have modding support. It is dynamically typed and it has fairly simple syntax.

That sounds fairly desirable, so what's the big deal? Because of the fact that Lua is dynamically typed, there is no type safety. Type safety means that the compiler will validate that variables are the correct type. If they aren't it'll throw an error.

The point of having type safety is so you can immediately know if you made certain mistakes. If something requires an integer (a whole number), providing it a float (a number with a decimal) is going to cause an error. Without type safety, you won't know that it'll break until it happens. Essentially, type safety makes development quicker and less of a headache.

Type safety is great, but it isn't required. You don't *need* it to write solid code. Some people don't care for type safety, while others treat it as gospel. At the end of the day, it's more of a preference thing. Some languages have it and some don't, but that doesn't make one language objectively bad compared to the other.

#### Where is this going? <a name="where-is-this-going"></a>

TypeScript is a language derived from Javascript, which is a language used in web development. TypeScript is strictly typed and guarantees type safety. Zamiel, a big fan of TypeScript[^1] and a big non-fan of Lua[^2], decided enough was enough and that he's going to recreate the entire Isaac API in TypeScript along with countless other features in a way that compiles seamlessly and swiftly into Lua code.

Wow! That's incredibly ambitious. But you know what? It works! It works pretty damn well. There are likely hundreds of useful (and not so useful, more on that later) helper functions that genuinely do speed up development of mods. It has an impressive library for creating custom stages and an intuitive save data manager.

This has got to be *the* thing to change modding forever, right? There are so many amazing features with hundreds of hours of labor put into them. So then, what's wrong?

It's a bit complicated.

#### The gist of it <a name="the-gist-of-it"></a>

I tried out IsaacScript briefly for about two weeks. In this article, I'm going to go over my first impressions and try to give some pros and cons for the tool.

Remember that this is about the tool itself, not TypeScript. I think it's a little misleading to attribute the inherent benefits of TypeScript to IsaacScript.

## The good <a name="the-good"></a>

First, let's go over the things I really enjoyed about IsaacScript, as it wouldn't be fair to only be negative.

#### 

[^1]: https://i.imgur.com/2w9AbAc.png
[^2]: https://i.imgur.com/wxklnK6.png