# AmyloseBroadening

How to use:

1. Input experimental DP (column A) and w(logRh) (column F) into Fitting Template.xlsx on the Region 3 sheet
2. Adjust the cell ranges for the slope and intercept calculations (H1 and H2) to match the range of the region being fitted
3. Copy the experimental DP data to column F of Broadening Template.xlsm and the experimental w(logRh) data to column G of Broadening Template.xlsm
4. Copy the regional exponential fit from column E of Fitting Template.xlsx to column B of Broadening Template.xlsm
5. Adjust the sigma value in Broadening Template.xlsm until the desired fit is achieved (C2) **NOTE: If an unexpected result is obtained for the broadened fit, recalculate all cells in column E of Broadening Template.xlsm**
6. Adjust the range to search for the location of the region's maximum in C13 and C15 to ensure correct normalization
7. Repeat the process for the other regions as desired.  For the subtractive method (worksheets labeled "Sub"), the residual from Region 3 is automatically used as the  experimental w(logRh) data in column G of Broadening Template.xlsm and should not be entered
8. Once all regions are fitted, paste the exponential and broadened fits (and residuals, if applicable) into either the Composite or Composite Sub sheet of Broadening Template.xlsm depending on the method used to obtain the composite plots
