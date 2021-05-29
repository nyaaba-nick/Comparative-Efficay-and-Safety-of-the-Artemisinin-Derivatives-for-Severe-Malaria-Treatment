# Comparative-Efficacy-and-Safety-of-the-Artemisinin-Derivatives-for-Severe-Malaria-Treatment
Introduction

This data was produced for a systematic review update and NMA was conducted according to the PRISMA guidelines extension.(1) The NMA protocol was registered with PROSPERO registration number CRD42020218190.(2) 

Search

We included all published and unpublished RCTs from three Cochrane systematic reviews that compared artemisinin derivatives to quinine in treating severe malaria.(3–5) In addition, we combined the search strategies of these previous reviews and updated them by searching the Cochrane Infectious Diseases Group Specialized Register; Cochrane Central Register of Controlled Trials (CENTRAL) in the Cochrane Library; MEDLINE, Embase, LILACS, ISI Web of Science, and trial registers from inception up to February 2021. There were no limitations regarding language, geographical setting and year of publication.

Method of Collection
Screening the title and abstract, and full-text for eligible studies were completed in duplicate using Rayyan review software(6) by the reviewing team independently, blinded to each other. Disagreements were resolved by the other co-reviewers.

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

Mortality, neurological sequela, and adverse events were assessed as binary outcomes whilst the rest as continuous outcomes.The data were extracted using a structured data form into an MS Excel workbook independently by NEA, GA, DSYA, MA and NN. 
This was designed and reviewed by NN, JOM and JH. Name of first author, year of publication, sample size, length of follow up, age group, summary estimate of age and geographical location was recorded for every study. Intervention specific data collected included name of intervention, dose, route of administration, sample size randomised to group and summary age provided. This same information was collected for comparator(s).
For binary outcomes, the number of participants experiencing the event and the number assessed in each intervention group was recorded. For continuous outcomes, arithmetic means and standard deviations for each intervention group, with the numbers assessed in each group were extracted. If the number assessed in each group was not reported, the number randomised in the intervention arm was used. 
Where medians and range or interquartile range were reported instead of the means and standard deviations, they were extracted and the arithmetic means and standard deviations were estimated from the medians and range or interquartile range respectively.(7) These estimations were used for the main analysis and later excluded for sensitivity analyses.

Statistical Analyses

Separate analyses were conducted for adults and children to reduce clinical inconsistency and heterogeneity. NMAs were conducted using a random effect model in a frequentist framework using R (version 3.6.0) netmeta package (version 1.2-1).(8) Summary Risk Ratios (RR) for binary outcomes and Mean Differences (MD) for continuous outcomes with 95% confidence intervals (95%CI) were estimated for quinine and the artemisinin derivatives, against each other for all outcomes including hypoglycaemia.(9) Network graphs were created with Stata 15 network map.(10) League tables and forest plots were used to summarise effect sizes for all possible comparisons, outcomes and subgroups.(8) Variability in the effects sizes was assessed globally for the whole network and locally at each possible study design, and it was described with Q and I2 statistics, degrees of freedom, and p-values. Variability in the effect sizes was further decomposed into within-design (heterogeneity) and between-design (inconsistency). Hotspots of inconsistency were identified with net-splitting and net heat plots.(11,12) Probability scores (p-scores) were used to rank treatments for each outcome.(13) Data from adults and children were combined to conduct subgroup analyses by severe malaria type, study continent, and time point of neurological sequela events. We used Eggers test and a comparison-adjusted funnel plot that incorporates all the effects of bias in a network to assess publication bias.(8) All statistical tests were two-sided with a significance level of 0.05.


Full Bibliography with study references

