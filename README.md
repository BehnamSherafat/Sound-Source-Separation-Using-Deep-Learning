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
Codes are explained as follows:
1. **Main file** (SSS_DeepLearning.m): This is the main file to execute.
2. **Inputs:**
  **Sound Data**
    Two .WAV files (equipment sound collected on the job site using a microphone)
      _ori: means original sound
      _den: means denoised sound

## Methodology
![image](https://user-images.githubusercontent.com/73087167/185807793-cc696857-14ce-40c0-8682-3ca6ca62cc0f.png)


## Results (Hard TFM)
![image](https://user-images.githubusercontent.com/73087167/185807809-dd383387-a636-4b70-8f94-c43b92f91833.png)

## Results (Soft TFM)
![image](https://user-images.githubusercontent.com/73087167/185807818-a4dbf015-ef4f-48c3-bbcc-eb753f3cb6f2.png)

## Source Separation Evaluation
![image](https://user-images.githubusercontent.com/73087167/185807835-7300e7c0-87ae-4d67-a15b-0183756c45e9.png)
