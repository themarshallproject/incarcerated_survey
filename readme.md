By [Anna Flagg](https://www.themarshallproject.org/staff/anna-flagg)

# Survey of the Incarcerated
The incarcerated population is often presented as a monolith; assumed to be Democrats and liberal-leaning, and characterized with various other similarly broad assumptions. But because of the notorious challenges in accessing incarcerated voices, very little is actually known about their opinions and politics.

Beginning in 2019, The Marshall Project/Slate began a large ongoing reporting project to survey the political views of incarcerated people in American prisons and jails. The survey is being carried out through collaboration with tablet companies serving some facilities, as well as in paper form through [News Inside](https://www.themarshallproject.org/tag/news-inside), The Marshall Project's print publication distributed inside some facilities. Paper questionnaires are mailed in to The Marshall Project by respondents.

Responses are being collected on a rolling basis over several months; by March of 2020 over 8,000 had arrived from incarcerated people across the country. Marshall Project/Slate reporters analyzed that data and reported findings in a series of stories published in March. 

This repository contains a cleaned, formatted and anonymized version of the raw survey data collected as of our March date of publish. In order to protect survey respondents from identification, all direct personal identifiers and open-ended responses were removed from the data. Additionally, some demographic groups were combined when necessary (e.g. rolling up age bins) and some identifiers (geographic in particular) were nulled out to ensure that no one permutation of demographic groups would have a small enough number of responses to allow for identification.

# Limitations
Due to the challenges of reaching incarcerated populations, it is not feasible at this time to reliably access and survey all facilities, geographic areas, and demographic groups. The Marshall Project/Slate is taking efforts to reach as many respondents as feasible, and works to carefully analyze demographic and personal information supplied by respondents to attempt to control for broad factors when interpreting results of the data. 

Ultimately, the Marshall Project/Slate decided not to weight the overall data at the time of publish, both because data collection is still ongoing and because of the difficulty in obtaining population level data for individual prisons and jails vs. state and federal level incarcerated populations. The data should therefore not be considered a representative picture of the entire incarcerated population of the United States.

In our analysis, instead of only focusing on the respondents as a whole, we looked for trends across race, gender and other demographic differences to ensure our reported results were meaningful. We suggest any further interpretation of this public data should be done with similar caution. 

# Timeline
Survey collection is ongoing; this public data is a snapshot of what the team had collected as of March 2020.

# Files
*data/incarcerated_survey_responses-marshallproject_slate-march_2019.csv* Contains the cleaned and anonymized survey responses data

*data/incarcerated_survey_questions-marshallproject_slate-march_2019.csv* Contains a matching between the short-form question descriptors used in the column names of the responses data and the longer question texts used in the survey. Sometimes question texts are slightly expanded to fully clarify the question with context, for instance, in the case of multiple choice questions.

# In the data
**age** Age group of the respondent: *35 or younger*, *36 or older*, *NA* if not given by respondent or withheld for privacy reasons

**identifies_as_man** Whether respondent identified as a man: *TRUE*, *FALSE*, *NA* if withheld

**identifies_as_woman** Whether respondent identified as a woman: *TRUE*, *FALSE*, *NA* if withheld

**identifies_as_hispanic_or_latinx** Whether respondent identified their ethnicity as Hispanic or Latino/a: *TRUE*, *FALSE*, *NA* if withheld

**identifies_as_black** Whether respondent identified their race as black: *TRUE*, *FALSE*, *NA* if withheld

**identifies_as_white** Whether respondent identified their race as white: *TRUE*, *FALSE*, *NA* if withheld

**highest_education_level** Respondent's highest level of education: *High school or GED or less*, *Trade/technical/vocational training, Associate degree, college degree, or more*, *NA* if not given or withheld

**length_in_this_facility** How long respondent has been incarcerated in their current facility: *10 years or less*, *Over 10 years*, *NA* if not given or withheld

**state** State of the facility where respondent is incarcerated: either state abbreviation, *NA* if not given or withheld

**party** Political party respondent identified as belonging to: *The Republican party*, *The Democratic party*, *Independent*, *NA* if not given or withheld

Columns of the form **cj_important_issue_...** Responses to question *Please pick the top three most important criminal justice issues for the next president: ...* for several given issues, *1* if respondent marked given reason as one of the top issues, *0* if not. Refer to *questions* descriptions in *data/incarcerated_survey_questions-marshallproject_slate-march_2019.csv* for details

**all other columns** Responses to the rest of the survey political questions, refer to *questions* descriptions in *data/incarcerated_survey_questions-marshallproject_slate-march_2019.csv* for details

# Contributors
[Nicole Lewis](https://www.themarshallproject.org/staff/nicole-lewis) Staff Writer at The Marshall Project

[Lawrence Bartley](https://www.themarshallproject.org/staff/lawrence-bartley) Director of News Inside at The Marshall Project

[Aviva Shen](https://slate.com/author/aviva-shen) Senior Editor at Slate

[Mark Morgioni](https://slate.com/author/mark-morgioni) Director, Research and Data at Slate

[Anna Flagg](https://www.themarshallproject.org/staff/anna-flagg) Senior Data Reporter at The Marshall Project

# Questions or comments?
Contact Anna Flagg at: aflagg@themarshallproject.org
