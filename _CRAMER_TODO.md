As of right now, _cramer() only does polynomial interpolation with up to 26 datapoints and needs the user to input the datapoints manually as strings delimited by spaces each time one wants to do an interpolation- it can't perform an interpolation on a matrix that has already been created. With these limitations in mind, I plan on adding the following functionality:

*Expand from 26 points to RAM_MAX

*Add coeffMatrix() functionality to allow a $matrix to perform Cramer interpolation without needing to get the datapoints from the user (in other words: coeffMatrix as a new datatype)

*add support for datapoints to be arrays instead of scalar strings

*add support to fetch arrays (or strings) of points from a file
