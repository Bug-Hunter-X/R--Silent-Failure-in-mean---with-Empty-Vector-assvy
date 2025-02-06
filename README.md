# R: Silent Failure in mean() with Empty Vector

This repository demonstrates a common, yet subtle, error in R: the silent failure of the `mean()` function when applied to an empty numeric vector.  The code calculates the mean of an empty vector, which results in a `NaN` value without any warning or error message.  This can lead to unexpected behavior in larger programs.

The solution demonstrates how to check for empty vectors before applying the `mean()` function, thus preventing the silent failure and improving the robustness of the code.