
 seattle_chicago_ds_051120

Welcome to the Flatiron Data Science Bootcamp.  We are so excited to lead you through this expansive journey.  We will update this repo with links to your lecture and warmup material. <br><br>

# [Cohort Link - Chicago](https://wework.zoom.com/j/92291566428?pwd=bzNWb0VoRmtlQVpaSnJqeFhZYTFTZz09)
This is a zoom meeting space for your corhort to use. Consider this your virtual table :)

# [Cohort Link - Seattle ](https://wework.zoom.com/j/97710512518?pwd%3DZ24rM1FkQkduSTF4R2oyR3FUTUVRdz09&sa=D&ust=1589391696884000&usg=AOvVaw0ReTIjAZWeILYVBzYTALHK)
This is a zoom meeting space for your corhort to use. Consider this your virtual table :)


# Calendar (Central Time)
<iframe src="https://calendar.google.com/calendar/embed?src=flatironschool.com_8cd3oqpuhfvj7hplfjbria9590%40group.calendar.google.com&ctz=America%2FChicago" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Calendar (Pacific Time)
<iframe src="https://calendar.google.com/calendar/embed?src=flatironschool.com_t1srpaj0clk1dbsomgfmp213n8%40group.calendar.google.com&ctz=America%2FLos_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
<br>
<br>
Maintaining a well organized project directory is an important part of data science. To start practicing your organization, create a directory somewhere on your computer (probably in the top level of ~/Documents) where you will clone the forked versions of the lecture repos.  It could perhaps look like the structure below.

```
chi_sea_ds
├── module_1/ 
│   ├── week_1/ 
│   ├── week_2/ 
│   └── week_3/ 
├── module_2/ 
│   ├── week_4/ 
│   ├── week_5/ 
│   └── week_6/ 
├── module_3/ 
│   ├── week_7/ 
│   ├── week_8/ 
│   └── week_9/ 
├── module_4/ 
│   ├── week_10/    
│   ├── week_11/ 
│   └── week_12/ 
└── module_5/ 
    ├── week_13/ 
    ├── week_14/ 
    └── week_15/ 
```

How you want to interact with the repositories is also up to you, but we suggest to fork each repo onto your personal github account, then clone the forked version onto your local computer. Once you have cloned the fork, you may want to set the upstream remote to the original.

`
$ git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git
` 

Once you have run the above command, run:

`
git remote -v
`

You should see two remotes, the origin pointing towards your forked repo, and an upstream pointing towards the original.

> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)<br>
> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)<br>
> upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (fetch)<br>
> upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (pull)<br>

This way, you can make changes to the notebooks on your local computer, then push your changes to your fork.  

**Quick note:** When creating your repo structure, do not initialize or clone reposistories within folders that are themselves git repos.  

