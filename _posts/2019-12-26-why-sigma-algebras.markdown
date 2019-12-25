---
layout: post
title:  "Why do we need sigma-algebras?"
date:   2019-12-25 05:52:00 +0200
categories: [probability theory, measure theory, sigma-algebra]
---

Anyone who has undergone a somewhat formal introduction to probability theory has stumbled upon the triplet $$(\Omega, \mathcal{F}, \mathbb{P})$$. Those are interpreted as follows: $$\Omega$$ is the *sample space* that is comprised of all elementary events (or all possible atomic outcomes of a random experiment), $$\mathcal{F}$$ is a $$\sigma$$-algebra (a.k.a. $$\sigma$$-field) that contains all events that we care for (an *event* $$A\in\mathcal{F}$$ is, of course, just a subset of $$\Omega$$) and, finally, $$\mathbb{P}$$ is a *probability measure* which assigns a number between 0 and 1 to each event of $$\mathcal{F}$$.