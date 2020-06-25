# FFT-Reverb
R&amp;D for a pure FFT based reverb 


The initial idea is to leaky integrate a FFT (with a time constant decay), and phase modulate the bins (maybe SHM resonant springs and some sinusoids).

FFT will be overlap and add with a appropriate window.

Hoping that the springs store the historical impulse information and make it sound like a delay based reverb.

