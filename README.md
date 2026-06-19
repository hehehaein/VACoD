# VACoD
Training-free hallucination mitigation for LVLMs via entropy-guided visual attention masking.

Official implementation of VACoD:
Visual Attention Contrastive Decoding for Hallucination Mitigation in Large Vision-Language Models.

## Overview

Large Vision-Language Models (LVLMs) often generate hallucinated objects that are not grounded in the input image.

VACoD mitigates hallucinations without retraining by:

- Visual Attention Masking
- Contrastive Decoding
- Entropy-guided Dynamic Layer Selection

## Key Contributions

- Training-free hallucination mitigation
- Dynamic masking layer selection
- Applicable to multiple LVLM architectures

## Benchmarks

- CHAIR
- POPE
- MME-H
- MMBench
- MM-Vet

## Results

Improved hallucination metrics while preserving general visual understanding performance.

## Publication

ICML 2026
