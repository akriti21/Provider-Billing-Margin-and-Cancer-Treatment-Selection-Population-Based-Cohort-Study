# Provider-Billing-Margin-and-Cancer-Treatment-Selection-Population-Based-Cohort-Study
Cohort creation as well as analysis codes

This contains 11 code files as described below
1.) Code file 1 - Apply inclusion/exclusion criterias to create the cohorts.
2.) Code file 2 - Assign treatment regimen as well as treatment start date to the patients identified in step above.
3.) Code file 3 - Create or clean all patient and provider level variables.
4.) Code file 3b - Import the NPI related datasets from physician compare and NPPES NPI registry.
5.) Code file 4a - Create and clean variables corresponding to treatment regimen such as fractional rank, weighted ranks and margin.  
6.) Code file 4b - Finalize analytical data to be used.
7.) Code file 5a - Family A analyses where we run 2 stages models. 
                   Stage 1 multinomial models are used to predict probability of receiving treatment regimen. 
                   Stage 2 models are mcfadden conditional logit models.
8.) Code file 5d - Family D analyses where we directly use mcfadden conditional logit models.
9.) Code file 6 - Used to create tables and figures for manuscript.
10.) Code file S1 - Sensitivity analysis using Family A (2 Stages model) where we use weighted rank instead of fractional rank.
11.) Code file S2 - Sensitivity analysis using Family A (2 Stages model) where we use margin LM instead of margin HM.
