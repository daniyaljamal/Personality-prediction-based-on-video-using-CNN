# Personality-prediction-based-on-video-using-CNN
This is repository for development of personality prediction using video processing.

Abstract—Personality computing and affective computing,
where the recognition of personality traits is essential, have
gained increasing interest and attention in many research areas
recently. We propose a novel approach to recognize the Big Five
personality traits of people from videos. Personality and emotion
affect the speaking style, facial expressions, body movements,
and linguistic factors in social contexts, and they are affected
by environmental elements. We develop a multimodal system
to recognize apparent personality based on various modalities
such as the face, environment, audio, and transcription features.
We use modality-specific neural networks that learn to recognize
the traits independently and we obtain a final prediction of
apparent personality with a feature-level fusion of these networks.
We employ pre-trained deep convolutional neural networks such
as ResNet and VGGish networks to extract high-level features
and Long Short-Term Memory networks to integrate temporal
information. We train the large model consisting of modalityspecific
subnetworks using a two-stage training process. We first
train the subnetworks separately and then fine-tune the overall
model using these trained networks. We evaluate the proposed
method using ChaLearn First Impressions V2 challenge dataset.
Our approach obtains the best overall “mean accuracy” score,
averaged over five personality traits, compared to the state-ofthe-
art.


The proposed model predicts the traits based on various
modalities including facial, ambient, audio, and transcription features. We make use of convolutional neural networks
(CNNs) in combination with Long Short-Term Memory
(LSTM) networks in a two-stage training phase. The proposed
approach obtains state-of-the-art results using ChaLearn First
Impressions V2 (CVPR’17) challenge dataset.

All the models will be published in "CNN Models" folder and dataset preperation codes will be in "data preprocessing" folder.

Regards 
Daniyal Jamal