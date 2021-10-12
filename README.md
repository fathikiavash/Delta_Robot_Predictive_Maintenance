# Delta_Robot_Predictive_Maintenance
An autoencoder Anomaly-based approach for predictive maintenance of a 3 DoF Delta Robot

The provided code snippet is the implemented autoencoder for performing predictive maintenance by detecting anomaly in the system. In what follows an overview of the proposed method can be found:
______________________________________________________________________________

Performing predictive maintenance (PdM) is challenging for many reasons. Dealing with large datasets which may not contain run-to-failure data (R2F) complicates PdM even more. When no R2F data are available, identifying condition indicators (CIs), estimating the health index (HI), and thereafter, calculating a degradation model for predicting the remaining useful lifetime (RUL) are merely impossible using supervised learning. In this paper, a 3 dof delta robot used for pick and place task is studied. In the proposed method, autoencoders (AEs) are used to predict when maintenance is required based on the signal sequence distribution and anomaly detection, which is vital when no R2F data is available. Due to the sequential nature of the data, non-linearity of the system, and correlations between parameter time series, convolutional layers are used for feature extraction. Thereafter, a sigmoid function is used to predict the probability of having an anomaly given CIs acquired from AEs. This function can be manually tuned given the sensitivity of the system or optimized by solving a minimax problem. Moreover, the proposed architecture can be used for fault localization for the specified system. Additionally, the proposed method is capable of calculating RUL using Gaussian process (GP), as a degradation model, given HI values as its input.
______________________________________________________________________________
*The the preprint version of the paper can be found at:*
https://www.preprints.org/manuscript/202109.0099/v1

_If there are any questions regarding the paper, idea or implementation do not hesitate to contact me (kiavash.fathi@zhaw.ch, fathikiavash@gmail.com)_

_Thank you in advance for your comments and suggestions :)_
