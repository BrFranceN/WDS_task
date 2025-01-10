# Visual Word Sense Disambiguation using CLIP, BLIP2, and ALBEF

This repository contains the implementation of experiments in Visual Word Sense Disambiguation (VWSD) using state-of-the-art models like CLIP, BLIP2, and ALBEF. VWSD aims to resolve the semantic ambiguity of words within a visual context, by matching polysemous words to the most relevant images.

## Introduction

VWSD addresses the challenge of understanding the semantic context of sentences and capturing meaningful relationships between text and images. This project uses CLIP for learning shared representation spaces, BLIP2 for bootstrapped language-image pretraining, and ALBEF which emphasizes alignment before fusion of visual and textual inputs

## Models Overview

- **CLIP**: Connects images and sentences through a contrastive learning approach
- **BLIP2**: Extends capabilities for understanding and connecting visual content with textual descriptions using large-scale pretraining
- **ALBEF**: Focuses on aligning visual and textual representations before their fusion for improved interpretation

## Experiments

Experiments were conducted on datasets in three languages: English, Italian, and Farsi, with two different preprocessing strategies:

1. **Preprocessing 1**: Augmentation of the target word/phrase with generic sentences to provide additional context
2. **Preprocessing 2**: Use of Wordnet synsets definitions to augment the target word/phrase.

## Presentation

For more detailed insights and visual results of the experiments, refer to the `wsd_presentation.pdf` file included in this repository
