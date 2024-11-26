---
layout: post
title: A Basic Introduction to Riemannian Manifolds
author: Mica
categories: geometry
tags: math geometry manifolds
top: 1
sidebar: []
---
This was a talk I gave for the Spring 2024 Directed Reading Program at UCSD on Riemannian Manifolds. You can download the talk [here](https://github.com/li-michelle/files-upload/releases/download/pdf/DRP_Riemannian_Geometry_Presentation.2.pdf). 

We being with a definition. A **smooth manifold** is a manifold that is endowed with some "smooth structure". This means that there is a way to smoothly transition between coordinate charts. See the below figure. 

![transition-map](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-030-27237-1_2/MediaObjects/483598_1_En_2_Fig10_HTML.png)

Some examples of a smooth manifold include $$\mathbb{S}^2$$ and the torus. Now that we have established what a (smooth) manifold is, we can now begin to define a notion of length on them. In $$\mathbb{R}^n$$, length is well-defined. It is the integral of the square root of the velocity. However, on a manifold we may run into some issues because of the transition maps as they do not generally preserve length or angles. Therefore, we need to be able to define a new structure so that we can measure length and angles on a manifold. 

In general, length is velocity multiplied by time. This means that we need to be able to define the velocity of a curve on a manifold, meaning that we need to somehow have a notion of the *length* of a tangent vector. Now, the question becomes: how do we develope a notion of distance on a manifold? 

Thus, we arrive at the idea of a tangent space to a manifold. The **tangent space** at a point $$p \in M$$, denoted by $$T_pM$$ is the space of all tangent vectors at that point $$p$$. An illustration is given below 

![tangent-space](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Tangentialvektor.svg/1024px-Tangentialvektor.svg.png)

If you want to read more math, you can read about the [Riemann Roch Theorem](https://www.brianton.me/fun-stuff/arithmetic-riemann-roch/) written by my friend Brian :). 
