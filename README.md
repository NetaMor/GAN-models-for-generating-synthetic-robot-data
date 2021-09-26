# GAN-models-for-generating-synthetic-robot-data
Implementation and analyzing four GAN models for generating synthetic robot data:
1. Fully connected GAN
2. Convulation+fully connected GAN
3. Residual GAN
4. "GMM" GAN


Metrics for comparing the models:
1. Comparison of the distribution of the generated data to the real data.
2. NearestNeighbors score for generated data (NearestNeighbors Model trained on real data)
3. Loss of prediction model (I didn't upload this code) that trained on generated data and predicted on real data
