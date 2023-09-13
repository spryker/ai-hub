---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title:  "Welcome to Spryker AI Hub!"
date:   2023-09-13 15:55:45 +0200
categories: ai welcome spryker
---

![Spryker AI Hub](/assets/spryker-ai-hub-hero1.jpg)

## Empower Your E-Commerce Journey with Intelligence

Greetings to our valued partners, customers, and innovators!
We're thrilled to introduce the Spryker AI Hub,
the central nexus where state-of-the-art artificial intelligence and
machine learning blend seamlessly with the world of e-commerce.

Built on the bedrock of collaboration,
the AI Hub is designed to serve as the focal point for an enriched and
intelligent e-commerce experience.

## Why Spryker AI Hub?

✨ Collaborative Innovation: At its heart, the AI Hub is about co-creation. We invite you to join hands with us, to contribute, refine, and utilize AI-driven solutions tailored for Spryker products. By bridging the gap between AI specialists and e-commerce experts, we're forging a community that's bigger than the sum of its parts.

✨ Customizable Solutions: Understand the unique demands of your e-commerce venture? Translate them into smart, efficient, and automated solutions. Whether it's B2B, B2C, or Marketplace, sprinkle a touch of AI magic to elevate user experiences. Use publicly available datasets to train your own AI models and integrate them with Spryker products.

✨ Stay Ahead: In today's dynamic digital landscape, staying updated is not just an advantage—it's a necessity. The AI Hub ensures you always have access to the latest tools, techniques, and insights to keep your e-commerce endeavors at the forefront.

## Get Started
Spryker AI Labs has prepared for you some initial datasets that can be used for training (ML)
of your AI models.

- Public documentation training raw md

| What            | Value                                                                   |
|-----------------|-------------------------------------------------------------------------|
| Scope           | all known public documentation .md files + 2 open api schema .json      |
| Cleannes        | raw                                                                     |
| Structure       | multi-level directory                                                   |
| Document count  | 11.182                                                                  |
| Token approx    | 9 million                                                               |
| Document format | md, json                                                                |
| Link            | https://drive.google.com/file/d/19gaIIq99rsUNlHdE5ZYL_lPyQitLv3BT/view  |

- Public documentation cleaned trained full (chroma)

| What              | Value                                                                  |
|-------------------|------------------------------------------------------------------------|
| Scope             | all known public documentation .md files + 2 open api schema .json     |
| Vectorization     | OpenAI.text-embedding-ada-002                                          |
| Structure         | multi-level directory                                                  |
| Tokenizer         | tiktoken.cl100k_base                                                   |
| TextSplit         | md: separater(^##?#?), chunk_size(2000), chunk_overlap(200)            | 
| TextSplit         | json: separater(\n), chunk_size(2000), chunk_overlap(200)              |
| Chroma collection | langchain                                                              |
| Link              | https://drive.google.com/file/d/1YXARbS6AME0jXfKEGf3SQb0m_V2uLb3k/view |

## Get Involved

1. <b>Get recognized</b>: Have a groundbreaking AI or ML tool? Show your expertise and share it with the community.
   Send us an email to ai-hub@spryker.com describing your tool and a link to repository on how to find it and we will recognize it on the Spryker AI Hub.
2. <b>Get Support</b>: Missing Spryker API or a data set? Let us know, so we transfer your request to our product team! Open an Issue with your request to spryker/ai-hub on GitHub.
