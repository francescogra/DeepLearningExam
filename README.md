# DeepLearningExam

# The meccano dataset: Action recognition from egocentric videos in an industrial-like domain

The aim of this project is to test and analyse two advanced neural network models for human action recognition through video analysis using the MECCANO dataset. This dataset, rich in detailed annotations of the actions performed in different scenes, provides a robust starting point for the training of artificial intelligence models specialised in the recognition of human activities. 
After testing the models, the results were analysed and compared to assess the performance and effectiveness of each model. Human action recognition is one of the most fascinating and complex challenges in computer vision and machine learning. 

The applications of this technology are diverse, ranging from security and surveillance to entertainment, human-machine interaction and robotics. In this context, the MECCANO dataset is the first egocentric video dataset to study human-object interaction in an industrial context. MECCANO was collected from 20 participants who were asked to build a motion model by interacting with small objects and tools. Two state-of-the-art neural network models were used to achieve the objectives:

SLOWFAST_8x8_R50_MECCANO: This neural network model is based on the PySlowFast architecture designed specifically for video analysis. The SlowFast approach involves two different paths: a slow one that captures high resolution spatial detail at a low frame rate, and a fast one that captures temporal dynamics at high speed but with reduced spatial resolution. This allows the model to balance spatial and temporal accuracy, improving action recognition.

MVITv2_S_16x4: The MViTv2 model represents a newer architecture based on multi-scale vision transformers. This model is designed to efficiently capture both spatial and temporal features, using attention mechanisms that can model relationships between different parts of the image and along the temporal dimension. Both models were trained and evaluated on the MECCANO dataset and as an action recognition task.

