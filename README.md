# MMOE: Enhancing Multimodal Models with Mixtures of Multimodal Interaction Experts

## Abstract
Advances in multimodal models have greatly improved how interactions relevant to various tasks are modeled. Today's models mainly focus on the correspondence between images and text, using this for tasks like image captioning and image-text retrieval. However, this covers only a subset of real-world interactions. Novel interactions, such as sarcasm expressed through opposing spoken words and gestures or figurative descriptions of images, remain challenging. In this paper, we introduce an approach to enhance multimodal models, which we call Multimodal Mixtures of Experts (MMoE). The key idea in MMoE is to train separate expert models for each type of interaction, such as redundancy present in both modalities, uniqueness in one modality, or varying degrees of synergy that emerge when both modalities are fused. On two multimodal sarcasm datasets, we obtain new state-of-the-art results. MMoE also provides the opportunity to design smaller specialized experts, and improves the transparency of the modeling process.

### Repository Set-Up

We support 4 different models for the MMoE setup: ALBEF, BLIP2, Mistral, and QWEN2. Each of the scripts required to train/test each model can be found under each directory at {model_name}_dataset_{train/test}.sh. THe dataset splits can be found at the {dataset}_data directories. We support the Mustard and Sarcasm datasets at the moment. Feel free to modify our bash scripts or dataset code as you feel to support your own methods!
