Copyright 2014 Hui-Wen Lu-Walther


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




    This file is part of fastSIM_GratingSearchforSLM.

    fastSIM_GratingSearchforSLM is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    fastSIM_GratingSearchforSLM is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with fastSIM_GratingSearchforSLM.  If not, see <http://www.gnu.org/licenses/>.