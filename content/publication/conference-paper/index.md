---
title: 'Multi-Robot Reliable Navigation in Uncertain Topological Environments with Graph Attention Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hongliang Guo

date: '2024-11-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Journal Paper']

# Publication name and optional abbreviated publication name.
# publication: 
# publication_short: In *ICW*

abstract: This paper studies the multi-robot reliable navigation problem in uncertain topological networks, which aims at maximizing the robot team's on-time arrival probabilities in the face of road network uncertainties. The uncertainty in these networks stems from the unknown edge traversability, which is only revealed to the robot upon its arrival at the edge's starting node. Existing approaches often struggle to adapt to real-time network topology changes, making them unsuitable for varying topological environments. To address the challenge, we reformulate the problem into a Partially Observable Markov Decision Process (POMDP) framework and introduce the Dynamic Adaptive Graph Embedding method to capture the evolving nature of the navigation task. We further enhance each robot's policy learning process by integrating deep reinforcement learning with Graph Attention Networks (GATs), leveraging self-attention to focus on critical graph features. The proposed approach, namely Multi-Agent Routing in Variable Environments with Learning (MARVEL) employs the generalized policy gradient algorithm to optimize the robots' real-time decision-making process iteratively. We compare the performance of MARVEL with state-of-the-art reliable navigation algorithms as well as Canadian traveller problem solutions in a range of canonical transportation networks, demonstrating improved adaptability and performance in uncertain topological networks. Additionally, real-world experiments with two robots navigating within a self-constructed indoor environment with uncertain topological structures demonstrate MARVEL's practicality.

# Summary. An optional shortened abstract.
summary: Under Review.

tags:
  - Multi-Agent System
  - Deep Reinforcement Learning
  - Graph Neural Networks

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://arxiv.org/abs/2411.16134'
url_code: 'https://github.com/YUJ0E/MARVEL'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
