# UIUC CS498 Spring 2020: Audio Labaratory Assignments

### Introduction

- This course covers the basic ideas of audio processing and wide range of techniques to create sound effects.

- Courses and assignments are designed by Professor Paris Smaragdis.

### Contents

- **W1**: Basic Sound Manipulation
    
    - Generate tones and basic sounds such as chirp, ping-pong, etc.
    - In/output sounds from/to storage or sound devices

- **W2**: Time and Frequency Domain

    - Conduct Short Time Fourier Transform and generate spectrograms
    - Blocking some noises in Frequency Domain and transform back to sound data in time domain.

- **W3**: Fix Sounds with Filters

    - Design Lowpass, Highpass, Bandpass, Bandstop filters with different techniques and apply on different type of noises.

- **W4**: Reverberation and Room Simulation

    - Generate reverb effects by designing Comb filters, Allpass filters, etc.
    - Create the room's response via deconvolution and apply to the sounds.

- **W5**: 3D Audio & Virtual Sound

    - Simulate the sound sources by convoluting the original sound with ITD and ILD filters
    - Simulate the dynamic sources by covoluting the sound with different HRTFs at each moment

- **W6**: Microphone Arrays

    - Generate steering vector for different inputs' phase shifts and identify the directions of sound sources.
    - Enable the microphone array to act like beamforming microphone and tramsform the original input to localized sound.

- **W7**: Denoising

    - Sample the background noise from recording and denoise with spectral subtraction and median filtering
    - Dynamically sample the noise by using voice activity detector to get better result in every moment

- **W8**: Pitch Tracking and modifications

    - Track the voice pitch by using autocorrelation and ignore un-pitched frames
    - Track the voice pitch by detecting zero-crossing and tune the sound with pitch synchronous overlap adding (PSOLA)

- **W9**: Spectral Factorizations

    - Learn the spectral factors in sound track and extract sounds emitted by each instrument
    - Train the factors of human speaking and chimes and separate the mixture of the two



