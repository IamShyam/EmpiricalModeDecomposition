# EmpiricalModeDecomposition

This is my take on understanding the relatively new concept of Empirical Mode Decomposition (EMD), which is a technique of finding the components of a given signal using only the input data (the compound signal) that is provided and no other metadata. Unlike other transforms, including Fourier and Laplace, this method is purely data-dependant, which makes it an attraction for the current researchers in this field. EMD finds out the component signals of a given input signal using recursion, and calls them Intrinsic Mode Functions (IMFs), which are necessarily monotonous (having a single frequency).

The demonstration of the working of EMD is shown in the Jupyter notebook named EMD_demo.ipynb
