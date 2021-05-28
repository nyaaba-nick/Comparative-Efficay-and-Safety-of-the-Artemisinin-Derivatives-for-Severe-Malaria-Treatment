# Comparative-Efficacy-and-Safety-of-the-Artemisinin-Derivatives-for-Severe-Malaria-Treatment

Introduction
This data was produced for a systematic review update and NMA was conducted according to the PRISMA guidelines extension.1 The NMA protocol was registered with PROSPERO registration number CRD420202181902 

Search
We included all published and unpublished RCTs from three Cochrane systematic reviews that compared artemisinin derivatives to quinine in treating severe malaria.3–5 In addition, we combined the search strategies of these previous reviews and updated them by searching the Cochrane Infectious Diseases Group Specialized Register; Cochrane Central Register of Controlled Trials (CENTRAL) in the Cochrane Library; MEDLINE, Embase, LILACS, ISI Web of Science, and trial registers from inception up to February 2021. Example of search strategy shown in S1. There were no limitations regarding language, geographical setting and year of publication.

Method of Collection
Screening the title and abstract, and full-text for eligible studies were completed in duplicate using Rayyan review software6 by the reviewing team independently, blinded to each other. Disagreements were resolved by the other co-reviewers.

Outcomes
Outcomes have pharmacological and clinical relevance. 
Primary Outcome
1.	Mortality.
The proportion of death from all causes was compared between all interventions from onset of treatment.
Secondary Outcomes
1.	Neurological Sequela Events among survivors
The proportion of patients developing neurological sequela was evaluated among those who survived. Subgroup analyses included time-point of neurological sequela assessment (acute vs persistent). 
2.	Coma Recovery time
Mean time in hours from start of treatment to coma recovery was compared among interventions. 
3.	Parasite Clearance time
The mean time in hours from initial administration of antimalarial absence of malaria parasites in blood-film was compared between treatments. 
4.	Fever Clearance Time
The mean time in hours from initial administration of antimalarial to consecutive normothermia (defined in some studies as < 37.5 Degrees Celsius) was compared between treatments.
5.	Adverse events
The proportion of patients experiencing adverse events after treatment was initiated was compared. Both specific events and composite measures were explored. The most frequently reported adverse events were included in the NMA and the others were reported in a table as number of events and proportion experiencing the event. 

Data Extraction

The primary outcome was proportion of death from all causes compared among drugs from onset of treatment. Secondary outcomes were neurological sequela events among survivors, coma recovery time, parasite clearance time, fever clearance time, and adverse events. 
Data Extraction
Mortality, neurological sequela, and adverse events were assessed as binary outcomes whilst the rest as continuous outcomes.The data were extracted using a structured data form into an MS Excel workbook independently by NEA, GA, DSYA, MA and NN. 
This was designed and reviewed by NN, JOM and JH. Name of first author, year of publication, sample size, length of follow up, age group, summary estimate of age and geographical location was recorded for every study. Intervention specific data collected included name of intervention, dose, route of administration, sample size randomised to group and summary age provided. This same information was collected for comparator(s).
For binary outcomes, the number of participants experiencing the event and the number assessed in each intervention group was recorded. For continuous outcomes, arithmetic means and standard deviations for each intervention group, with the numbers assessed in each group were extracted. If the number assessed in each group was not reported, the number randomised in the intervention arm was used. 
Where medians and range or interquartile range were reported instead of the means and standard deviations, they were extracted and the arithmetic means and standard deviations were estimated from the medians and range or interquartile range respectively.7 These estimations were used for the main analysis and later excluded for sensitivity analyses. 
Statistical Analyses
Separate analyses were conducted for adults and children to reduce clinical inconsistency and heterogeneity. NMAs were conducted using a random effect model in a frequentist framework using R (version 3.6.0) netmeta package (version 1.2-1).8 Summary Risk Ratios (RR) for binary outcomes and Mean Differences (MD) for continuous outcomes with 95% confidence intervals (95%CI) were estimated for quinine and the artemisinin derivatives, against each other for all outcomes including hypoglycaemia.9 Network graphs were created with Stata 15 network map.10 League tables and forest plots were used to summarise effect sizes for all possible comparisons, outcomes and subgroups.8 Variability in the effects sizes was assessed globally for the whole network and locally at each possible study design, and it was described with Q and I2 statistics, degrees of freedom, and p-values. Variability in the effect sizes was further decomposed into within-design (heterogeneity) and between-design (inconsistency). Hotspots of inconsistency were identified with net-splitting and net heat plots.11,12 Probability scores (p-scores) were used to rank treatments for each outcome.13 Data from adults and children were combined to conduct subgroup analyses by severe malaria type, study continent, and time point of neurological sequela events. We used Eggers test and a comparison-adjusted funnel plot that incorporates all the effects of bias in a network to assess publication bias.8 All statistical tests were two-sided with a significance level of 0.05.





  

