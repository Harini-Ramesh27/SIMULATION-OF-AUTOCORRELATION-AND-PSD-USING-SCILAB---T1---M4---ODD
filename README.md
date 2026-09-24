# SIMULATION-OF-AUTOCORRELATION-AND-PSD-USING-SCILAB

## AIM

Write a program for Autocorrelation and PSD of signals in SCILAB and verify Wiener-Khinchin relation.

## EQUIPMENTS NEEDED

- Computer with i3 Processor
- SCI LAB

## THEORY

The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the Fourier transform of the corresponding autocorrelation function.

### Power Spectral Density (PSD)

$$
S_{XX}(\omega)=FT[R_{XX}(\tau)]
=\int_{-\infty}^{\infty}R_{XX}(\tau)e^{-j\omega\tau}d\tau
$$

### Autocorrelation Function (ACF)

$$
R_{XX}(\tau)=IFT[S_{XX}(\omega)]
=\frac{1}{2\pi}\int_{-\infty}^{\infty}S_{XX}(\omega)e^{j\omega\tau}d\omega
$$

## ALGORITHM

### 1. Load or Define the Signal:

Input your time-domain signal.

### 2. Compute Autocorrelation:

Calculate the autocorrelation function of the signal.

### 3. Compute Power Spectral Density (PSD):

Estimate the PSD of the signal, either directly using a method like Welch’s periodogram or by using the Fourier transform of the autocorrelation.

### 4. Plot Results:

Visualize the autocorrelation function and PSD.

## PROCEDURE

- Refer Algorithms and write code for the experiment.
- Open SCILAB in System.
- Type your code in New Editor.
- Save the file.
- Execute the code.
- If any Error, correct it in code and execute again.
- Verify the generated waveform using Tabulation and Model Waveform.

## Output
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/d8091d04-f4e7-4feb-a988-ca8673e953eb" />
MARK SPLIT-UP:
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/7ce48222-892f-4179-bd76-a0bbe85ed70a" />



## Result
<img width="1600" height="304" alt="image" src="https://github.com/user-attachments/assets/7b66da7e-fbae-44a2-8e31-a1322de3654f" />

