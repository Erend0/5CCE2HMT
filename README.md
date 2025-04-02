# Heat Transfer Coefficient Calculator

## Overview
This MATLAB script calculates the expected heat transfer coefficients (\(h\)) for thermocouples T8 and T9 using Whitaker's correlation. It compares measured vs. calculated \(h\) values for the "no shield" case U > 0 m/s from experimental data. The script uses air property interpolation for temperatures between 300 K and 500 K, with thermocouple diameters of 1 mm (T8) and 3 mm (T9). 

## Usage
1. Ensure MATLAB is installed.
2. Run `calculate_h_whitaker_final.m` to compute and display the results in a table format.
3. Results are shown for \(U = 0.5, 1.0, 2.0, 4.0 \, m/s.

## AI Disclaimer
This README and the MATLAB script (`calculate_h_whitaker_final.m`) were generated with assistance from Grok, an AI developed by xAI. The AI provided support in structuring the code, performing calculations, and drafting documentation. All outputs have been reviewed for accuracy, but users should verify results for critical applications.

## References
- Air properties data sourced from *Fundamentals of Heat and Mass Transfer* by Frank P. Incropera, David P. DeWitt, Theodore L. Bergman, and Adrienne S. Lavine, Table A.4 (Air at 1 atm).
- Whitaker's correlation is based on standard heat transfer literature for forced convection over a sphere.

## License
MIT License. See `LICENSE` file for details.
