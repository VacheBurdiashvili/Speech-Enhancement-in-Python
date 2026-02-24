# Speech Enhancement Using Classical DSP Techniques

## Overview

In real-life scenarios, speech signals are often corrupted by white, stationary or non-stationary noise. Thus, reducing the speech clarity and quality. In order to improve that I used 3 classical DSP techniques: Spectal Filtering (Spectral Subtraction), Wiener Filtering and Adaptive Filtering (LMS). *I decided not to go into the heavy maths of each of the techniques here, as they are explained in Jupyter notebook files*

## How I did it

I recorded my own voice recording and added a gaussian noise. Then I applied all of the methods to see which one is better and compared them with evaluation metrics.

## Evaluation Metrics

For evaluating I used Signalt to noise Ratio (SNR), Frequency spectrum comparison and listening tests.

## Conclusion/Results

Looking at SNR, all of the techniques showed a massive improvement, going from -22dB to more than 20dB. The best method was Adaptive Filtering as it improved by 50dBs going from -22dB to 33dB. Adaptive filtering also proves to be the best in real-life scenarios since it can handle non-stationary noise, unlike spectral and wiener filtering.
