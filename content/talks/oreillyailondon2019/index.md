---
title: Anomaly Detection in Smart Buildings using Federated Learning
authors:
- admin
- Bargava Subramanian
event: O'reilly AI London 2019
event_url: https://conferences.oreilly.com/artificial-intelligence/ai-eu/public/schedule/detail/78152
location: 225 Edgware Road, Paddington, London W2 1JU, United Kingdom


summary: Building Intrusion Detection System for network traffic data.
abstract: "There is an exponential growth in the number of Internet-enabled devices on modern smart buildings. In this talk, the speakers show how they built anomaly detection models using federated learning for a) data quality and b) cyber security. Federated learning is privacy-preserving and doesn't require data to be moved to the cloud."


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-10-17T16:00:00Z"
date_end: "2019-10-01T16:40:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2018-11-01T00:00:00Z"


tags: [oreillyailondon2019]

# Is this a featured talk? (true/false)
featured: false



#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/tuhinsharma121
url_code: "https://github.com/tuhinsharma121/federated-ml"
url_slides: "talks/oreillyailondon2019.pdf"
url_video: ""

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

<h2>Description</h2>


A modern smart building has a number of internet-enabled devices. IoT sensors to measure temperature, internet-enabled lighting, IP camera, IP Phone, etc. Data is generated at scale across all the devices. There are two critical aspects of the network of devices to function well:

- Data Quality - The data that is generated has to be correct (typically within an accepted error range)
- Security - with a number of internet-connected devices, securing the network from cyber threats is very important.

But there are two broad challenges to achieve the above:

- The data collected are very sensitive to the business operations and hence the solution has to be privacy-preserving
- The amount of data generated is huge and is not feasible to upload all of them to the cloud.

The speakers used Federated learning to build anomaly detection models that monitor data quality and cyber security - while preserving data privacy.

Federated learning enables Edge devices to collaboratively learn a machine learning model but keeping all of the data on the device itself. Instead of moving data to the cloud, the models are trained on the device and only the updates of the model are shared across the network. Using federated learning gave us the following advantages:

- More accurate and Low latency models: The data are not moved. Only the model updates are shared. This results in models having low latency (since the models are on the device) and are also more accurate
- Privacy Preserving: The data remains on the device.
- Energy Efficient: The workload on the device is drastically reduced - leading to lesser power consumption and longer device life.

The speakers built deep learning models using pytorch and pysyft.

The speakers discuss their architecture and also show how federated learning can help improve the models. Federated learning provides a framework to port models across organizations for the same domain of the device. This is something that's not possible in traditional cloud-based anomaly detection models. This makes it easy to deploy with very limited data and the speakers share some of their success stories.

<h2>Presentation Video</h2>

{{< youtube 6S3R2pOyyxo >}}