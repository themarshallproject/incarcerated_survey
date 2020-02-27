By [Anna Flagg](https://www.themarshallproject.org/staff/anna-flagg)

# Survey of the Incarcerated
Monolith, voices silenced, not heard, very little is known about the views of the incarcerated population.

Beginning in the winter of 2019, The Marshall Project/Slate undertook a large reporting project to survey the political views of incarcerated people in American prisons and jails. The survey was carried out through collaboration with tablet companies serving some facilities, as well as in paper form through News Inside, The Marshall Project's print publication distributed inside some facilities. 

After collecting responses on a rolling basis for several months, by March of 2020 over 8,000 survey responses had arrived from incarcerated people across the country. Marshall Project/Slate reporters analyzed that data and reported findings in a series of stories published in March. 

This repository contains a cleaned, formatted and anonymized version of that raw survey data. 

# Limitations
Due to the difficulty of accessing incarcerated populations, it was not feasible to reliably reach and survey all facilities, geographic areas, and demographic groups in the United States. The Marshall Project/Slate took efforts to reach as many respondents as feasible, and worked to carefully analyze demographic and personal information supplied by respondents to attempt to control for broad factors when interpreting results of the data; however, this survey should in no way be considered a representative picture of the entire incarcerated population of the United States, and any further interpretation of this public data should be done with similar caution. 

# Timeline
Survey collection is ongoing; this public data is a snapshot of what the team had collected as of March 2020.

# Files
**data/incarcerated_survey_responses-marshallproject_slate-march_11_2019.csv** Contains the cleaned and anonymized survey responses data

**data/incarcerated_survey_questions-marshallproject_slate-march_11_2019.csv** Contains a matching from the short-form question descriptors used in the column names of the responses data, and the longer question texts used in the survey. Sometimes question texts are slightly expanded to fully clarify the question with context, for instance in the case of multiple choice questions.

# In the data
**age** Age group of the respondent: *35 or younger*, *36 or older*, *NA* if not given by respondent, *masked* if withheld for privacy reasons

**identifies_as_man** Whether respondent identified as a man: *TRUE* if so, *FALSE* if not,*masked* if withheld

**identifies_as_woman** Whether respondent identified as a woman: *TRUE* if so, *FALSE* if not, *masked* if withheld

**identifies_as_hispanic_or_latinx** Whether respondent identified their ethnicity as Hispanic or Latino/a: *TRUE* if so, *FALSE* if not, *masked* if withheld

**identifies_as_black** Whether respondent identified their race as black: *TRUE* if so, *FALSE* if not, *masked* if withheld

**identifies_as_white** Whether respondent identified their race as white: *TRUE* if so, *FALSE* if not, *masked* if withheld

**highest_education_level** Respondent's highest level of education: *High school or GED or less*, *Trade/technical/vocational training, Associate degree, college degree, or more*, *NA* if not given by respondent, *masked* if withheld

**length_in_this_facility** How long respondent has been incarcerated in their current facility: *10 years or less*, *Over 10 years*, *NA* if not given by respondent, *masked* if withheld

**state** State of the facility where respondent is incarcerated: either state abbreviation, *NA* if not given by respondent, *masked* if withheld

**party** Political party respondent identified as belonging to: *The Republican party*, *The Democratic party
*, *Independent*, *NA* if not given by respondent, *masked* if withheld

**Please pick the top three most important criminal justice issues for the next president: ...** Responses to questions of these form are *1* if respondent marked given reason as one of the top issues, *0* if not. Refer to *questions* descriptions in *data/incarcerated_survey_questions-marshallproject_slate-march_11_2019.csv* for details

**all other columns** Responses to survey questions, Refer to *questions* descriptions in *data/incarcerated_survey_questions-marshallproject_slate-march_11_2019.csv* for details