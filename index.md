---
layout: default
title: Home
---

![ASB Diagram](/assets/image/Abstract.png)

## Abstract

Unlike bitmap images, scalable vector graphics (SVG) maintain quality when scaled, frequently employed in computer vision and artistic design in the representation of SVG code. In this era of proliferating AI-powered systems, enabling AI to understand and generate SVG has become increasingly urgent. However, AI-driven SVG understanding and generation (U\&G) remain significant challenges. SVG code, equivalent to a set of curves and lines controlled by floating-point parameters, demands high precision in SVG U\&G. Besides, SVG generation operates under diverse conditional constraints, including textual prompts and visual references, which requires powerful multi-modal processing for condition-to-SVG transformation. Recently, the rapid growth Multi-modal Large Language Models (MLLMs) have demonstrated capabilities to process multi-modal inputs and generate complex vector controlling parameters, suggesting the potential to address SVG U\&G tasks within a unified model. To unlock MLLM’s capabilities in the SVG area,  we propose an SVG-centric dataset called UniSVG, comprising 525k data items, tailored for MLLM training and evaluation. To our best knowledge, it is the first comprehensive dataset designed for unified SVG generation (from textual prompts and images) and SVG understanding (color, category, usage, etc.). As expected, after learning on the proposed dataset, open-source MLLMs can be enhanced comprehensively to handle various SVG U\&G tasks, and outperforms SOTA close source MLLMs like GPT-4V. We will release dataset, benchmark, weights, and codes on \href{https://ryanlijinke.github.io/}{https://ryanlijinke.github.io/}.