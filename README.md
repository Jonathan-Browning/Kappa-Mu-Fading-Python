# Kappa-Mu-Fading-Python

The \kappa-\mu fading model implemented in python. Plots the theoretical and simulated envelope porbability density functions (PDFs)

This project uses PySimpleGUI, numpy, matplotlib and tkinter.

This project was developed on a windows OS, using Spyder IDE with Python 3.8. All the dependencies where installed by anaconda.

The input \kappa accepts values in the range 0 to 50.
The input \mu accepts integer values in the range 1 to 10.
The input \hat{r} accepts values in the range 0.5 to 2.5.

Runing main.py to start the GUI displays:
  
![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Fading-Python/main/docs/window.png)

Entering values for the Rician K factor, the root mean sqaure of the signal \hat{r}(the input is the squared value), and \phi the phase parameter:

![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Fading-Python/main/docs/inputs.png)

The theoretical evenlope PDF is plotted to compare with the simulation and gives the execution time for the theoretical calculation and simulation together:

![ScreenShot](https://raw.github.com/Jonathan-Browning/Kappa-Mu-Fading-Python/main/docs/results.png)
