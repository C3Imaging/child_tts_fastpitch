# child_tts_fastpitch
Fastpitch text-to-speech (TTS) model for generating high-quality synthetic child speech. This study uses the transfer learning training pipeline. The approach involved finetuning a multi-speaker TTS model to work with child speech. We use the publicly available MyST dataset (55 hours) for our finetuning experiments. 

### Abstract: 
Speech synthesis technology has witnessed significant advancements in recent years, enabling the creation of natural and expressive synthetic speech. One area of particular interest is the generation of synthetic child speech, which presents unique challenges due to the distinct vocal characteristics and developmental stages of children. This paper presents a novel approach that leverages the Fastpitch text-to-speech (TTS) model for generating high-quality synthetic child speech. This study uses the transfer learning training pipeline. The approach involved finetuning a multi-speaker TTS model to work with child speech. We use the publicly available MyST dataset (55 hours) for our finetuning experiments. We also release a small set of synthetic datasets generated from this research. By using a pretrained MOSNet, we conducted an objective assessment that showed a significant correlation between real and synthetic child voices. Additionally, we employed an automatic speech recognition (ASR) model to compare the word error rates (WER) of real and synthetic child voices.

### Codebase: 
We follow the Nvidia's implementation of Fastpitch available here: https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/SpeechSynthesis/FastPitch 
Additional training and usage details are provided in their Github. 

### Checkpoint to use the Fastpitch child TTS model: 
See the 'ckps' folder

### OneDrive link to Generated Datasets: 
https://nuigalwayie-my.sharepoint.com/:f:/g/personal/0125225s_universityofgalway_ie/EpWCo1kPOl9OhVC_4KXOfr4B1lv6KpQzgpgS7rI3d4FUog

