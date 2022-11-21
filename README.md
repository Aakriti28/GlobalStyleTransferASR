# Global Rhythm Style Transfer Without Text Transcriptions

Here is a [Link to the Presentation](./Project_Report.pdf)

## Problem statement
  - Prosody plays an important role in characterizing the style of a speaker or an emotion, but most non-parallel voice or emotion style transfer algorithms   do not convert any prosody information.
  - Two major components of prosody are pitch and rhythm.
  - AutoPST disentangle global prosody style from speech without relying on any text transcriptions.
 
## Our Implementation
We have implemented a Prosody style transfer system for speech using autoencoders with a novel resampling module. We trained models with MFCCs as input and demonstrated performance in different fast, slow and abnormal settings. Taking inspiration from the paper on Rhythm Style Transfer (https://arxiv.org/pdf/2106.08519.pdf), we have experimented for the following cases:-
1. Fast speaker to slow speaker
2. Slow speaker to fast speaker
3. Abnormal speech pattern