Table 1. Study Characteristics
Author Year	Trial Date	N	%Female
	Country	Cerebral Malaria Only	Follow up(days)	Drugs	Route of 
Administration	Age Group	Agea
(years)
Anh et al 198914
February to December 1989	41	24	Vietnam	Yes	unclear	ASU	IM	Adults	30.26 ± 13.75
							QN	IV		38.68 ± 13.05
Win et al  199215
February 1989 to August 1991	141	-	Myanmar	Yes	unclear	ASU	IV	Adults	23.67 ± 4.8
							AME	IM		22.98 ± 2.62
							QN	IV		22.23 ± 3.87
Karbwang et al 199216
May to Dec 1991	26	4.0	Thailand	No	7	AME	IM	Adults	30.4 ± 10
							QN	IV		31.7 ± 10.4
Hien et al 199217
1989 to 1990	79	11	Vietnam	Yes	unclear	ASU	IV	Adults	29
(16-50)
							AMI	Rectal		30
(15-50)
							QN	IV		28
(19-52)
Walker et al 199318
not stated	54	44	Nigeria	Yes	>28	AME	IM	Children	-
							QN	IV		-
Anh et al 199519
July 1992 to May 1995	190	18	Vietnam	Yes	unclear	ASU	IM	Adults	32.8
(17-62)
							QN	IV		29.1
(16-63)
Karbwang et al 199520
1992 to 1994	102	10	Thailand	No	unclear	AME	IM	Adults	25
(15-55)
							QN	IV		28
(15-54)
Hien et al 199621
not stated	560	24	Vietnam	No	unclear	AME	IM	Adults	30
(15-79)
							QN	IM		30
(15-78)
van Hensbroek et al 199622
1992 to 1994	576	49	Gambia	Yes	28	AME	IM	Children	4 ± 1.8
						28	QN	IV		3.8 ± 1.8
Murphy et al 199623
not stated	160	50	Kenya	Yes	unclear	AME	IM	Children	2.1
(1.2-9)
							QN	IV		2.5
(1.2-12)
Vihn et al 199724
1992 to  1994	180	32	Vietnam	No	unclear	ASU	IV	Adults	30
(15-60)
							ASU	IM		24
(15-66)
							AMI	Rectal		28
(16-62)
							AME	IM		28
(16-65)
Phuong et al 199725
 Aug 1992 to Mar 1995	109	50	Vietnam	No	28	ASU	IM	Children	6
(0.5-14)
							AMI	Rectal		7
(0.7-14)
							QN	IV		5
(0.3-13)
Seaton et al 199826
Jun 1992 to May 1995	33	-	Papua New Guinea	No	28	AME	IM	Adults	-
							QN	IV		
Taylor et al 199827
Jan 1992 to Jun 1994	183	45	Malawi	Yes	>28	AME	IM	Children	2.9 ± 2
							QN	IV		3.2 ± 2
Ojuawo et al 1998	unclear	37		Nigeria	Yes		AME	IM	Children	
							QN	IV		
Olumese et al 199928
not stated	103	47	Nigeria	Yes	28	AME	IM	Children	3.1
							QN	IV		3.2
Thuma et al 200029
Jan 1996 to May 1997	95	47	Zambia	Yes	28	ATE	IM	Children	3.9 ± 2.3
							QN	IV		3.3 ±1.8 
Moyou-Somo et al 200130
 Nov 1995 to Dec 1997	102	42	Cameroon	Yes	28	ATE	IM	Children	3.4
							QN	IV		3.3
Adam et al 200231
Nov 2001 to Jan 2002	41	49	Sudan	No	>28	AME	IM	Children	4.1(2.5)
							QN	IV		3.59(3.2)
