# Anomaly-Detection-using-Masked-Autoencoder
 In this work, Masked autoencoder (MAE) based on autoencoder architecture along with One-class SVM is employed for the classification and detection of anomalies. UCSD anomaly detection dataset is used to evaluate the performance metrics.
Introduction
Masked autoencoder[7]is a recently introduced technique in computer vision that presents a simple,
effective, and scalable form of a masked autoencoder (MAE)for visual learning. Masked autoencoder (MAE) follows an autoencoding scheme that reconstructs the original data given
its partially masked input data. It has an encoder that maps the observed data to a latent space, and a decoder that reconstructs the original data from the latent space. Differing from classical
autoencoders, it adopts an asymmetric design that allows the encoder to operate only on the partial, observed data that has no mask tokens and decoder that reconstructs the full
data from the latent space and mask tokens. In this project,anomaly detection using masked autoencoder for feature extraction and One-class SVM is used for the classification of anomalies based on learned features presented. A well-known benchmark dataset is used to evaluate the performance
of the model (UCSD Anomaly Detection Dataset).
