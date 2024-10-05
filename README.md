# DeepLearningExam

# The meccano dataset: Action recognition from egocentric videos in an industrial-like domain

![alt text](https://github.com/francescogra/DeepLearningExam/blob/main/slide1.png)

The objective of this project is to test and analyse two advanced neural network models for the recognition of human actions through video analysis, using the MECCANO dataset. Wearable cameras allow images and videos to be captured from the user's perspective, offering a new dimension for understanding human behaviour in egocentric contexts, particularly in industrial environments.
Action recognition consists of determining the action performed by the camera wearer from an egocentric video segment. The objective is to assign the correct action class to the video segment, using RGB frames as input. This project compares the performance of two neural network models: the SlowFast model (SLOWFAST_8x8_R50_MECCANO) and the newer MViT model (MVITv2_S_16x4). The models were not developed from scratch, but were used to test and analyse the results, comparing their performance to assess the effectiveness of each approach in the context of action recognition.

Translated with DeepL.com (free version)

![alt text](https://github.com/francescogra/DeepLearningExam/blob/main/slide2.png)

The applications of this technology are diverse, ranging from security and surveillance to entertainment, human-machine interaction and robotics. In this context, the MECCANO dataset is the first egocentric video dataset to study human-object interaction in an industrial context. MECCANO was collected from 20 participants who were asked to build a motion model by interacting with small objects and tools. Two state-of-the-art neural network models were used to achieve the objectives:

SLOWFAST_8x8_R50_MECCANO: This neural network model is based on the PySlowFast architecture designed specifically for video analysis. The SlowFast approach involves two different paths: a slow one that captures high resolution spatial detail at a low frame rate, and a fast one that captures temporal dynamics at high speed but with reduced spatial resolution. This allows the model to balance spatial and temporal accuracy, improving action recognition.

MVITv2_S_16x4: The MViTv2 model represents a newer architecture based on multi-scale vision transformers. This model is designed to efficiently capture both spatial and temporal features, using attention mechanisms that can model relationships between different parts of the image and along the temporal dimension. Both models were trained and evaluated on the MECCANO dataset and as an action recognition task.

