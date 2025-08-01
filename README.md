# Raw Data Matters: Enhancing Prompt Tuning by Internal Augmentation on Vision-Language Models
> Haoyang Li<sup>1,2</sup>, Liang Wang<sup>1,2</sup>, Chao Wang<sup>2</sup>, Siyu Zhou<sup>1</sup>, Jing Jiang<sup>1</sup>, Yan Peng<sup>2</sup> and Guodong Long<sup>1</sup> <br>
> <sup>1</sup>_Australian Artificial Intelligence Institute, University of Technology Sydney_ <br>
> <sup>2</sup>_School of Mechanical Engineering and Automation, Shanghai University_ <br>

### Abstract

For CLIP-based prompt tuning, introducing more data as additional knowledge for enhancing fine-tuning process is proved to be an effective approach. Existing data amplification strategies for prompt tuning typically rely on external knowledge (e.g., large language models or pre-structured knowledge bases), resulting in higher costs for data collection and processing, while generally ignoring further utilization of features in image modality. To address this, we propose **Aug**mentation-driven **P**rompt **T**uning (**AugPT**), a self-contained distillation-based prompt tuning approach using only internal augmentation on raw dataset to better exploit known features. Specifically, AugPT employs self-supervised augmentation on unlabeled images in the training set, and introduces a novel gating mechanism based on consensus test, reusing the pre-trained prompt tuning backbone model to spontaneously filter noisy samples, further enhancing the quality of augmented views. Extensive experiments validate that AugPT simultaneously enhances model performance and generalization capability without using appended external knowledge.

### Our Previous Work in 2025
- **[CVPR 2025]** [DPC: Dual-Prompt Collaboration for Tuning Vision-Language Models](https://arxiv.org/abs/2503.13443)
- **[ICME 2025]** [MAO: Efficient Model-Agnostic Optimization of Prompt Tuning for Vision-Language Models](https://arxiv.org/abs/2503.18160)

### Code Statement
We promise to release our code implementation in the future.
