# maskedEnhancement
We propose a method based on the theory of Compressed Sensing to obtain an edge mask from the sparse Total Variation image to remove any high-frequency component that is not a real edge while maintaining the real boundaries of the image.
The pipeline will be the following: the \acrshort{tv} image will be processed and smoothed with a diffusion filter, which will then be used as a mask on the high-frequency details of the image to remove the noise and preserve the edges.
Diffusion filtering was implemented in MATLAB the function developed by Lopes "https://www.mathworks.com/matlabcentral/fileexchange/14995-anisotropic-diffusion-perona-malik".
The rest of the images I programmed in MATLAB.
