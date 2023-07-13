---
title: Assessing generalization of cognitive tasks using multi-regional modular recurrent neural networks with transfer learning

summary: An example of using the in-built project page.
tags:
  - Transfer learning, cognitive tasks
date: '2022-01-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# Introduction
The study of cognitive tasks plays a crucial role in understanding human mental processes. Recently, recurrent neural networks have been widely applied in the computational modelling of cognition, offering a controllable approach to investigating cognitive processes and the relationship between cognitive tasks. However, current research primarily focuses on specific tasks, ignoring the fact that real brains have knowledge of multiple tasks simultaneously in different brain regions.

# Methods
In this study, we proposed a multi-regional modular recurrent neural network to simulate the cognitive processes. The model is structured into three different modules: perception, information integration, and decision. Here a transfer learning approach is adopted to investigate generalizability across tasks. After training models on source tasks, we fixed the information integration layers, transferred the models to target tasks, and tested their performance. By comparing the performance of different source-target task pairs, we assessed the similarity between different cognitive tasks.

# Results
We visualized the activation of models and found different firing patterns corresponding to specific trigger conditions and modalities.

Additionally, the results demonstrated better transferability between cognitive tasks in the same category. Clustering and similarities for cognitive tasks are also indicated in recurrent neural networks that resemble human subjects' performances.


# Conclusion
These findings shed light on the coordination and functioning of functional modules in different brain regions and present transfer learning as a new way for investigating generalization across diverse cognitive tasks.


