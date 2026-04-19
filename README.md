# HTGM v2 Hindi LLM – Session 12 | 106 Hours Training Progress

## Overview

Session 12 of HTGM v2 Hindi LLM training is now completed.

This session focused on stable continuation from checkpoint, maintaining validation performance, and improving training consistency after previous learning rate and warmup fixes.

Even with only 6 hours of Kaggle GPU time remaining, the model continued learning effectively.

This repository documents the real progress of building a Hindi LLM from scratch using a GPT-style architecture.

---

## Session Information

- Session Number: 12
- Session Duration: 6 Hours
- Total Training Time: 106+ Hours
- Total Sessions Completed: 12

---

## Technical Details

- Model Name: HTGM v2
- Type: Hindi Large Language Model (Hindi LLM)
- Architecture: GPT-style Transformer
- Model Size: 163.4M Parameters
- Sequence Length: 2048
- Vocabulary Size: 100,000
- Dataset Size: ~41GB
- Dataset Source: AI4Bharat Sangrah + Manual Cleaning
- Training Platform: Kaggle
- GPU: 2x T4
- Tokenizer: Hugging Face BPE-based Tokenizer

---

## Training Progress

- Total Planned Optimizer Steps: 923,382
- Resumed From Checkpoint Step: 850,735
- Current Training Step: 27,376+
- Final Checkpoint Saved: ckpt_final_s876051.pt

---

## Dataset Used

### Loaded Chunks

- chunk_1.txt
- chunk_2.txt
- chunk_3.txt

---

## Training Metrics

### Loss & Validation

- Training Loss Observed: 2.7152
- Later Observed Loss: 4.4995
- Final Validation Loss: 4.9467
- Final Perplexity (PPL): 140.70

---

## Checkpoint Strategy

Training was resumed from a previous checkpoint instead of restarting from scratch.

### Benefits

- Safe long training workflow
- Hyperparameter testing without losing progress
- Stable continuation after interruptions
- Reliable optimizer and scheduler recovery

---

## Observations

### What Improved

- Stable learning rate behavior
- Validation remained controlled
- No major crashes
- Smooth checkpoint saving
- Strong GPU utilization
- W&B monitoring active

### Why It Matters

Even short sessions can create meaningful progress when optimization is stable.

This session proved that better training quality matters more than longer unstable runs.

---

## Current Status

- Training is stable
- Validation is improving
- Perplexity is controlled
- Model outputs are improving gradually

Still not production-ready, but strong foundation is built.

---

## Next Steps

- Apply Supervised Fine-Tuning (SFT)
- Improve instruction-following capability
- Better dataset structuring
- Continue long training sessions
- Improve response quality and coherence

---

## Author

Mahesh Editor  
India AI Official

---

## Build in Public

This project is shared publicly to document real AI development, not just final results.

Every training log, problem, improvement, and experiment is part of the journey.