Satti et al 200232
 May 1995 to Jun 1996	77	-	Sudan	Yes	28	AME	IM	Children	-
							QN	IV		
Newton et al 200333
May to Jul 1994 and 1995 to 2001	113	43	Thailand	No	unclear	ASU	IV	Adults	25
(15-66)
							QN	IV		25
(15-59)
Huda et al 200334
Apr 2000 to Jul 2001	46	48	India	No	28	AME	IM	Children	6.6 ± 3.5
							QN	IV		5.8 ± 2.4
Mohanty et al 200435
Jan 2000 to Jan 2002	80	40	India	No	28	AME	IM	Children	8.1 ± 3.23
							QN	IV		7.31 ± 3.47
Minta et al 200536
Jun 1993 to Feb 1994 and Jun 1994 to Dec 1994	67	-	Mali	No	unclear	AME	IM	Children	7.3 ± 3.9
							QN	IV		6.3 ± 4.0
Dondorp et al 200537
Jun 2003 to May 2005	1761	30	Bangladesh, Myanmar (Burma), India, and Indonesia.	No	>28	ASU	IV	Both	27.9
							QN	IV		27.9
Haroon et al 200538
July 2000 to August 2002	35	14	India	No	unclear	AME	IM		32
(18-47.5)
							QN	IV		31
(18-47.5)
Aguwa et al 201039
Jul to Oc 2007	90	58	Nigeria	N0	14	AME	IM	Children	3.2 ± 1.7
							QN	Parenteral		3.8 ± 1.3
Phu et al 201040
May 1996 to Jun 2003	370	26	Vietnam	No	unclear	AME	IM	Adults	32.5
(15-77)
							ASU	IM		32
(15-74)
Dondorp et al 201041
Oct 2005 to Jul 2010	5425	48	Mozambique, The Gambia, Ghana, Kenya, Tanzania, Nigeria, Uganda, Rwanda, and Democratic Republic of the Congo	No	>28	ASU	Parenteral	Children	2.8
(1.6-4.2)
							QN	Parenteral		2.9
(1.7-4.3)
Eltahir et al 201042
 Aug to Sep 2010	66	44	Sudan	No	unclear	ASU	IV	Children	4.4 ± 2.6
							QN	IV		4.6 ± 3.4
Osunuga et al  201143–45
not stated	32	38	Nigeria	No	14	AME	IM	Children	6 ± 3.7
							QN	IV		8.2 ± 3.4
Abdallah  et al 201446
October 2012 to December 2012	94	43	Sudan	No	unclear	ASU	IV	Both	23.5 ± 20.2
							QN	IM		21.5 ± 17.6
Bobossi-Serengbe et al 201547
Jun to Aug 2010	212	55	Central African Republic	No	unclear	AME	IM	Children	2.4
							QN	IV		2.5
AMI, Artemisinin; ATE, Arteether; AME, Artemether; ASU, Artesunate; QN, Quinine. 
aAge was reported in mean ± SD, (range/ interquartile range)

 
Table of Definition of Variables

Variables	Descriptions	Cartegories
author	First author	
publication_year	Year of Publication	
author_year	First author with year publication	
review	Cochrane Systematic Review where RCT is from	a=Afolabi et al, e= Esu et al, s= Sinclair et al, n= newly added
N	Total Sample size in RCT	
age_group	Age groups	a=adults, c =children, b=both
study continent	Study Continent	Asia, Africa
c_malaria only	Whether RCT was conducted among participants with Cerebral malaria only ? 	Yes, No
t	Abbreviation for treatments	AMI= Artemisinin, ATT= Arteether, AME=Artemether, ASU=Artesunate, QN=Quinine
T	Treatments	Artemisinin, Arteether, Artemether, Artesunate, Quinine
roa	Route of Administration	IM= Intramuscular, IV= Intravenous, Parenteral, Rectal
mortality_e	Number of deaths	
mortality_n	Total number assessed	
crt_mean	Mean time in hours from start of treatment to coma recovery 	coma recovery time
crt_sd	Standard deviation of mean of come recovery time 	
crt_n	Total number assessed for coma recovery	
pct_mean	Mean time in hours from start of treatment to a negative test 	parasite clearance time
pct_sd	Standard deviation of mean of parasite clearance time	
pct_n	Total number assessed for parasite clearance	
fct_mean	Mean time in hours from start of treatment to resolution of fever	fever clearance time
fct_sd	Standard deviation of mean of fever clearance time	
fct_n	Total number assessed for fever clearance	
neuro	Time of assessment of neurological sequaela events	a=acute (discharge or day 7), p=persistent (28 days and beyond), n= not specified
neuro_e	Number of neurological sequela events 	
neuro_n	Total number assessed for neurological sequaela events	
hypoglycaemia_e	Number of hypogycaemia events	
hypoglycaemia_n	Total number assessed for hypoglycaemia 	
ecg_e	Number of electrocardiogram abnormalities events	eletrocardiogram abnormalities including QT prolongations and subventricular tachycardia
ecg_n	Total number assessed for  electrocardiogram abnormalities	
		