1. 	Hutton B, Salanti G, Caldwell DM, Chaimani A, Schmid CH, Cameron C, et al. The PRISMA extension statement for reporting of systematic reviews incorporating network meta-analyses of health care interventions : Checklist and explanations. Ann Intern Med. 2015;162(11):777–84. 
2. 	Nyaaba N, Ordonez-Mena J, Hirst J. What are the comparative efficacy and safety of the artemisinin derivatives for treating severe malaria? [Internet]. PROSPERO- International prospective register of systematic reviews; 2020. Available from: https://www.crd.york.ac.uk/prospero/display_record.php?ID=CRD42020218190
3. 	Sinclair D, Donegan S, Lalloo DG. Artesunate versus quinine for treating severe malaria ( Review ) SUMMARY OF FINDINGS FOR THE MAIN COMPARISON. Heal (San Fr. 2011;(4). 
4. 	Esu EB, Effa EE, Opie ON, Meremikwu MM. Artemether for severe malaria. Cochrane Database Syst Rev. 2019;2019(6). 
5. 	Afolabi BB, Okoromah CA. Intramuscular arteether for treating severe malaria. Cochrane Database Syst Rev. 2004;(4). 
6. 	Ouzzani M, Hammady H, Fedorowicz Z, Elmagarmid A. Rayyan-a web and mobile app for systematic reviews. Syst Rev. 2016;5(210). 
7. 	Wan X, Wang W, Liu J, Tong T. Estimating the sample mean and standard deviation from the sample size, median, range and/or interquartile range. BMC Med Res Methodol. 2014;14(1):1–13. 
8. 	Rücker G, Krahn U, König J, Efthimiou O, Schwarzer G. netmeta: Network Meta-Analysis using Frequentist Methods [Internet]. R package; 2020. Available from: https://cran.r-project.org/package=netmeta
9. 	Jackson D, White I, Riley R. Quantifying the impact of between-study heterogeneity in multivariate meta-analyses. Stat Med. 2012;31:3805–20. 
10. 	White I. Network meta-analysis. Stata J. 2015;15:951–85. 
11. 	Chaimani A, Salanti G. Visualizing assumptions and results in network meta-analysis : The network graphs package. 2015;(4):905–50. 
12. 	Donegan S, Dias S, Welton NJ. Assessing the consistency assumptions underlying network meta-regression using aggregate data. Res Synth Methods [Internet]. 2019;10(2):207–24. Available from: http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=medc&NEWS=N&AN=30367548
13. 	Rücker G, Schwarzer G. Ranking treatments in frequentist network meta-analysis works without resampling methods. BMC Med Res Methodol [Internet]. 2015;1–9. Available from: http://dx.doi.org/10.1186/s12874-015-0060-8
14. 	Anh T, Kim N, Bich N, Huong N n., Phuong N., Al. E. Randomized comparative study of artesunate intravenously and quinine in loading dose IV on severe and complicated malaria. Vietnam; 1989. 
15. 	K. W, M. T. Comparison of combinations of parenteral artemisinin derivatives plus oral mefloquine with intravenous quinine plus oral tetracycline for treating cerebral malaria. Bull World Health Organ [Internet]. 1992;70(6):777–82. Available from: http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=emed4&NEWS=N&AN=23032583
16. 	Karbwang J, Sukontason K, Rimchala W, Mansiripongpun W, Tin T, Auprayoon P, et al. Preliminary report: A comparative clinical trial of arthemeter and quinine in severe falciparum malaria. Southeast Asian J Trop Med Public Health. 1992;23(4):768–72. 
17. 	Hien TT, Arnold K, Vinh H, Cuongl BM, Nguyen HP, Chau HTT, et al. Comparison of artemisinin suppositories with intravenous artesunate and intravenous quinine in he treatment of cerebral malaria. Trans R Soc Trop Med Hyg. 1992;582–3. 
18. 	Walker O, Salako L, Sowunmi A, Omokhodion S. An open randomized comparative study of intramuscular artemether and intravenous quinine in cerebral malaria in children. Trans R Soc Trop Med Hyg. 1993;87(5):564–6. 
19. 	Anh T, Binh T, Kim N, Al. E. Comparative study of intravenous artesunate followed by oral meﬂoquine versus intravenous quinine in the treatment of severe and complicated malaria in Viet Nam. 1995. 
20. 	Karbwang J, Tin T, Rimchala W, Sukontason K, Namsiripongpun V, Thanavibul A, et al. Comparison of artemether and quinine in the treatment of severe falciparum malaria in south-east Thailand. Trans R Soc Trop Med Hyg. 1995;89(6):668–71. 
21. 	Hien TT, Day NPJ, Phu NH, Mai NTH, Chau TTH, Loc PP, et al. A controlled trial of artemether or quinine in Vietnamese adults with severe falciparum malaria. N Engl J Med. 1996;335(2):76–83. 
22. 	Hensbroek MB Van, Onyiorah E, Jaffar S, Schneider G, Kwiatowski D. A trial of artemether or quinine in children with cerebral malaria. N Engl J Med. 1996;335:69–75. 
23. 	Murphy S, English M, Waruiru C, Mwangi I, Amukoye E, Crawley J, et al. An open randomized trial of artemether versus quinine in the treatment of cerebral malaria in African children. Trans R Soc Trop Med Hyg. 1996;90(3):298–301. 
24. 	Vinh H, Huong NN, Ha TTB, Cuong BM, Phu NH, Chau TTH, et al. Severe and complicated malaria treated with artemisinin, artesunate or artemether in Viet Nam. Trans R Soc Trop Med Hyg. 1997;91(4):465–7. 
25. 	Phuong CXT, Bethell DB, Phuong PT, Mai TTT, Thuy TTN, Ha NTT, et al. Comparison of artemisinin suppositories, intramuscular artesunate and intravenous quinine for the treatment of severe childhood malaria. Trans R Soc Trop Med Hyg. 1997;91(3):335–42. 
26. 	Seaton RA, Trevett AJ, Wembri JP, Nwokolo N, Naraqi S, Black J, et al. Randomized comparison of intramuscular artemether and intravenous quinine in adult, Melanesian patients with severe or complicated, plasmodium falciparum malaria in Papua New Guinea. Ann Trop Med Parasitol. 1998;92(2):133–9. 
27. 	Taylor TE, Wills BA, Courval JM, Molyneux ME. Intramuscular artemether vs intravenous quinine: An open, randomized trial in Malawian children with cerebral malaria. Trop Med Int Heal. 1998;3(1):3–8. 
28. 	Ojuawo A, Adegboye A, Oyewalo O. Clinical response and parasite clearance in childhood cerebral malaria: A comparison between intramuscular artemether and intravenous quinine. East Afr Med J. 1998;75:450–2. 
29. 	Olumese PE, Björkman A, Gbadegesin RA, Adeyemo AA, Walker O. Comparative efficacy of intramuscular artemether and intravenous quinine in Nigerian children with cerebral malaria. Acta Trop. 1999;73(3):231–6. 
30. 	Thuma PE, Bhat GJ, Mabeza GF, Osborne C, Biemba G, Shakankale GM, et al. A randomized controlled trial of artemotil (β-arteether) in Zambian children with cerebral malaria. Am J Trop Med Hyg. 2000;62(4):524–9. 
31. 	Moyou-Somo R, Tietche F, Ondoa M, Kouemeni LE, Ekoe T, Mbonda E, et al. Clinical trial of β-arteether versus quinine for the treatment of cerebral malaria in children in Yaounde, Cameroon. Am J Trop Med Hyg. 2001;64(5):229–32. 
32. 	Adam I, Idris H, Mohamed-Ali A, Aelbasit I, Elbashir M. Comparison of intramuscular artemether and intravenous quinine in the treatment of Sudanese children with severe falciparum malaria. East Afr Med J. 2002;79(12):621–5. 
33. 	Satti G, Elhassan S, Ibrahim S. The efficacy of artemether versus quinine in the treatment of cerebral malaria. J Egypt Soc Parasitol. 2002;32(2):611–23. 
34. 	Newton PN, Angus BJ, Chierakul W, Dondorp A, Ruangveerayuth R, Silamut K, et al. Randomized Comparison of Artesunate and Quinine in the Treatment of Severe Falciparum Malaria. Clin Infect Dis. 2003;37(1):7–16. 
35. 	Huda SN, Shahab T, Ali SM, Afzal K, Khan HM. A Comparative Clinical Trial of Artemether and Quinine in Children with Severe Malaria. Indian Pediatr. 2003;40(10):939–45. 
36. 	Mohanty AK, Rath BK, Mohanty R, Samal AK, Mishra K. Randomized control trial of quinine and artesunate in complicated malaria. Indian J Pediatr [Internet]. 2004;71(4):291–5. Available from: http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=med5&NEWS=N&AN=15107507
37. 	Minta D, Sissoko M, Sidibe I, Dolo A, Poudiougou B, Dembele M, et al. Efficacy and safety of artemether in the treatment of severe end complicated malaria in mali. Mali Med. 2005;20(1–2):28–32. 
38. 	Dondorp A, Nosten F, Stepniewska K, Day N, White N; SEAQAMT (SEAQUAMAT) group. Artesunate versus quinine for treatment of severe falciparum malaria: a randomised trial. Lancet. 2005;366(9487):717–25. 
39. 	Haroon N, Amichandwala K, Solu MG. Comparative efficacy of quinine and artesunate in the treatment of severe malaria: a randomized controlled trial. JK Sci [Internet]. 2005;7(1 CC-Infectious Diseases):32‐35. Available from: https://www.cochranelibrary.com/central/doi/10.1002/central/CN-00569384/full
40. 	Aguwa CN, Ukwe C V., Adibe MO. A comparative study of quinine and artemether in the treatment of severe malaria in Nigerian children. Trop J Pharm Res. 2010;9(1):11–7. 
41. 	Phu NH, Tuan PQ, Day N, Mai NTH, Chau TTH, Chuong L V., et al. Randomized controlled trial of artesunate or artemether in Vietnamese adults with severe falciparum malaria. Malar J. 2010;9:97. 
42. 	Dondorp AM, Fanello CI, Hendriksen IC, Gomes E, Seni A, Chhaganlal KD, et al. Artesunate versus quinine in the treatment of severe falciparum malaria in African children (AQUAMAT): An open-label, randomised trial. Lancet [Internet]. 2010;376(9753):1647–57. Available from: http://dx.doi.org/10.1016/S0140-6736(10)61924-1
43. 	Eltahir HG, Omer AA, Mohamed AA, Adam I. Comparison of artesunate and quinine in the treatment of Sudanese children with severe Plasmodium falciparum malaria. Trans R Soc Trop Med Hyg [Internet]. 2010;104(10):684–6. Available from: http://dx.doi.org/10.1016/j.trstmh.2010.05.009
44. 	Osonuga O, Osonuga A, Osonuga I, Osonuga A. Comparison of Coma Resolution Time in the Course of Treating Childrenwith Severe Falciparum Malaria with Quinine and Artemether. World J Med Sci. 2011;2(1):42–5. 
45. 	Osonuga O, Osonuga I. Parasitaemia changes in the course of treatment of severe malaria patients with artemether and quinine (A preliminary study). Maced J Med Sci. 2009;2(4):319–23. 
46. 	Osonuga O, Osonuga A, Osonuga I, Osonuga A. Temperature changes in the course of treatment of severe malaria patients with artemether and quinine. Asian J Med Sci. 2011;6(2):42–5. 
47. 	Abdallah TM, Elmardi KA, Elhassan AH, Omer MB, Elhag MS, Desogi MA, et al. Comparison of artesunate and quinine in the treatment of severe Plasmodium falciparum malaria at Kassala hospital, Sudan. J Infect Dev Ctries [Internet]. 2014;8(5):611–5. Available from: http://ovidsp.ovid.com/ovidweb.cgi?T=JS&PAGE=reference&D=med11&NEWS=N&AN=24820465
48. 	Bobossi-Serengbe G, Gody JC, Fioboy R, Elowa JB, Manirakiza A. Comparaison de l’efficacité de l’artémether et de la quinine dans le traitement du paludisme grave chez les enfants à Bangui, République centrafricaine. Bull la Soc Pathol Exot. 2015;108(2):107–11. 


