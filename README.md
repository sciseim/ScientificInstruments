# ScientificInstruments

The dataset is based on two surveys that gauged academics’ perceptions on the credibility of references to scientific instruments in natural science journals. The code is written in SPSS, and interrogates two Excel files (Survey 1 Dataset, Survey 2 Dataset). The first line in the dataset contains the label for the variables. An explanation of each variable in the Excel dataset can be found below. Some items (university affiliation, year of earning PhD) have been removed to ensure anonymity of the respondents.

Survey 1: Explanation of transformed variables
Columns AH to AM (Ref_peer_reviewed_j	Ref_star_scientist	Ref_high_impact	Ref_industry_coauthor	Ref_firm_coauthor	Ref_in_high_impact_expensiveVSch) all refer to questions about the importance of information on scientific instruments in various types of publication outlets. 1 = references are very important, 5 = references not important at all.
Column AU (ICA_none) refers to if the respondent has answered yes to any of the questions related to (ICA) entrepreneurial activity. 1 = entrepreneurial activity.
Colummn AX (impact_factor) refers to the 2-year Thompson Reuter impact factor of the respondent's best publication.
Column BA (US1EU0) refers to where the respondent's university is located.
Column BM (budget_dummy) is a transformation of the Budget variable. 1 = 80.000 Euros and higher, 0 = less than 80.000 Euros.
Column BN (gov_dummy) is a transformation of the Government Funds variable. 2 = 76% or more of funding stems from the government, 1 = 75% or less of funding stems from the government.
Column BQ (response_half) refers to if the respondent's answer was among the first half of all respondents (0), or latter half (1).
Column BR (age_dummy1977) refers to the respondent's age. 0 = born before 1976, 1 = born after 1976.
Column BS (impact_dummy7) refers to the impact factor of the respondent's best publication. 0 = impact factor of 6 or less, 1 = impact factor of 7 or more. Same principle for other impact_dummies, BZ and CA).
Columns BT to BX (Professor_responsehalf	Assocprofessor_responsehalf	Assistprofessor_responsehalf	Postdoc_responsehalf	PhDstudent_responsehalf) combines employment status and response half variables (1 = early, 2 = late).
Column CC (Young_highimpact7) refers to if young scholar have published in journals with impact factor of 7 or more (= 2).
Column CF (Young_highimpact9) ibid.

Survey 2: Explanation of transformed variables
Column J (government_dummy) is a transformation of the Government Funds variable. 1 = 76% or more of funding stems from the government, 0 = 75% or less of funding stems from the government. 
Columns M-Q (Reliable_peerreview	Reliable_starscientist	Reliable_highimpact	Reliable_industrycoauthor	Reliable_firmcoauthor) refer to questions about the reliability of information on scientific instruments in various types of publication outlets.
Budget and Government dummies follow same principles as in Survey 1.
