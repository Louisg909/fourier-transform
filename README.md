# Fourier Transform

## To do:
- Read up on fast fourier transform techniques
- Write function to do an efficient fourier transform
- compare to numpy's fast fourier transform code to see if I can do it any more efficiently

(note: I may change this repository to be a signal processing repository where fourier transform is one of the tools used)

## Fourier Transform
The Fourier Transform is a mathematical tool thought up by Joseph Fourier in his efforts to solve the heat equation, however, thesedays It has gone alot further, with uses ranging from music EQ-ing to data processing.
In data analysis, the data is in a descrete form so the descrete Fourier transform is used:

$$X_k=\sum_{n=0}^{N-1}x_n\cdot e^{-\frac{i2\pi}{N}kn$$
