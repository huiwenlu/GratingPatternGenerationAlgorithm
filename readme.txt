2014 May Hui-Wen Lu-Walther

-----------------------------------------------------------
Use Matlab and Dipimage tool box.
-----------------------------------------------------------

1. Search for gratings

call "CalcGrat.m" function 

% Example: CalcGrat(2.800, 2.850, 3, 1, 3)
% Example: CalcGrat(2.700, 2.850, 9, 4, 6)



2. After some grating parameters are found, generate binary grating images with those parameters and check the phase of each grating image.

call "FourDimGrating2png_HW.m" function 

Example: FourDimGrating2png_HW([5 17 25 39 19 9;-26 -19 -9 8 17 25;2 19 33 6 17 9;4 -17 -9 4 19 33],3,3,1,'o6p3_LSIM')

