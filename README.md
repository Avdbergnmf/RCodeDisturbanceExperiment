# R Analysis README

## Usage
- Run `DataProcessing.Rmd`
    - This should auto-install the required packages and start an interactive browser window with all plots.

## TO DO
- [x] Fix packages
- [x] Check Questionnaire plots
- [ ] Plot the stepping points / locations!!!
- [ ] Correct step data
- [ ] Remove any steps that were done onto a target (as well as the step afterwards)
- [ ] Get a version of the tracker data with time*v added to one of the positions.


1. Find some way to plot better and get an overview of the "correctness" of the step detection
2. Correct detection
- ONLY count stepoff if current phase has been in effect for a certain threshold.
 - Fix first step (WHICH FOOT)
 - How can there STILL be tiny steps? -> Probably if toe-off is detected during heelstrike of other foot? hmm




## Maybe later when bored
- [ ] fix pattern stuff --> STILL NOT WORKING...
- [ ] Update all packages -> devtools::install_github("coolbutuseless/ggpattern")
    ```
    package ‘Rcpp’ successfully unpacked and MD5 sums checked
    Warning: cannot remove prior installation of package ‘Rcpp’
    Warning: restored ‘Rcpp’
    package ‘fastmap’ successfully unpacked and MD5 sums checked
    Warning: cannot remove prior installation of package ‘fastmap’
    Warning: restored ‘fastmap’
    package ‘cachem’ successfully unpacked and MD5 sums checked
    Warning: cannot remove prior installation of package ‘cachem’
    Warning: restored ‘cachem’
    package ‘utf8’ successfully unpacked and MD5 sums checked
    Warning: cannot remove prior installation of package ‘utf8’
    Warning: restored ‘utf8’
    package ‘fansi’ successfully unpacked and MD5 sums checked
    Warning: cannot remove prior installation of package ‘fansi’
    Warning: restored ‘fansi’
    package ‘farver’ successfully unpacked and MD5 sums checked
    ```