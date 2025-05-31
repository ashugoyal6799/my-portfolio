---
title: "Dead Code and Sentimental Value: Why We Keep What We Should Delete"
date: 2025-05-18T12:00:00+00:00
draft: false
author: "Ashu Goyal"
tags:
  [
    "Software Development",
    "Code Quality",
    "Technical Debt",
    "Psychology",
    "Best Practices",
  ]
categories: ["Technology", "Software Engineering"]
description: "A deep dive into why software teams struggle to delete unnecessary code and how the psychology of sentimental value affects engineering decisions."
---

A strange thing happens in software teams: we often know some code should be deleted, but we leave it in. Sometimes it's commented out, sometimes moved to a "backup" file, sometimes just left there quietly collecting dust. We tell ourselves it might be useful later — but deep down, we know it won't.

So why do we keep it? Not because it's important, but because **deleting it feels risky**. What if it breaks something we've forgotten? What if it was written by someone senior? What if we just don't fully understand it anymore? Sometimes it's just easier to ignore it than to clean it up.

## The Hidden Cost of Keeping Code

But here's the thing: keeping code is still a decision. That code still gets read, maintained, misunderstood, and debugged. It becomes noise. It slows down new engineers. It adds weight we forget we're carrying — until something breaks and we have to dig through it again.

## Simple Rules for Code Cleanup

I've learned a few simple rules:

- **If you're afraid to delete it, write a test first**
- **If nobody knows what it does, that's a red flag, not a reason to keep it**
- **If it hasn't been used in over a year, it's probably already dead** — you're just giving it free rent in your codebase

## The Psychology of Code

Code doesn't have sentimental value. We do. And sometimes that's what gets in the way of good engineering.

The truth is, **cleaning up is part of building**. Every line of code we keep is a choice about what kind of system we want to maintain. Every function we leave "just in case" is a bet against our future selves.

Don't let the old code haunt the future.

---

_Have you ever found yourself reluctant to delete code that you knew was unnecessary? What strategies have helped you overcome this in your team?_
