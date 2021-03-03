# Taxonomy of Security Weaknesses in Native Android Apps

The data used in the study is available in the present repository established as an online appendix.

## Description

### RQ1 raw data

**1_github_repository_name.csv** list of 8,157 real-world open-source Android applications.

**2_patterns** folder contains the list of regular expressions (They may vary depending on the needs when being used)

**3_query** BigQuery query in order to retrieve Kotlin projects using GitHub Archive Dataset. One should define (i) the date using YYYY.MM format, (ii) the programming language 'LANG' and (iii) the limit of results 'N'. Morevover, notice thatt we are considering PullRequestEvent as type of event since it is an indicator that developers are working on it.

**4_commits_and_classification.csv** contains the 400 commits together with the classiﬁcation we assigned to them.

**5_taxonomy_validation_.pdf** Construction of the validation taxonomy in order to support the completeness of our main taxonomy. (i) Categories highlighted in red are new categories that emerged while validating the stability of our main taxonomy. Notice that in this case we are presenting the concrete number of artefacts classified under a category and not aggregating them up to the root. 

**6_survey_answers.csv** contains the (anonymized) answers collected from our survey.

**7_tools.txt** contains the list of tools mentioned by developers when answering the survey.
