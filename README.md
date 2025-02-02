# Autism---Speech-Classification
Autism Spectrum Disorder (ASD) often includes challenges in verbal communication, particularly for minimally verbal (mv*) individuals. Mv* individuals with ASD often find it difficult to communicate with people since their vocalizations are highly personalized and often non-verbal, making it extremely difficult for people to understand their needs. Recent advances in machine learning and deep learning have made it possible for researchers to explore new avenues and provide personalized care for individuals with ASD. This research explores transfer learning and Mel spectrograms to classify non-verbal vocalizations from mv* ASD individuals, aiming to improve understanding and communication. We conduct three experiments to verify the robustness and generalizability of our approach in different setups. Using a dataset of 7077 vocalizations from eight mv* individuals collected from noisy, real-world settings, we convert the audio signals to Mel spectrograms and evaluate six transfer learning models and a custom convolutional neural network model. Our experiments demonstrated that DenseNet161, ResNet101, and VGG19, particularly when combined in an ensemble, effectively classify vocalizations into six categories: self-talk, frustration, delight, dysregulation, social, and request. Results suggest that this ensemble achieves state-of-the-art performance with an F1 score of 0.79, outperforming traditional machine learning methods and highlighting the potential of artificial intelligence in enhancing care for mv* ASD individuals. We believe that our work could provide a good starting point to building mobile devices and applications that help people understand non-verbal vocalizations from ASD individuals quickly and accurately.



# File Organization: -

1. p01-autism.ipynb, p02-autism.ipynb, p03-autism.ipynb, p05-autism.ipynb, p06-autism.ipynb, p08-autism.ipynb, p11-autism.ipynb, p16-autism.ipynb: Builds dataset for each individual from the entire dataset and runs the ensemble model for each individual. 
2. alexnet-mobilevnet.ipynb, autism-mobilevnet.ipynb, Vision Transformers.ipynb, densenet-autism.ipynb, resnet-autism.ipynb, vgg-autism.ipynb: Tranfer learning models for comparative analysis. 
3. ensemble-autism.ipynb: Builds an ensemble of DenseNet161, ResNet101, and VGG19 and classifies audio without being individual specific.  
4. Autism Scores - Confusion Matrix.ipynb: Builds bar graphs and confusion matrices for all the models.
   



# Dataset Information: -

https://www.spectrumnews.org/news/researchers-publish-new-dataset-on-minimally-verbal-autistic-people/
https://zenodo.org/record/5786860#.ZG0w_HZBw2w
Installing files from Zenodo: -
pip install zenodo-get
zenodo_get 10.5281/zenodo.5786860
