DSP - LABORATORY EXERCISE 1

Group Members:
Krysten Yzabella Juelo
Ayeesha Mamalinta
 
I. OBJECTIVES: 
In this laboratory exercise, the students are expected to: 
  * find Discrete Fourier Transform and Inverse Discrete Fourier Transform of given digital signal..
    
II. MATERIALS: 
  * Software: MATLAB
    
III. PROCEDURE: 
THEORY: 
Basic equation to find the DFT of a sequence is given below.
![image](https://github.com/user-attachments/assets/25d4fe75-35c3-484a-be8d-03ff5733b56e)

Basic equation to find the IDFT of a sequence is given below.
![image](https://github.com/user-attachments/assets/f5676df8-b39c-46f1-a942-045447456ed4)

RESULT: 
VIVA QUESTIONS: 

1. Define signal, Give Examples for 1-D, 2-D, 3-D signals.

A signal is a function that carries information and varies with time or space. A 1-D signal like a sound wave depends on time, a 2-D signal like an image depends on two spatial dimensions, and a 3-D signal like a video depends on space and time.

2. Define transform. What is the need for transform?

A transform is a mathematical operation that converts a signal from one domain to another, such as from time to frequency domain. Transforms are needed to simplify signal analysis, highlight frequency components, and apply filters more easily.

3. Differentiate Fourier transform and discrete Fourier transform.

The Fourier Transform (FT) applies to continuous-time signals and produces a continuous frequency spectrum, while the Discrete Fourier Transform (DFT) is used for discrete-time signals and gives a discrete set of frequency values.

4. Differentiate DFT and DTFT.

The DFT is used for finite-length signals and gives discrete frequency values, while the DTFT is used for infinite-length signals and results in a continuous frequency spectrum.

5. Explain the mathematical formula for calculation of DFT.

The DFT formula is X(k) = \sum_{n=0}^{N-1} x(n) \cdot e^{-j \frac{2\pi}{N} kn}, which converts a time-domain signal into its frequency-domain representation.

6. Explain the mathematical formula for calculation of IDFT.

The IDFT formula is x(n) = \frac{1}{N} \sum_{k=0}^{N-1} X(k) \cdot e^{j \frac{2\pi}{N} kn}, and it is used to recover the original time-domain signal from its frequency-domain form.


7. How to calculate FT for 1-D signal?

The Fourier Transform for a 1-D signal is calculated using X(f) = \int_{-\infty}^{\infty} x(t) \cdot e^{-j2\pi ft} dt, which transforms a continuous-time signal into the frequency domain.

8. What is meant by magnitude plot, phase plot, power spectrum?

A magnitude plot shows the strength of each frequency in a signal. A phase plot shows how much each frequency is shifted. The power spectrum displays the energy distribution across frequencies and is the square of the magnitude.

9. Explain the applications of DFT.

DFT is used in many areas such as signal processing, audio and image compression, frequency analysis, filtering, and feature extraction in pattern recognition.

10. What are separable transforms?

Separable transforms are those that can be applied separately along each dimension of a multi-dimensional signal, such as applying a 1-D DFT row-wise and then column-wise in 2-D image processing.


Exercise: 
1. Find 8-point DFT of the sequence x (n) = [1 2 3 4 4 3 2 1] 
![Screenshot 2025-04-07 175557](https://github.com/user-attachments/assets/6ecd85b5-6d50-4c11-a59d-09baa7b87fa5)
