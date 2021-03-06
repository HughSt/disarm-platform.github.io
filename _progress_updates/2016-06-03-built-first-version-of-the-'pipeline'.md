---
layout: post
title: Built first version of the 'pipeline'
post_date: '2016-06-03'
image: DiSARM_Pipeline_2
published: true
---

We want to use DiSARM to remove as many of the technical barriers as possible, making it easy use data and information that’s already been collected. The automated risk modelling and mapping approach [insert link to HS article] was a really important start, but we needed a way to make that process run regularly on its own, gathering the inputs it needs, and creating the full range of outputs needed. And avoiding the need to have R expertise to run the models.

We settled on a ‘pipeline’ concept, that can be configured, and then run as needed. For example, we tell it where to find the EarthEngine exports [insert link to information on EE exports], and how to clean up case data, and from then it needs no more interaction to create the risk map outputs.

This pipeline has been built and tested for Matabeleland South (Zimbabwe) and Swaziland.

See here [insert link!] for information on how we’re handling the project’s code. It runs on both Windows and Linux (as well as Mac for development).

UPDATE: We are currently building a user-friendly interface to this, to further reduce the requirements for running the pipeline. It will include buttons to start a new run, check the progress of previous runs, and re-run them if necessary.
