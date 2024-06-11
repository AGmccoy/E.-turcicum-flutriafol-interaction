# Sensitivity of the causal agent of northern leaf blight of corn, _Exserohilum turcicum_, to the demethylase inhibiting fungicide flutriafol
Nolan R. Anderson* & Austin G. McCoy*, Cristina Castellano, Martin I. Chilvers, Eric ALinger, Tom W. Allen, Kaitlyn Bissonnette, Drake Copeland, Nick Hustedde, Tamra A. Jackson-Ziems, Nathan Kleczewski, Christopher Leon, John Mueller, Trey Price, Richard Raid, Alison E. Robertson, Edward J. Sikora, Darcy E. P. Telenko, matthew Wiggins, Kiersten Wise. _Plant Health Progress_. 2024 https://apsjournals.apsnet.org/doi/10.1094/PHP-11-23-0098-RS
* these authors contributed equally to this manuscript

For the current study, you will only need to interact with the file "Model_Selection_GIT_Eturcicumxflutriafol.R" and the associated raw data file "E. turcicum flutriafol sensitivity data for Austin_batch_rep.xlsx"

The current code is well annotated for analysis/EC50 calculation. Less so for graphing and visualization of the data, but we dont do anything too crazy there.

The use of M. Breunig and Z. Noels original code has been cited within the respective manuscript (Breunig and Chilvers 2021). Here we used this code to determine the best model for EC50 calculations and added more code for visualization, testing, data wrangling, etc.

### The code for bulk model selection was forked from the below github and was originally used for _Fusarium_ spp. and Pydiflumetofen testing by Dr. Mikaela Breunig
https://github.com/mikbreunig/Pydiflumetofen

Based off of code from the study: Breunig, M., and Chilvers, M.I. (2021) Baseline sensitivity of _Fusarium graminearum_ from wheat, corn, drybean and soybean to pydiflumetofen in Michigan, USA. Crop Protection Journal 140:105419