References
1. 	Hutton B, Salanti G, Caldwell DM, et al. The PRISMA extension statement for reporting of systematic reviews incorporating network meta-analyses of health care interventions : Checklist and explanations. Ann Intern Med. 2015;162(11):777-784. doi:https://doi.org/10.7326/M14-2385
2. 	Nyaaba N, Ordonez-Mena J, Hirst J. What are the comparative efficacy and safety of the artemisinin derivatives for treating severe malaria? 2020. https://www.crd.york.ac.uk/prospero/display_record.php?ID=CRD42020218190.
3. 	Esu EB, Effa EE, Opie ON, Meremikwu MM. Artemether for severe malaria. Cochrane Database Syst Rev. 2019;2019(6). doi:10.1002/14651858.CD010678.pub3.
4. 	Afolabi BB, Okoromah CA. Intramuscular arteether for treating severe malaria. Cochrane Database Syst Rev. 2004;(4). doi:10.1002/14651858.cd004391.pub2
5. 	Sinclair D, Donegan S, Lalloo DG. Artesunate versus quinine for treating severe malaria ( Review ) SUMMARY OF FINDINGS FOR THE MAIN COMPARISON. Heal (San Fr. 2011;(4). doi:10.1002/14651858.CD005967.pub4.www.cochranelibrary.com
6. 	Ouzzani M, Hammady H, Fedorowicz Z, Elmagarmid A. Rayyan-a web and mobile app for systematic reviews. Syst Rev. 2016;5(210). doi:10.1186/s13643-016-0384-4
7. 	Wan X, Wang W, Liu J, Tong T. Estimating the sample mean and standard deviation from the sample size, median, range and/or interquartile range. BMC Med Res Methodol. 2014;14(1):1-13. doi:10.1186/1471-2288-14-135
8. 	Rücker G, Krahn U, König J, Efthimiou O, Schwarzer G. netmeta: Network Meta-Analysis using Frequentist Methods. 2020. https://cran.r-project.org/package=netmeta.
9. 	Jackson D, White I, Riley R. Quantifying the impact of between-study heterogeneity in multivariate meta-analyses. Stat Med. 2012;31:3805-3820.
10. 	White I. Network meta-analysis. Stata J. 2015;15:951-985.
11. 	Chaimani A, Salanti G. Visualizing assumptions and results in network meta-analysis : The network graphs package. 2015;(4):905-950. doi:10.1177/1536867X1501500402
12. 	Donegan S, Dias S, Welton NJ. Assessing the consistency assumptions underlying network meta-regression using aggregate data. Res Synth Methods. 2019;10(2):207-224. doi:https://dx.doi.org/10.1002/jrsm.1327
13. 	Rücker G, Schwarzer G. Ranking treatments in frequentist network meta-analysis works without resampling methods. BMC Med Res Methodol. 2015:1-9. doi:10.1186/s12874-015-0060-8
14. 	Anh T, Kim N, Bich N, Huong N n., Phuong N., Al. E. Randomized comparative study of artesunate intravenously and quinine in loading dose IV on severe and complicated malaria. 1989.
15. 	K. W, M. T. Comparison of combinations of parenteral artemisinin derivatives plus oral mefloquine with intravenous quinine plus oral tetracycline for treating cerebral malaria. Bull World Health Organ. 1992;70(6):777-782. http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=emed4&NEWS=N&AN=23032583.
16. 	Karbwang J, Sukontason K, Rimchala W, et al. Preliminary report: A comparative clinical trial of arthemeter and quinine in severe falciparum malaria. Southeast Asian J Trop Med Public Health. 1992;23(4):768-772.
17. 	Hien TT, Arnold K, Vinh H, et al. Comparison of artemisinin suppositories with intravenous artesunate and intravenous quinine in he treatment of cerebral malaria. Trans R Soc Trop Med Hyg. 1992:582-583.
18. 	Walker O, Salako L, Sowunmi A, Omokhodion S. An open randomized comparative study of intramuscular artemether and intravenous quinine in cerebral malaria in children. Trans R Soc Trop Med Hyg. 1993;87(5):564-566. doi:10.1016/0035-9203(93)90092-5
19. 	Anh T, Binh T, Kim N, Al. E. Comparative study of intravenous artesunate followed by oral meﬂoquine versus intravenous quinine in the treatment of severe and complicated malaria in Viet Nam. 1995.
20. 	Karbwang J, Tin T, Rimchala W, et al. Comparison of artemether and quinine in the treatment of severe falciparum malaria in south-east Thailand. Trans R Soc Trop Med Hyg. 1995;89(6):668-671.
21. 	Hien TT, Day NPJ, Phu NH, et al. A controlled trial of artemether or quinine in Vietnamese adults with severe falciparum malaria. N Engl J Med. 1996;335(2):76-83. doi:10.1056/NEJM199607113350202
22. 	Hensbroek MB Van, Onyiorah E, Jaffar S, Schneider G, Kwiatowski D. A trial of artemether or quinine in children with cerebral malaria. N Engl J Med. 1996;335:69-75.
23. 	Murphy S, English M, Waruiru C, et al. An open randomized trial of artemether versus quinine in the treatment of cerebral malaria in African children. Trans R Soc Trop Med Hyg. 1996;90(3):298-301. doi:10.1016/S0035-9203(96)90260-6
24. 	Vinh H, Huong NN, Ha TTB, et al. Severe and complicated malaria treated with artemisinin, artesunate or artemether in Viet Nam. Trans R Soc Trop Med Hyg. 1997;91(4):465-467. doi:10.1016/S0035-9203(97)90287-X
25. 	Phuong CXT, Bethell DB, Phuong PT, et al. Comparison of artemisinin suppositories, intramuscular artesunate and intravenous quinine for the treatment of severe childhood malaria. Trans R Soc Trop Med Hyg. 1997;91(3):335-342. doi:10.1016/S0035-9203(97)90099-7
26. 	Seaton RA, Trevett AJ, Wembri JP, et al. Randomized comparison of intramuscular artemether and intravenous quinine in adult, Melanesian patients with severe or complicated, plasmodium falciparum malaria in Papua New Guinea. Ann Trop Med Parasitol. 1998;92(2):133-139. doi:10.1080/00034983.1998.11813272
27. 	Taylor TE, Wills BA, Courval JM, Molyneux ME. Intramuscular artemether vs intravenous quinine: An open, randomized trial in Malawian children with cerebral malaria. Trop Med Int Heal. 1998;3(1):3-8. doi:10.1046/j.1365-3156.1998.00166.x
28. 	Olumese PE, Björkman A, Gbadegesin RA, Adeyemo AA, Walker O. Comparative efficacy of intramuscular artemether and intravenous quinine in Nigerian children with cerebral malaria. Acta Trop. 1999;73(3):231-236. doi:10.1016/S0001-706X(99)00031-5
29. 	Thuma PE, Bhat GJ, Mabeza GF, et al. A randomized controlled trial of artemotil (β-arteether) in Zambian children with cerebral malaria. Am J Trop Med Hyg. 2000;62(4):524-529. doi:10.4269/ajtmh.2000.62.524
30. 	Moyou-Somo R, Tietche F, Ondoa M, et al. Clinical trial of β-arteether versus quinine for the treatment of cerebral malaria in children in Yaounde, Cameroon. Am J Trop Med Hyg. 2001;64(5):229-232. doi:10.4269/ajtmh.2001.64.229
31. 	Adam I, Idris H, Mohamed-Ali A, Aelbasit I, Elbashir M. Comparison of intramuscular artemether and intravenous quinine in the treatment of Sudanese children with severe falciparum malaria. East Afr Med J. 2002;79(12):621-625.
32. 	Satti G, Elhassan S, Ibrahim S. The efficacy of artemether versus quinine in the treatment of cerebral malaria. J Egypt Soc Parasitol. 2002;32(2):611-623.
33. 	Newton PN, Angus BJ, Chierakul W, et al. Randomized Comparison of Artesunate and Quinine in the Treatment of Severe Falciparum Malaria. Clin Infect Dis. 2003;37(1):7-16. doi:10.1086/375059
34. 	Huda SN, Shahab T, Ali SM, Afzal K, Khan HM. A Comparative Clinical Trial of Artemether and Quinine in Children with Severe Malaria. Indian Pediatr. 2003;40(10):939-945.
35. 	Mohanty AK, Rath BK, Mohanty R, Samal AK, Mishra K. Randomized control trial of quinine and artesunate in complicated malaria. Indian J Pediatr. 2004;71(4):291-295. http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=med5&NEWS=N&AN=15107507.
36. 	Minta D, Sissoko M, Sidibe I, et al. Efficacy and safety of artemether in the treatment of severe end complicated malaria in mali. Mali Med. 2005;20(1-2):28-32.
37. 	Dondorp A, Nosten F, Stepniewska K, Day N, White N; SEAQAMT (SEAQUAMAT) group. Artesunate versus quinine for treatment of severe falciparum malaria: a randomised trial. Lancet. 2005;366(9487):717-725. doi:10.1016/S0140-6736(05)67176-0
38. 	Haroon N, Amichandwala K, Solu MG. Comparative efficacy of quinine and artesunate in the treatment of severe malaria: a randomized controlled trial. JK Sci. 2005;7(1 CC-Infectious Diseases):32‐35. https://www.cochranelibrary.com/central/doi/10.1002/central/CN-00569384/full.
39. 	Aguwa CN, Ukwe C V., Adibe MO. A comparative study of quinine and artemether in the treatment of severe malaria in Nigerian children. Trop J Pharm Res. 2010;9(1):11-17. doi:10.4314/tjpr.v9i1.52030
40. 	Phu NH, Tuan PQ, Day N, et al. Randomized controlled trial of artesunate or artemether in Vietnamese adults with severe falciparum malaria. Malar J. 2010;9:97. doi:10.1186/1475-2875-9-97
41. 	Dondorp AM, Fanello CI, Hendriksen IC, et al. Artesunate versus quinine in the treatment of severe falciparum malaria in African children (AQUAMAT): An open-label, randomised trial. Lancet. 2010;376(9753):1647-1657. doi:10.1016/S0140-6736(10)61924-1
42. 	Eltahir HG, Omer AA, Mohamed AA, Adam I. Comparison of artesunate and quinine in the treatment of Sudanese children with severe Plasmodium falciparum malaria. Trans R Soc Trop Med Hyg. 2010;104(10):684-686. doi:10.1016/j.trstmh.2010.05.009
43. 	Osonuga O, Osonuga A, Osonuga I, Osonuga A. Comparison of Coma Resolution Time in the Course of Treating Childrenwith Severe Falciparum Malaria with Quinine and Artemether. World J Med Sci. 2011;2(1):42-45.
44. 	Osonuga O, Osonuga I. Parasitaemia changes in the course of treatment of severe malaria patients with artemether and quinine (A preliminary study). Maced J Med Sci. 2009;2(4):319-323.
45. 	Osonuga O, Osonuga A, Osonuga I, Osonuga A. Temperature changes in the course of treatment of severe malaria patients with artemether and quinine. Asian J Med Sci. 2011;6(2):42-45.
46. 	Abdallah TM, Elmardi KA, Elhassan AH, et al. Comparison of artesunate and quinine in the treatment of severe Plasmodium falciparum malaria at Kassala hospital, Sudan. J Infect Dev Ctries. 2014;8(5):611-615. doi:https://dx.doi.org/10.3855/jidc.3813
47. 	Bobossi-Serengbe G, Gody JC, Fioboy R, Elowa JB, Manirakiza A. Comparaison de l’efficacité de l’artémether et de la quinine dans le traitement du paludisme grave chez les enfants à Bangui, République centrafricaine. Bull la Soc Pathol Exot. 2015;108(2):107-111. doi:10.1007/s13149-015-0428-3

