---
title: "My Pre-Registration"
output: html_document
bibliography: example.bib
csl: apa.csl  
---

# Pre-registration Template
Adapted from [https://osf.io/preprints/metaarxiv/epgjd](https://osf.io/preprints/metaarxiv/epgjd) into markdown format.

<details>

-   [Study Information](#study-information)
    -   [1. Title](#1-title)
    -   [2. Authors](#2-authors)
    -   [3. Description](#3-description)
    -   [4. Hypotheses](#4-hypotheses)
-   [Design Plan](#design-plan)
    -   [5. Study type](#5-study-type)
    -   [6. Blinding](#6-blinding)
    -   [7. Is there any additional blinding in this study?](#7-is-there-any-additional-blinding-in-this-study-)
    -   [8. Study design](#8-study-design)
    -   [9. Randomization](#9-randomization)
-   [Sampling Plan](#sampling-plan)
    -   [10. Existing data](#10-existing-data)
    -   [11. Explanation of existing data](#11-explanation-of-existing-data)
    -   [12. Data collection procedures](#12-data-collection-procedures)
    -   [13. Sample size](#13-sample-size)
    -   [14. Sample size rationale](#14-sample-size-rationale)
    -   [15. Stopping rule](#15-stopping-rule)
-   [Variables](#variables)
    -   [16. Manipulated variables](#16-manipulated-variables)
    -   [17. Measured variables](#17-measured-variables)
    -   [18. Indices](#18-indices)
-   [Analysis Plan](#analysis-plan)
    -   [19. Statistical models](#19-statistical-models)
    -   [20. Transformations](#20-transformations)
    -   [21. Inference criteria](#21-inference-criteria)
    -   [22. Data exclusion](#22-data-exclusion)
    -   [23. Missing data](#23-missing-data)
    -   [24. Exploratory analysis](#24-exploratory-analysis)
-   [Other](#other)
    -   [25. Other](#25-other)

</details>

# Study Information 

## 1. Title 

> Provide the working title of your study. It may be the same title that you submit for publication of your final manuscript, but it is not a requirement.
>
> - Example: Effect of sugar on brownie tastiness. 
>
> More info: The title should be a specific and informative description of a project. Vague titles such as 'Fruit fly preregistration plan' are not appropriate.

## 2. Authors 

> Your names here

## 3. Description 

> Please give a brief description of your study, including some background, the purpose of the of the study, or broad research questions. 
>
> NOTE that for the sake of this class, we are expecting longer descriptions than required in the OSF template. Please see the assignment description for more details. 
> 
> Here is an example of how to cite a source in your Description [@wright2023auditory].
> NOTE that this reference gets pulled from the .bib file that you define in your YAML header at the top of this document. You should swap out my `example.bib` file with your own bib file. You can export a .bib file from your preferred reference management software. Or you can create your own. Just make sure the filename is defined properly above, and sources will automatically get integrated into your text and compiled into a reference list at the end of this document. To get the references to display in proper APA style, you should make sure the appropriate .csl file is fined in the YAML header. You can find a large list of different .csl files here: [https://github.com/citation-style-language/styles](https://github.com/citation-style-language/styles). For ease, I have included the `apa.csl` file in the course resources [here.](apa.csl)
> 
> If you want an in-text citation that does not involve paranthesis, e.g., to say something like "@wright2023auditory show...", then just leave the square brackets off of the citation (`@refkeyhere` vs. `[@refkeyhere]`). 
>
> The [example.bib](example.bib) file is also in the course resources. If you are ever confused about where to find these files, you can always go to the source code for this website: [https://github.com/Perception-Lab-PNB3EE3/courseBook/tree/main](https://github.com/Perception-Lab-PNB3EE3/courseBook/tree/main)

## 4. Hypotheses 

> List specific, concise, and testable hypotheses. Please state if the hypotheses are directional or non-directional. If directional, state the direction. A predicted effect is also appropriate here. If a specific interaction or moderation is important to your research, you can list that as a separate hypothesis.
>
> -   Example: If taste affects preference, then mean preference indices will be higher with higher concentrations of sugar.


# Design Plan 

> In this section, you will be asked to describe the overall design of your study. Remember that this research plan is designed to register a single study, so if you have multiple experimental designs, please complete a separate preregistration.

## 5. Study type 

> **Experiment** - A researcher randomly assigns treatments to study subjects, this includes field or lab experiments. This is also known as an intervention experiment and includes randomized controlled trials.
>
> **Observational Study** - Data is collected from study subjects that are not randomly assigned to a treatment. This includes surveys, ñnatural experiments,î and regression discontinuity designs.
>
> **Meta-Analysis** - A systematic review of published studies.
>
> **Other** - please describe.

## 6. Blinding 
> Blinding describes who is aware of the experimental manipulations within a study. Mark all that apply.

- [x] No blinding is involved in this study.

- [ ] For studies that involve human subjects, they will not know the treatment group to which they have been assigned.

- [ ] Personnel who interact directly with the study subjects (either human or non-human subjects) will not be aware of the assigned treatments. (Commonly known as “double blind”)

- [ ] Personnel who analyze the data collected from the study are not aware of the treatment applied to any given group.

## 7. Is there any additional blinding in this study? 

> Please outline anything not covered by the question above.

## 8. Study design 

> Describe your study design. Examples include two-group, factorial, randomized block, and repeated measures. Is it a between (unpaired), within-subject (paired), or mixed design? Describe any counterbalancing required. Typical study designs for observation studies include cohort, cross sectional, and case-control studies.
>
> -   Example: We have a between subjects design with 1 factor (sugar by mass) with 4 levels.
>
> More info: This question has a variety of possible answers. The key is for a researcher to be as detailed as is necessary given the specifics of their design. Be careful to determine if every parameter has been specified in the description of the study design. There may be some overlap between this question and the following questions. That is OK, as long as sufficient detail is given in one of the areas to provide all of the requested information. For example, if the study design describes a complete factorial, 2 X 3 design and the treatments and levels are specified previously, you do not have to repeat that information.

## 9. Randomization 

> If you are doing a randomized study, how will you randomize, and at what level?
>
> -   Example: We will use block randomization, where each participant will be randomly assigned to one of the four equally sized, predetermined blocks. The random number list used to create these four blocks will be created using the web applications available at <http://random.org>.
>
> More info: Typical randomization techniques include: simple, block, stratified, and adaptive covariate randomization. If randomization is required for the study, the method should be specified here, not simply the source of random numbers.

# Sampling Plan 

> In this section we'll ask you to describe how you plan to collect samples, as well as the number of samples you plan to collect and your rationale for this decision. Please keep in mind that the data described in this section should be the actual data used for analysis, so if you are using a subset of a larger dataset, please describe the subset that will actually be used in your study.

## 10. Existing data 

> Preregistration is designed to make clear the distinction between confirmatory tests, specified prior to seeing the data, and exploratory analyses conducted after observing the data. Therefore, creating a research plan in which existing data will be used presents unique challenges. Please select the description that best describes your situation. Please do not hesitate to contact us if you have questions about how to answer this question ([prereg\@cos.io](mailto:prereg@cos.io){.email}).

-   [x] Registration prior to creation of data: As of the date of submission of this research plan for preregistration, the data have not yet been collected, created, or realized.
-   [ ] Registration prior to any human observation of the data: As of the date of submission, the data exist but have not yet been quantified, constructed, observed, or reported by anyone - including individuals that are not associated with the proposed study. Examples include museum specimens that have not been measured and data that have been collected by non-human collectors and are inaccessible.
-   [ ] Registration prior to accessing the data: As of the date of submission, the data exist, but have not been accessed by you or your collaborators. Commonly, this includes data that has been collected by another researcher or institution.
-   [ ] Registration prior to analysis of the data: As of the date of submission, the data exist and you have accessed it, though no analysis has been conducted related to the research plan (including calculation of summary statistics). A common situation for this scenario when a large dataset exists that is used for many different studies over time, or when a data set is randomly split into a sample for exploratory analyses, and the other section of data is reserved for later confirmatory data analysis.
-   [ ] Registration following analysis of the data: As of the date of submission, you have accessed and analyzed some of the data relevant to the research plan. This includes preliminary analysis of variables, calculation of descriptive statistics, and observation of data distributions. Please see cos.io/prereg for more information.

## 11. Explanation of existing data 

> If you indicate that you will be using some data that already exist in this study, please describe the steps you have taken to assure that you are unaware of any patterns or summary statistics in the data. This may include an explanation of how access to the data has been limited, who has observed the data, or how you have avoided observing any analysis of the specific data you will use in your study.
>
> -   Example: An appropriate instance of using existing data would be collecting a sample size much larger than is required for the study, using a small portion of it to conduct exploratory analysis, and then registering one particular analysis that showed promising results. After registration, conduct the specified analysis on that part of the dataset that had not been investigated by the researcher up to that point.
>
> More info: An appropriate instance of using existing data would be collecting a sample size much larger than is required for the study, using a small portion of it to conduct exploratory analysis, and then registering one particular analysis that showed promising results. After registration, conduct the specified analysis on that part of the dataset that had not been investigated by the researcher up to that point.

## 12. Data collection procedures 

> Please describe the process by which you will collect your data. If you are using human subjects, this should include the population from which you obtain subjects, recruitment efforts, payment for participation, how subjects will be selected for eligibility from the initial pool (e.g. inclusion and exclusion rules), and your study timeline. For studies that donÍt include human subjects, include information about how you will collect samples, duration of data gathering efforts, source or location of samples, or batch numbers you will use.
>
> -   Example: Participants will be recruited through advertisements at local pastry shops. Participants will be paid \$10 for agreeing to participate (raised to \$30 if our sample size is not reached within 15 days of beginning recruitment). Participants must be at least 18 years old and be able to eat the ingredients of the pastries.
>
> More information: The answer to this question requires a specific set of instructions so that another person could repeat the data collection procedures and recreate the study population. Alternatively, if the study population would be unable to be reproduced because it relies on a specific set of circumstances unlikely to be recreated (e.g., a community of people from a specific time and location), the criteria and methods for creating the group and the rationale for this unique set of subjects should be clear.

## 13. Sample size 

> Describe the sample size of your study. How many units will be analyzed in the study? This could be the number of people, birds, classrooms, plots, interactions, or countries included. If the units are not individuals, then describe the size requirements for each unit. If you are using a clustered or multilevel design, how many units are you collecting at each level of the analysis?
>
> -   Example: Our target sample size is 280 participants. We will attempt to recruit up to 320, assuming that not all will complete the total task.
>
> More information: For some studies, this will simply be the number of samples or the number of clusters. For others, this could be an expected range, minimum, or maximum number.

## 14. Sample size rationale 

> This could include a power analysis or an arbitrary constraint such as time, money, or personnel.
>
> -   Example: We used the software program G\*Power to conduct a power analysis. Our goal was to obtain .95 power to detect a medium effect size of .25 at the standard .05 alpha error probability.
>
> More information: This gives you an opportunity to specifically state how the sample size will be determined. A wide range of possible answers is acceptable; remember that transparency is more important than principled justifications. If you state any reason for a sample size upfront, it is better than stating no reason and leaving the reader to "fill in the blanks." Acceptable rationales include: a power analysis, an arbitrary number of subjects, or a number based on time or monetary constraints.

## 15. Stopping rule 

> If your data collection procedures do not give you full control over your exact sample size, specify how you will decide when to terminate your data collection.
>
> -   Example: We will post participant sign-up slots by week on the preceding Friday night, with 20 spots posted per week. We will post 20 new slots each week if, on that Friday night, we are below 320 participants.
>
> More information: You may specify a stopping rule based on p-values only in the specific case of sequential analyses with pre-specified checkpoints, alphas levels, and stopping rules. Unacceptable rationales include stopping based on p-values if checkpoints and stopping rules are not specified. If you have control over your sample size, then including a stopping rule is not necessary, though it must be clear in this question or a previous question how an exact sample size is attained.

# Variables 

> In this section you can describe all variables (both manipulated and measured variables) that will later be used in your confirmatory analysis plan. In your analysis plan, you will have the opportunity to describe how each variable will be used. If you have variables which you are measuring for exploratory analyses, you are not required to list them, though you are permitted to do so.

## 16. Manipulated variables 

> Describe all variables you plan to manipulate and the levels or treatment arms of each variable. This is not applicable to any observational study.
>
> -   Example: We manipulated the percentage of sugar by mass added to brownies. The four levels of this categorical variable are: 15%, 20%, 25%, or 40% cane sugar by mass.
>
> More information: For any experimental manipulation, you should give a precise definition of each manipulated variable. This must include a precise description of the levels at which each variable will be set, or a specific definition for each categorical treatment. For example, "loud or quiet," should instead give either a precise decibel level or a means of recreating each level. 'Presence/absence' or 'positive/negative' is an acceptable description if the variable is precisely described.


## 17. Measured variables 

> Describe each variable that you will measure. This will include outcome measures, as well as any predictors or covariates that you will measure. You do not need to include any variables that you plan on collecting if they are not going to be included in the confirmatory analyses of this study.
>
> -   Example: The single outcome variable will be the perceived tastiness of the single brownie each participant will eat. We will measure this by asking participants 'How much did you enjoy eating the brownie' (on a scale of 1-7, 1 being 'not at all', 7 being 'a great deal') and 'How good did the brownie taste' (on a scale of 1-7, 1 being 'very bad', 7 being 'very good').
>
> More information: Observational studies and meta-analyses will include only measured variables. As with the previous questions, the answers here must be precise. For example, 'intelligence,' 'accuracy,' 'aggression,' and 'color' are too vague. Acceptable alternatives could be 'IQ as measured by Wechsler Adult Intelligence Scale' 'percent correct,' 'number of threat displays,' and 'percent reflectance at 400 nm.'


## 18. Indices 

> If any measurements are going to be combined into an index (or even a mean), what measures will you use and how will they be combined? Include either a formula or a precise description of your method. If your are using a more complicated statistical method to combine measures (e.g. a factor analysis), you can note that here but describe the exact method in the analysis plan section.
>
> -   Example: We will take the mean of the two questions above to create a single measure of 'brownie enjoyment.'
>
> More information: If you are using multiple pieces of data to construct a single variable, how will this occur? Both the data that are included and the formula or weights for each measure must be specified. Standard summary statistics, such as "means" do not require a formula, though more complicated indices require either the exact formula or, if it is an established index in the field, the index must be unambiguously defined. For example, "biodiversity index" is too broad, whereas "Shannon's biodiversity index" is appropriate.


# Analysis Plan 

> You may describe one or more confirmatory analysis in this preregistration. Please remember that all analyses specified below must be reported in the final article, and any additional analyses must be noted as exploratory or hypothesis generating.
>
> A confirmatory analysis plan must state up front which variables are predictors (independent) and which are the outcomes (dependent), otherwise it is an exploratory analysis. You are allowed to describe any exploratory work here, but a clear confirmatory analysis is required.


## 19. Statistical models 

> What statistical model will you use to test each hypothesis? Please include the type of model (e.g. ANOVA, multiple regression, SEM, etc) and the specification of the model (this includes each variable that will be included as predictors, outcomes, or covariates). Please specify any interactions, subgroup analyses, pairwise or complex contrasts, or follow-up tests from omnibus tests. If you plan on using any positive controls, negative controls, or manipulation checks you may mention that here. Remember that any test not included here must be noted as an exploratory test in your final article.
>
> -   Example: We will use a one-way between subjects ANOVA to analyze our results. The manipulated, categorical independent variable is 'sugar' whereas the dependent variable is our taste index.
>
> More information: This is perhaps the most important and most complicated question within the preregistration. As with all of the other questions, the key is to provide a specific recipe for analyzing the collected data. Ask yourself: is enough detail provided to run the same analysis again with the information provided by the user? Be aware for instances where the statistical models appear specific, but actually leave openings for the precise test. See the following examples:
>
> -   If someone specifies a 2x3 ANOVA with both factors within subjects, there is still flexibility with the various types of ANOVAs that could be run. Either a repeated measures ANOVA (RMANOVA) or a multivariate ANOVA (MANOVA) could be used for that design, which are two different tests.
> -   If you are going to perform a sequential analysis and check after 50, 100, and 150 samples, you must also specify the p-values you'll test against at those three points.



## 20. Transformations 

> If you plan on transforming, centering, recoding the data, or will require a coding scheme for categorical variables, please describe that process.
>
> -   Example: The "Effect of sugar on brownie tastiness" does not require any additional transformations. However, if it were using a regression analysis and each level of sweet had been categorically described (e.g. not sweet, somewhat sweet, sweet, and very sweet), 'sweet' could be dummy coded with 'not sweet' as the reference category.
>
> More information: If any categorical predictors are included in a regression, indicate how those variables will be coded (e.g. dummy coding, summation coding, etc.) and what the reference category will be.




## 21. Inference criteria 

> What criteria will you use to make inferences? Please describe the information youÍll use (e.g. p-values, bayes factors, specific model fit indices), as well as cut-off criterion, where appropriate. Will you be using one or two tailed tests for each of your analyses? If you are comparing multiple conditions or testing multiple hypotheses, will you account for this?
>
> -   Example: We will use the standard p\<.05 criteria for determining if the ANOVA and the post hoc test suggest that the results are significantly different from those expected if the null hypothesis were correct. The post-hoc Tukey-Kramer test adjusts for multiple comparisons.
>
> More information: P-values, confidence intervals, and effect sizes are standard means for making an inference, and any level is acceptable, though some criteria must be specified in this or previous fields. Bayesian analyses should specify a Bayes factor or a credible interval. If you are selecting models, then how will you determine the relative quality of each? In regards to multiple comparisons, this is a question with few "wrong" answers. In other words, transparency is more important than any specific method of controlling the false discovery rate or false error rate. One may state an intention to report all tests conducted or one may conduct a specific correction procedure; either strategy is acceptable.





## 22. Data exclusion 

> How will you determine what data or samples, if any, to exclude from your analyses? How will outliers be handled? Will you use any awareness check?
>
> -   Example: No checks will be performed to determine eligibility for inclusion besides verification that each subject answered each of the three tastiness indices. Outliers will be included in the analysis.
>
> More information: Any rule for excluding a particular set of data is acceptable. One may describe rules for excluding a participant or for identifying outlier data.





## 23. Missing data 

> How will you deal with incomplete or missing data?
>
> -   Example: If a subject does not complete any of the three indices of tastiness, that subject will not be included in the analysis.
>
> More information: Any relevant explanation is acceptable. As a final reminder, remember that the final analysis must follow the specified plan, and deviations must be either strongly justified or included as a separate, exploratory analysis.


## 24. Exploratory analysis 

> If you plan to explore your data set to look for unexpected differences or relationships, you may describe those tests here. An exploratory test is any test where a prediction is not made up front, or there are multiple possible tests that you are going to use. A statistically significant finding in an exploratory test is a great way to form a new confirmatory hypothesis, which could be registered at a later time.
>
> -   Example: We expect that certain demographic traits may be related to taste preferences. Therefore, we will look for relationships between demographic variables (age, gender, income, and marital status) and the primary outcome measures of taste preferences. Other



# Other 

## 25. Other 

> **(Optional)** If there is any additional information that you feel needs to be included in your preregistration, please enter it here. 

# References
> Include any works cited here. 
