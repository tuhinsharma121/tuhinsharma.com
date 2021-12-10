---
title: Writer Independent Offline Signature Verification in Banks using Few Shot Learning.
authors:
- admin
- pravin-jha
event: Strata Data and AI Conference
event_url: https://conferences.oreilly.com/strata-data-ai/stai-eu/public/schedule/detail/82680
location: Excel London, One Western Gateway, Royal Victoria Dock, London, E16 1XL, UK


summary: Offline signature verification is one of the most critical tasks in traditional banking and financial industries. The unique challenge is to detect subtle but crucial differences between genuine and forged signatures. This verification task is even more challenging in writer independent scenarios, which is undeniably fiscal to most of the use cases.
abstract: "Offline signature verification is one of the most critical tasks in traditional banking and financial industries. The unique challenge is to detect subtle but crucial differences between genuine and forged signatures. This verification task is even more challenging in writer independent scenarios, which is undeniably fiscal to most of the use cases."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-04-23T16:35:00Z"
date_end: "2020-04-23T17:15:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2018-11-01T00:00:00Z"


tags: [oreillylondon2020]

# Is this a featured talk? (true/false)
featured: false



#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/tuhinsharma121
#url_code: "https://github.com/tuhinsharma121/federated-ml"
#url_slides: "talks/dhsindia2019.pdf"
#url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: files/cv.pdf

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- internal-project

# Enable math on this page?
math: true
---

<h3>Description</h3>

Signature is arguably the most popular and widely accepted biometric hallmarks used in the Banking sector for verifying documents, bank checks, forms etc. That is why signature verification is such a critical task and a simple bug in the system can cause severe repercussions. There are two popular ways to do it – Online and Offline. In online process, signature needs to be captured on electronic writing pad and several other types of information like writing speed, pressure etc. are captured. In offline process signature is captured by scanner. While online process performs better than offline process, it comes with a cost due to special hardware requirements. Additionally there are many cases where offline process is the only option such as check transaction and document verification. Offline signature verification can be of two types -  writer dependent and writer independent. a writer dependent system needs to be updated with every new signer and for a bank, where every day new consumers can open their account this incurs huge cost. That is why the writer independent scenario is preferable over writer dependent approaches where a generic model is built to classify the signatures as genuine or forged based on the learnt discrepancies between a genuine and a forged signature. 
In case of standard image classification task, the input image is fed into a series of layers, and finally at the output we generate a probability distribution over all the classes. But it requires a large number of images. In offline signature verification scenario, we neither have enough signature for each signer and the total number signers is huge as well as dynamically changing. Thus, the cost of data collection and periodical retraining is too high. On the other hand, in a few shot image classification, we require only a few signatures for each signer, hence the name Few Shot.

The speakers will discuss the following:-
    
1. Introduction to Few Shot Learning
2. The architecture of Siamese Network
3. How to train Offline signature verification system using Siamese Networks on real life data.
4. Tools to build such model.
5. How to deploy such model on cloud.
6. How to serve such model in real time.
7. Pros and Cons of our approach.

<p>Presentation Video </p>



TBA!!