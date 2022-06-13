# Circle_Method
CV calculation with Circle Method
% Calculate conduction velocity via the Circle Method
%
% [AvgSpeed, Angle]= CV_CircleMethod( LAT, r, row, col, SpaceScale)
%
% Inputs
%          LAT     2-D matrix of Local Activation Time in [ms]
%            r     radius of the circle used to calulate time difference in [px]
%          row     row at which CV is being calculated
%          col     column at which CV is being calculated
%   SpaceScale     spatial resolution in [mm/px]
%
% Outputs
%     AvgSpeed     speed of the wave front
%        Angle     angular orientation of the wave front propagation 