## Module 1, Week 1
|Day |Subject|Link|Video|
|------------ |-----|---|--- |
|1 | Program Intro|  [Intro_deck](https://docs.google.com/presentation/d/1qpujdemiC5SS2_BIwJf5aypD5kV6UAnsVZo9f78TywY/edit#slide=id.g84719f3c09_0_5)  |[Program Intro](https://www.youtube.com/watch?v=OT9LfBbEQaI&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=2&t=0s) |
|1 | Unix Fundamentals| [Unix Fundamentals Deck](https://docs.google.com/presentation/d/1mcCqBkziqk33hSipbwtnt-FcA5DG5LcCoxM0Ul698os/edit#slide=id.g5b87c484ed_1_154) | |
|1 | Environment Setup| [Professional Data Science Environment](https://docs.google.com/presentation/d/140hJ5IwnGifAm3eyxSgN85xd9XqLzwZOHek3uLVT0LY/edit#slide=id.g5b87c484ed_1_154) |[Pro DS Envivornment](https://www.youtube.com/watch?v=a-WXyFxP2yQ&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=5&t=0s) |
|1 | Terminal Exercise| [repo_creator](https://github.com/learn-co-students/terminal_cave-seattle-chicago-ds) | |
|2 | Python Part 1| [Python 101 Notebook](https://github.com/learn-co-students/python_101_seattle-chicago-ds)  |[Python 101](https://www.youtube.com/watch?v=XPpU57plqGs&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=3&t=0s)  |
|2 | Github | [github deck](https://docs.google.com/presentation/d/1t9RMDX9BAankOSKLsxRKciBZtDDYpRakhd8QsSlP5Ao/edit#slide=id.g65767c560f_1_0)  | [Github Basics_Partial](https://www.youtube.com/watch?v=DkouecudixI&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=4&t=0s)  |
|2 | Github | [Github Codealong](https://github.com/learn-co-students/git_chi_sea_ds/)  |  |
|3 | Python Part 2| [Python 201 Notebook](https://github.com/learn-co-students/python_202_seattle-chicago-ds) |[python_202](https://www.youtube.com/watch?v=tSC_HfSFxvk&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=6&t=0s)  |
|3 | Exploratory Data Analysis | [EDA Deck](https://docs.google.com/presentation/d/1gkCgfGF6vMU6wZv6QOlu6-94tm4jSo-4jumyzFHdBEw/edit#slide=id.g5b87c484ed_1_154)  |[EDA](https://www.youtube.com/watch?v=TUdfS4-EPuo&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=8&t=0s)   |
|3 | Exploratory Data Analysis| [Data Analysis Notebook](https://github.com/gadamico/data_analysis_built_in_types)  |[EDA_same_as_above](https://www.youtube.com/watch?v=TUdfS4-EPuo&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=8&t=0s)   |
|4 | Data Viz | [MPL and SNS_notebooks](https://github.com/learn-co-students/data_viz_chi_sea_ds_051120) |[data viz](https://www.youtube.com/watch?v=19jCXiwpwRc&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=7&t=0s)  |
|4 | Numpy| [Intro to Numpy notebook](https://github.com/learn-co-students/numpy_seattle-chicago-ds/)| [numpy](https://www.youtube.com/watch?v=4ttg4-yicOo&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=9&t=0s) |
|5 | Pandas p1| [Intro to Pandas notebooks](https://github.com/learn-co-students/pandas1_seattle-chicago-ds) | [pandas_1](https://www.youtube.com/watch?v=fFYW53QK5QU&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=10&t=0s) |
| - |Blogs| [Blogs Deck](https://docs.google.com/presentation/d/1gD7Ta1eYuFKPuBZXM7KX0RuGg2xjMcRK2rjbZbdbiyM/edit#slide=id.g522373b1e4_0_0) ||

## Module 1, Week 2
|Day |Subject|Link|Video|
|------------ |-----|---|--- |
|1 |Data Cleaning with Pandas |[pandas_p2](https://github.com/learn-co-students/pandas2_seattle-chicago-ds) |  |   
|1 |Descriptive Stats|[descriptive stats](https://github.com/learn-co-students/descriptive_stats_seattle-chicago-ds) |[decriptive_stats](https://www.youtube.com/watch?v=4sjDGs1MlOw&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=10)  |   
|2 |Reshaping Data in Pandas |[reshaping](https://github.com/learn-co-students/small_multiples_and_more_pandas_seattle-chicago-ds)|[small_multiples](https://www.youtube.com/watch?v=HFknjzbB7aI&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=11) |
|2 |Intro to Relational Databases|[rdbms](https://github.com/learn-co-students/rdbms_seattle-chicago-ds)|[sql_video](https://www.youtube.com/watch?v=v0mQYXA_7qM&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=12) |
|3 |SQL Practice |[sql_whiteboard](https://github.com/learn-co-students/seattle_chicago-sql-whiteboarding) | 
|3 |json api mongo |[json_api_mongo](https://github.com/learn-co-students/json_apis_mongo_seattle-chicago-ds)|[json-api-mongo-video](https://www.youtube.com/watch?v=aHCMBigAsBo&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=15&t=0s)|
|4 |webscraping|[webscraping](https://github.com/learn-co-students/webscraping_seattle-chicago-ds)|[webscraping_video](https://www.youtube.com/watch?v=uZJ8ML1qTxQ&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=16&t=0s)|

## Module 2, Week 1
|Day |Subject|Link|Video|
|------------ |-----|---|----|
|1 |Intro|[scenarios](https://github.com/learn-co-students/probability_seattle-chicago-ds) | |
|1 |Probabilities and Combinatorics|[prob_and_combs](https://github.com/learn-co-students/probability_seattle-chicago-ds) |[probability_video](https://www.youtube.com/watch?v=Hg0ROW-3W9g&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=17&t=0s) |
|2 | Distributions | [distributions](https://github.com/learn-co-students/distributions_sea-chi-ds/)|[distributions_p1](https://www.youtube.com/watch?v=hgrYgE6W-S8&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=18&t=0s)| 
|2 | Distributions | [distributions](https://github.com/learn-co-students/distributions_sea-chi-ds/)|[distributions_p2](https://www.youtube.com/watch?v=c-qCVZChdG4&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=25&t=0s) | 
|3 | Sampling and CLT| [sampling_and_clt](https://github.com/learn-co-students/distributions_sea-chi-ds/)|[sampling_and_cli_video](https://www.youtube.com/watch?v=sL79yi_XVmM&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=19&t=0s) | 
| 4 | Confidence Intervals|[CI](https://github.com/learn-co-students/on_confidence_intervals_seattle-chicago-ds)|[CI_video](https://www.youtube.com/watch?v=uNG07MIQylI&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=20&t=0s)|
| 4 | Hypothesis Testing| [Hypo_test](https://github.com/learn-co-students/hypothesis_testing_seattle-chicago-ds)|[hypo_test_video](https://www.youtube.com/watch?v=-VmZvryL1Ls&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=21&t=0s)|
| 5 | Effect Size and Power | [power_and_effect](https://github.com/learn-co-students/effect_size_power_seattle-chicago-ds) |[p_and_e_video](https://www.youtube.com/watch?v=yQM9cszhAnk&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=24&t=0s)|

## Module 2, Week 2
|Day |Subject|Link|Video|
|------------ |-----|---|----|
|1| Bayes Theorem| [Bayes](https://github.com/learn-co-students/bayesian_reasoning_seattle-chicago-ds)|[Bayes_video](https://www.youtube.com/watch?v=whxnBCAJdvc&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=26)|
|2| ANOVA | [ANOVA](https://github.com/learn-co-students/ANOVA_seattle-chicago-dsc) |[ANOVA_video](https://www.youtube.com/watch?v=6n6V61l6Bf4&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=29&t=0s)|
|2| Linear Regression | [LR](https://github.com/learn-co-students/linear_regression_seattle-ds)|[LR_p1_video](https://www.youtube.com/watch?v=32N8Vxh1U5Q&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=29)|
|3| Linear Regression | [LR_p2_video](https://docs.google.com/presentation/d/1DwCvkgzA0PmdwZJAqD82QJnwcR_AnGcFM74s5QxpDkQ/edit?usp=sharing) |[LR_p1](https://www.youtube.com/watch?v=N7hfcg7Xte8&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=30)|
|3| Bootstrapping| [Bootstrap](https://github.com/learn-co-students/bootstrapping_seattle-ds) |[bootstrap_vid](https://www.youtube.com/watch?v=Cbjm9UGygEk&list=PLc6AmvC5ZybzC7QnaXyhyREbhIfUIEgSc&index=31)|
|4| LR Pair| [lr_pair](https://github.com/learn-co-students/linear_regression_pair-sea-chi-ds) |