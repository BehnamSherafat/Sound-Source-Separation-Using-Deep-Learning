# Sound-Source-Separation-Using-Deep-Learning
Please cite this paper if you used the codes or dataset:
Sherafat, B., Rashidi, A. and Song, S., 2020, November. A Software-Based Approach for Acoustical Modeling of Construction Job Sites with Multiple Operational Machines. In Construction Research Congress 2020: Computer Applications (pp. 886-895). Reston, VA: American Society of Civil Engineers.
## Keywords
1. Deep learning
2. Deep Nueral Networks (DNNs)
3. Binary Time-Frequency Masks
4. Off-the-shelf microphone
5. Blind Source Separation (BSS)
6. Soft Masks and Hard masks
7. Short Time Fourier Transform (STFT)
8. Adaptive Moment Estimation (ADAM)
10. Sigmoid activation function
11. Source to Distortion Ratio (SDR)
12. Source to Interferences Ratio (SIR)
13. Source to Artifacts Ratio (SAR)
14. Independent Component Analysis (ICA)

## Introduction
I proposed a software-oriented approach using Deep Neural Networks (DNNs) and Time-Frequency Masks (TFMs) to address sound source separation issues with microphone arrays. The proposed method requires using single microphone, as the sound sources could be differentiated by training a DNN. The presented approach has been tested and validated under simulated job site conditions where two machines operated simultaneously. Results show that the average accuracy for soft TFM is 38% higher than binary TFM.

## Programming Language Used
MATLAB

## Guide to folders and files
There are 10 folders available in this repo, that provides the required codes for each type of heavy construction equipment (each equipment has different movements and actions; hence different labels/targets.
Each folder consists of several files, which are explained as follows:
1. **Main file** (Fusion_Training.m): This is the main file to execute.
2. **Denoising algorithms and functions** (algorithm developed by Rangachari, S.; Loizou, P.C. A noise-estimation algorithm for highly non-stationary environments. Speech Commun. 2006, 48, 220–231):
  initialise_parameters.m
  mcra2_estimation.m
  noise_estimation.m
  specsub_ns.m
3. **Inputs:**
  **Kinematic Data** (Accelerometer and gyroscope):
    test2.mat
  **Sound Data**
    Two .WAV files (equipment sound collected on the job site using a microphone)
      _ori: means original sound
      _den: means denoised sound

## Methodology
![image](https://user-images.githubusercontent.com/73087167/185805547-b7f6c797-d257-45bb-b596-1bb6b028aeeb.png)

## Sample data (sound signals)
![image](https://user-images.githubusercontent.com/73087167/185805572-b3380470-7e43-4042-ba23-401d36bf1ee3.png)

## Principal Component Analysis
![image](https://user-images.githubusercontent.com/73087167/185805597-fcba0bc7-1430-4463-93ef-aa6ee023006b.png)

## Confusion Matrix
![image](https://user-images.githubusercontent.com/73087167/185805610-a832b48c-e0e0-420c-a9ab-31eb1696c2dd.png)

