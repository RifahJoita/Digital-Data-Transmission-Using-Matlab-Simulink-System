# Digital-Data-Transmission-Using-Matlab-Simulink-System
Developed a digital data transmission system which performs A/D conversion, digital modulation, multiplexing in order to transmit all the data from transmitter to receiver and vice-versa using Matlab Simulink.

Environment description:
1. Used 4 different message sources with frequency 2kHz, 5kHz, 4kHz and 4kHz.
2. Channel bandwith 16-80 kHz
3. A/D conversion was done using interger to bit converter.
4. Pulse Code Modulation was applied using Sample and Hold, Quantizer and Uniform Encoder.
5. Multiplexed the four frequency signals and QPSK modulated.
6. The signal was QPSK demodulated and demultiplexed.
7. Signal was digital to analog converted in Bit to integer converter.
8. PCM demodulation was done using Uniform Decoder and Butterworth filter.
9. The received signals were shown in 4 oscilloscopes. 
