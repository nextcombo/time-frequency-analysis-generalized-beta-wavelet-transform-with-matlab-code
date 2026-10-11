# Time-Frequency Analysis: Generalized Beta Wavelet Transform [with MATLAB Code]

1. Summary
Utilizing Continuous Wavelet Transform (CWT) for time-frequency analysis of signals can provide important information for the delineation of underground reservoirs. However, CWT is limited by the Heisenberg Uncertainty Principle, balancing between time and frequency localization. At the same time, mother and daughter waves should adapt to the actual seismic wave waveforms. Therefore, for reflection seismic signals, we propose a progressive wavelet family called Generalized Beta Wavelet (GBW). By changing two parameters controlling the shape of the wavelet, the time-frequency representation of GBW can be given sufficient flexibility while maintaining precise analytical properties. To achieve an adaptive trade-off between time-frequency localization, the optimization workflow is designed to estimate the appropriate parameters of GBW in the time-frequency analysis of seismic data. For both noiseless and noisy synthetic signals from sedimentary cyclothems models, the results using spectral components with GBW in CWT show its flexibility and robustness in the adaptive time-frequency representation. Finally, we apply CWT and GBW to three-dimensional seismic data to demonstrate their potential for discriminating vertical parts of river channels and depicting more distinct horizontal slices of the river channels. The application of CWT with GBW provides a potential technique for improving the resolution of exploration seismic interpretations.
2 GBW Principle
Considering the 141 characteristics of source sub-wavelets (Neidell, 1991), this probability distribution should at least satisfy the following conditions: smooth, unimodal, some oblique, and just the Beta distribution can meet such requirements.
Since its density function can present various shapes, we believe that in the frequency domain, wavelets are similar to the Beta distribution. Let B(·, ·) be the beta function, for 0 ≤ x ≤ 1, and parameters α > 0 and β > 0, the probability density function of the Beta distribution is defined as:
Therefore, we propose a progressive wavelet family called Generalized Beta Wavelet (GBW), which is a bi-parameter analytical wavelet family:
Among them, U(w) is the unit step function, αα, β are normalization constants, and α and β are two parameters that control the wavelet shape. To be an effective wavelet, it must have α > 0 and β > 0. Since φα,β(0) = 0, GBW obviously has zero mean and finite energy, and satisfies the "permissible condition".
3 Simulation results

## Images

![(Time-Frequency Analysis)Generalized Beta Wavelet Transform [Attached MATLAB Code]](01.png)
![(Time-Frequency Analysis)Generalized Beta Wavelet Transform [Attached MATLAB Code]](02.jpg)
![(Time-Frequency Analysis)Generalized Beta Wavelet Transform [Attached MATLAB Code]](03.jpg)
![(Time-Frequency Analysis)Generalized Beta Wavelet Transform [Attached MATLAB Code]](04.jpg)
![(Time-Frequency Analysis)Generalized Beta Wavelet Transform [Attached MATLAB Code]](05.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
