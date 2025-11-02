# TASR: Enhancing Training-Free Few-Shot CLIP

This repository contains the implementation of our course assignment project **“TASR: Enhancing Training-Free Few-Shot CLIP via Text–Image Mutual Guidance and Soft Feature Selection.”**

---

## Overview

We combine two complementary ideas:

* **TIMO** – Text–Image Mutual Optimization, aligning text and image features through bidirectional guidance.
* **APE** – Adaptive Prior Refinement, identifying key feature dimensions that contribute most to classification.

Our hybrid approach introduces a **soft feature selection** module to re-weight CLIP feature dimensions, improving discriminability in few-shot scenarios while keeping the method fully *training-free*.

---
This repo is build upon previous repos include [TIP-Adapter](https://github.com/gaopengcuhk/Tip-Adapter/), [CLIP](https://github.com/openai/CLIP), [CoOp](https://github.com/KaiyangZhou/CoOp/), [SuS-X](https://github.com/vishaal27/SuS-X), [CuPL](https://github.com/sarahpratt/CuPL) [APE](https://github.com/yangyangyang127/APE), [GDA-CLIP](https://github.com/mrflogs/ICLR24) and [TIMO](https://github.com/lyymuwu/TIMO). Thanks for their contributions.