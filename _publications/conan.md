---
title: "Conan: A Chunkwise Online Network for Zero-Shot Adaptive Voice Conversion"
collection: publications
permalink: /publication/conan
date: 2025-12-08
venue: 'ASRU'
paperurl: 'https://ieeexplore.ieee.org/document/11434701'
status: 'publication'
excerpt: Zero-shot online voice conversion (VC) holds significant promise for real-time communications and entertainment. However, current VC models struggle to preserve semantic fidelity under real-time constraints, deliver natural-sounding conversions, and adapt effectively to unseen speaker characteristics. To address these challenges, we introduce Conan, a chunkwise online zero-shot voice conversion model that preserves the content of the source while matching the voice timbre and styles of reference speech. Conan comprises three core components: 1) a Stream Content Extractor that leverages Emformer for low-latency streaming content encoding; 2) an Adaptive Style Encoder that extracts fine-grained stylistic features from reference speech for enhanced style adaptation; 3) a Causal Shuffle Vocoder that implements a fully causal HiFiGAN using a pixel-shuffle mechanism. Experimental evaluations demonstrate that Conan outperforms baseline models in subjective and objective metrics. Audio samples can be found on the [demo page](https://aaronz345.github.io/ConanDemo).
citation: 'Zhang, Y., Tian, B., & Duan, Z. (2025). Conan: A Chunkwise Online Network for Zero-Shot Adaptive Voice Conversion. Proc. IEEE ASRU. 2025.'
authors: Yu Zhang, **Baotong Tian**, Zhiyao Duan
---
