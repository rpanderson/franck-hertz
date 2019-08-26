# Franck-Hertz data analysis
Python data analysis to find the lowest excitation energy of mercury.

**Intended audience:** Undergraduate students and instructors undertaking the canonical Franck-Hertz experiment.

This computational workshop entails:
 * Importing data in CSV format from an oscilloscope.
 * Extracting the metadata from the CSV header.
 * Creating a versatile time-series data type using [`pandas`](https://pandas.pydata.org/).
 * Presentation-quality plotting of the data in parametric form.
 * Extracting a subset of the data based on a compound conditional statement.
 * Performing a moving average using a specified time-interval.
 * Finding the peaks/troughs in the data using [`scipy.signal.find_peaks`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.find_peaks.html).
 * Analysing these peak/trough locations statistically.
 * Reporting the above results as an average/representative splitting, with standard error.
 * Quantifying the linearity of the minima separation splitting using linear regression.
 * Phenomenological multi-peak + polynomial modelling of the data using [`lmfit`](https://lmfit.github.io/lmfit-py/).
 * Observing any variation of the minima separation with peak/trough number, inspired by [Rapior, Sengstock, and Baev, Am. J. Phys. 74, 423 (2006)](https://doi.org/10.1119/1.2174033). 
