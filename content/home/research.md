+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Research"
subtitle = ""

# Order that this section will appear in.
weight = 20

+++
<!-- Research -->
<div class="row">
	<!-- ML -->
	<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseML" aria-expanded="false" aria-controls="collapseML">
		<h3 class="text-left">Machine Learning/Data Mining related</h3>
	</a>
	<div id="collapseML" class="collapse" role="tabpanel" aria-labelledby="headingML">
		<div class="card-block">
			<table>
				<tbody>
					<tr>
						<td><font size="4"><b> 1, Image Analysis (by Tensorflow) </b>
<br/> <b> Objective: </b> To detect the colorectal lesions like polyps and cancers, and to predict their type for diagnosis by analyzing the colonoscopy images from the databases of Digestive Endoscopic Center, Changhai Hospital. Also to compare the accuracy of different deep nets in endoscopic datasets.  <br/> <b> Methods: </b> A total number of 10000 images with more than 2000 images with lesions were expected to download from the Digestive Endoscopic Center, and labeled by experienced endoscopists. A transfer learning strategy was implemented by using the structures of several Deep Convolutional Neural Networks (DCNN) like GoogLeNet Inception V3, AlexNet or ResNet only, or using both structures and features of the DCNNs that the nets have learned from great number of datasets with non-medical images. <br/> <b> Results: </b> A preliminary experiment of 200 normal images and 200 images with lesions have showed classification accuracies of 89.56%, 87.12%, and 91.11% by GoogLeNet Inception V3, AlexNet or ResNet, respectively.
<br/> <b> [This research is ongoing now. An idea of adding other predicting factors into the net, such as patients’ ages, symptoms, and blood routine indices is under consideration.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 2, Random Forest (by R) </b>
<br/> <b> Objective: </b> To estimate the effect of influencing factors on the occurrence of adverse drug reactions by random forest algorithm. <br/> <b> Methods: </b> The muscular weakness and paraplegia caused by cytarabine in 2007 at Shanghai and some other places in China were used as an example in this research. Random forest was used to analyze the important influencing factors of this adverse drug reaction, and the results calculated by random forest were compared with the features of the cytarabine event. Thus, the feasibility of random forest algorithm in spontaneous reporting system databases can be assessed. <br/> <b> Results: </b> The muscular weakness and paraplegia were caused by two batches of impure cytarabine injections produced by a particular company, and these cytarabine injections caused the nervous disorders via intrathecal route of administration. The four important influencing factors calculated by random forest: route of administration, time to onset, season and company were all the important features of the cytarabine event. According to the results of random forest, the muscular weakness and paraplegia were more possibly related to the influencing factors compared to the other adverse reactions. So, close attention should be paid to muscular weakness and paraplegia. This result of random forest is in conformity with the real event of cytarabine as well. <br/> <b> Conclusions: </b> The random forest algorithm can identify the real important influencing factors from complex adverse drug reaction datasets and evaluate their effects on adverse reactions. It will be useful for further analyzing the features and mechanisms of adverse reactions, discriminating high risk populations, and possible route of administrations. So, random forest algorithm may be a valuable tool in practical use such as signal detection, causal relationship assessment and clinical practice guidance. <br/> <b> [This research is published as “Random Forest for Influencing Factors Analysis in Adverse Drug Reactions” in Chinese. I am the first author.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 3, Association Rules (by SAS) </b>
<br/> <b> Background: </b> The detection of signals of adverse drug events (ADEs) has increased because of the use of data mining algorithms in spontaneous reporting systems (SRSs). However, different data mining algorithms have different traits and conditions for application. The objective of our study was to explore the application of association rule (AR) mining in ADE signal detection and to compare its performance with that of other algorithms. <br/> <b> Methodology/PrincipalFindings: </b> Monte Carlo simulation was applied to generate drug-ADE reports randomly according to the characteristics of SRS datasets. Thousand simulated datasets were mined by AR and other algorithms. On average, 108,337 reports were generated by the Monte Carlo simulation. Based on the predefined criterion that 10% of the drug-ADE combinations were true signals, with RR equaling to 10, 4.9, 1.5, and 1.2, AR detected, on average, 284 suspected associations with a minimum support of 3 and a minimum lift of 1.2. The area under the receiver operating characteristic (ROC) curve of the AR was 0.788, which was equivalent to that shown for other algorithms. Additionally, AR was applied to reports submitted to the Shanghai SRS in 2009. Five hundred seventy combinations were detected using AR from 24,297 SRS reports, and they were compared with recognized ADEs identified by clinical experts and various other sources. <br/> <b> Conclusions/Significance: </b> AR appears to be an effective method for ADE signal detection, both in simulated and real SRS datasets. The limitations of this method exposed in our study, i.e., a non-uniform thresholds setting and redundant rules, require further research. <br/> <b> [This research is published as “Exploration of the association rules mining technique for the signal detection of adverse drug events in spontaneous reporting systems”. The first author of this research have shared a research team with me, and we worked together.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 4, Sequential Pattern Mining (by R) </b>
<br/> Sequential Pattern Mining can be used to detect the sequential order of events, and it is commonly used in the Behavior Pattern Analysis. This method shares similarities in many ways with association rules, while, it cares more about the order of the events rather than the associations. The “TraMineR package” of R is implemented here. The most frequent sequential order of events can be discovered, and a serials of sequential orders can be used to splice the original sequential. <br/> <b> [This research is only for fun. There’s no publications.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 5, Text Analysis (by R) </b>
<br/> <b> Objectives: </b> The high digestive disease incidence and prevalence of the population, and inadequate supply of the healthcare providers, had brought about the high workload to Chinese gastrointestinal endoscopists. A national online Gastrointestinal Endoscopy Research Platform (GERP) in mainland China was constructed at 2012. We intended to discover the pattern of endoscopists’ occupational emotions and concerns. <br/> <b> Methods: </b> In 2013, all the doctors from GERP were invited in a cross-sectional study to answer a free-answer question to describe the current focus during their work. Text mining technology was used for analysis and word segments were marked by positive, negative, or neutral. The results were illustrated by word clouds. The opinion difference between subgroups were analyzed as well. <br/> <b> Results: </b> All the 26203 endoscopists on GERP participated in this survey. A total of 18338 responses were received, with response rate of 70.0%. Among the remaining 15519 endoscopists, about 51.4% expected self-improvement and further training, 34.6% cared about their safety under nervous doctor-patient relationship, 27.2% complained about high workload without rest and 24.6% mentioned work income, also, 13.1% of participants felt stress or nervous. The percentage of negative words in all answer texts were twice as much as that of positive ones (9.7% vs 4.7%, p<0.001). The female wrote more positive words than male did (5.0% vs 4.6%, p=0.002). <br/> <b> Conclusions: </b> The emotions of Chinese endoscopists were more incline to negative. The leading concerns of Chinese endoscopists were the chance of self-improvement, the safeguard of personal safety during work, and high workload with low salary. <br/> <b> [This research is submitted to a journal, while not accepted yet. I am the first author.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 6, Gene Data Analysis (by R) </b>
<br/> <b> Objectives: </b> To improve the diagnosis of Irritable Bowel Syndrome (IBS) under the situation of lacking specific symptoms, a screening biomarker for early diagnosis of IBS is in urgent need. <br/> <b> Methods: </b> We searched the National Center of Biotechnology Information databases of expression profiling by array on GEO, for comparing gene expression profile of IBS biopsy’s and normal biopsies. A total of 183 serials of gene expression microarray data from 4 suitable platforms (“GPL570”, “GPL6480”, and “GPL96”) were used for analysis, with 97 serials in IBS group and 86 in health control group. The Bioconductor is used for analysis. <br/> <b> [This research is ongoing now.] </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b> 7, Meta-analysis (by RevMan) </b>
<br/> <b> AIM: </b> To summarize the evidence from randomized controlled trials (RCTs) regarding the effect of probiotics by using a meta-analytic approach. <br/> <b> METHODS: </b> In July 2013, we searched PubMed, EMBASE, Ovid, the Cochrane Library, and three Chinese databases (Chinese Biomedical Literature Database, Chinese Medical Current Content, and Chinese Scientific Journals database) to identify relevant RCTs. We included RCTs investigating the effect of a combination of probiotics and standard therapy (probiotics group) with standard therapy alone (control group). Risk ratios (RRs) were used to measure the effect of probiotics plus standard therapy on Helicobacter pylori ( H. pylori ) eradication rates, adverse events, and patient compliance using a random-effect model. <br/> <b> RESULTS: </b> We included data on 6997 participants from 45 RCTs, the overall eradication rates of the probiotic group and the control group were 82.31% and 72.08%, respectively. We noted that the use of probiotics plus standard therapy was associated with an increased eradication rate by per-protocol set analysis (RR = 1.11; 95%CI: 1.08-1.15; P < 0.001) or intention-totreat analysis (RR = 1.13; 95%CI: 1.10-1.16; P < 0.001). Furthermore, the incidence of adverse events was 21.44% in the probiotics group and 36.27% in the control group, and it was found that the probiotics plus standard therapy significantly reduced the risk of adverse events (RR = 0.59; 95%CI: 0.48-0.71; P < 0.001), which demonstrated a favorable effect of probiotics in reducing adverse events associated with H. pylori eradication therapy. The specific reduction in adverse events ranged from 30% to 59%, and this reduction was statistically significant. Finally, probiotics plus standard therapy had little or no effect on patient compliance (RR = 0.98; 95%CI: 0.68-1.39; P = 0.889). <br/> <b> CONCLUSION: </b> The use of probiotics plus standard therapy was associated with an increase in the H. pylori eradication rate, and a reduction in adverse events resulting from treatment in the general population. However, this therapy did not improve patient compliance. <br/> <b> [This research is published as “Probiotics in Helicobacter pylori eradication therapy: a systematic review and meta-analysis”. I am the co-first author.] </b></font></td>
					</tr>					
				</tbody>
			</table>
		</div>
	</div>
	<!-- EPI -->
	<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseEPI" aria-expanded="false" aria-controls="collapseEPI">
		<h3 class="text-left">Epidemiological investigations</h3>
	</a>
	<div id="collapseEPI" class="collapse" role="tabpanel" aria-labelledby="headingEPI">
		<div class="card-block">
			<table>
				<tbody>
					<tr>
						<td><font size="4"><b>1,</b>
<br/><b>Official Title:</b> The Survey of the Quality of Endoscopic procedures in China (2016; 2017).
<br/><b>Objective:</b> Describe the endoscopic volumes and describe a series of endoscopic quality index.
<br/><b>Enrollment:</b> 1683 (2016); 4654 (2017).
<br/><b>Study Period:</b> 2016.10-2016.12; 2017.09-2017.11.
<br/><b>My Responsibility: data management; statistical plan; statistical report</b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>2,</b>
<br/><b>Official Title:</b> A big-data clinical research of preventing, diagnosing, and treating esophageal cancer.
<br/><b>Objective:</b> Describe the demography, diagnostic status, and therapeutic status of individuals with esophageal cancer, and analyze the risk factors of esophageal cancer in China
<br/><b>Enrollment:</b> 10000
<br/><b>Study Period:</b> 2015.09-now
<br/><b>My Responsibility: participate in the study design and database design</b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>3, </b>
<br/><b>Official Title: </b> A Multi-center Prospective Big-data Clinical Observational Study of Drug Therapy for Severe Chronic Atrophic Gastritis.
<br/><b>Objective: </b> Compare the efficacy and safety of the current drugs for severe chronic atrophic gastritis
<br/><b>Enrollment: </b> 10000
<br/><b>Study Period: </b> 2015.06-now
<br/><b>My Responsibility: participate in the study design and database design </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>4, </b>
<br/><b>Official Title: </b> A National Web-based Big-data Research of Acute Pancreatitis in China.
<br/><b>Objective: </b> Describe the incidence and morbidity, diagnosis status and therapy status of individuals with acute pancreatitis in China
<br/><b>Enrollment: </b> 10000 
<br/><b>Study Period: </b> 2016.01-now
<br/><b>My Responsibility: participate in the study design and database design; statistical plan (interim analysis); statistical report (interim analysis) </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>5, </b>
<br/><b>Official Title: </b> Serological ABC method combined endoscopy screening for early gastric cancer in population with high risk of gastric cancer, a multi-center clinical research.
<br/><b>Objective: </b> Evaluate the diagnostic value of serum gastrin-17 combined with pepsinogen for early gastric cancer in population with high risk of gastric cancer
<br/><b>Enrollment: </b> 16397
<br/><b>Study Period: </b> 2015.05-2016.12
<br/><b>My Responsibility: participate in the study design; data management; statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>6, </b>
<br/><b>Official Title: </b> The Investigation of Endoscopic Technology for Diagnosis and Therapy in China.
<br/><b>Objective: </b> Describe the endoscopic technology volumes, demography of endoscopists, numbers of endoscopic facilities, and the view of endoscopists about their job
<br/><b>Enrollment: </b> 6128 hospitals (26203 endoscopists)
<br/><b>Study Period: </b> 2012.10-2015.06
<br/><b>My Responsibility: participate in the study design; data management; statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>7, </b>
<br/><b>Official Title: </b> The Study of Colonoscopy Screening for Colorectal Cancer in Individuals without Specific Symptoms at Yixing, Jiangsu Province.
<br/><b>Objective: </b> Describe the demography of subjects, analyze the risk factors of colorectal polyp and colorectal cancer.
<br/><b>Enrollment: </b> 935
<br/><b>Study Period: </b> 2012.10-2013.04
<br/><b>My Responsibility: statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>8, </b>
<br/><b>Official Title: </b> The Survey of the Outpatient Service in Changhai Hospital.
<br/><b>Objective: </b> Describe satisfaction rate and analyze the influence factors of satisfaction
<br/><b>Enrollment: </b> 1297
<br/><b>Study Period: </b> ?-2013.02
<br/><b>My Responsibility: part of the statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>9, </b>
<br/><b>Official Title: </b> The Investigation of the Diagnosis and Therapy of Chronic Gastritis in China.
<br/><b>Objective: </b> Describe the morbidity, diagnosis status and therapy status of the population
<br/><b>Enrollment: </b> 8907
<br/><b>Study Period: </b>?-2012.12
<br/><b>My Responsibility: statistical plan; statistical report </b></font></td>
					</tr>
					
					<tr>
						<td><font size="4"><b>10, </b>
<br/><b>Official Title: </b> The Epidemiological survey of Subjects with Leukoderma in the Target Population.
<br/><b>Objective: </b> Describe the morbidity, current skin lesions, diagnosis and therapy of the population
<br/><b>Enrollment: </b> 5953
<br/><b>Study Period: </b> ?-2012.06
<br/><b>My Responsibility: statistical plan; statistical report</b></font></td>
					</tr>					
				</tbody>
			</table>
		</div>
	</div>
	<!-- CT -->
	<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseCT" aria-expanded="false" aria-controls="collapseCT">
		<h3 class="text-left">Clinical Trials</h3>
	</a>
	<div id="collapseCT" class="collapse" role="tabpanel" aria-labelledby="headingCT">
		<div class="card-block">
			<table>
				<tbody>
					<tr>
						<td><font size="4"><b>1, </b>
<br/><b>Official Title: </b> A Worldwide Multi-center, Randomized, Double-blind, Self-controlled Study of Comparing Endoscopic Technology of Flexible Spectral Imaging Color Enhancement (FICE) with that of White Light in Screening Early Gastric Cancer.
<br/><b>Enrollment: </b> 409
<br/><b>Study Period: </b> 2015.04-now
<br/><b>My Responsibility: participate in the study design; statistical plan </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>2, </b>
<br/><b>Official Title: </b> A Multi-center, Randomized, Controlled Study of Comparing Endoscopic Technology of Linked Color Imaging (LCI) with that of White Light in Screening Early Gastric Cancer. 
<br/><b>Enrollment: </b> 2800
<br/><b>Study Period: </b> 2017.05-now
<br/><b>My Responsibility: participate in the study design</b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>3, </b>
<br/><b>Official Title: </b> A Multi-center, Randomized, Parallel-controlled Study of the Combination of Total Glucosides of White Paeony Capsules (the extract of a Chinese medicine) and Prednisone for Subjects with Oral Lichen Planus.
<br/><b>Enrollment: </b> 566
<br/><b>Study Period: </b> 2016.08-now
<br/><b>My Responsibility: participate in the study design </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>4, </b>
<br/><b>Official Title: </b> A Multi-center, Randomized, Double-blind, Placebo Parallel-controlled Study of the “Gan hai wei kang” Capsules (a Chinese medicine) for Subjects with Chronic Gastritis and Functional Dyspepsia.
<br/><b>Enrollment: </b> 286
<br/><b>Study Period: </b> 2017.06-now
<br/><b>My Responsibility: participate in the study design </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>5, </b>
<br/><b>Official Title: </b> Study Comparing Esomeprazole Sodium for Injection (Nexium) 40mg Daily Versus Esomeprazole Sodium for Injection (Aisuping, a Chinese brand) 40mg Daily as Gastric Acid Inhibitor in Health Volunteers.
<br/><b>Enrollment: </b> 20
<br/><b>Study Period: </b> 2016.10-2017.09
<br/><b>My Responsibility: statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>6, </b>
<br/><b>Official Title: </b> A single center and non-inferiority clinical study program for the Decrustation ointment treatment of deep II degree burn with random, single blind and blind evaluation, positive drug self-control.
<br/><b>Enrollment: </b> 44
<br/><b>Study Period: </b> 2015.01-2016.08
<br/><b>My Responsibility: participate in the study design; data management; statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>7, </b>
<br/><b>Official Title: </b> A Prospective, Randomized, Double-blind, Double-dummy, Sucralfate Controlled, Multicenter Study to Evaluate the Efficacy of Teprenone On Chinese Patients With Chronic Non-Atrophic Erosive Gastritis.
<br/><b>Enrollment: </b> 332
<br/><b>Study Period: </b> 2011.02-2014.06
<br/><b>My Responsibility: data management; statistical plan; statistical report</b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>8, </b>
<br/><b>Official Title: </b> A Multi-center, Randomized, Double-blind, Placebo Parallel-controlled Study of “Hou pu pai qi he ji” (a Chinese medicine) for Subjects with Dyspepsia and Abdominal Distention.
<br/><b>Enrollment: </b> 172
<br/><b>Study Period: </b> 2013.06-2014.12
<br/><b>My Responsibility: participate in the study design; data management; statistical plan; statistical report </b></font></td>
					</tr>

					<tr>
						<td><font size="4"><b>9, </b>
<br/><b>Official Title: </b> Study of Multi-wavelength Laser Unit for Subjects with Urological Calculi.
<br/><b>Enrollment: </b> 144
<br/><b>Study Period: </b> 2010.05-2012.09
<br/><b>My Responsibility: statistical plan; statistical report</b></font></td>
					</tr>
					
					<tr>
						<td><font size="4"><b>10, </b>
<br/><b>Official Title: </b> A Multi-center, Randomized, Controlled, Open Label Study of Stilamin for Prevention of Post-ERCP Pancreatitis.
<br/><b>Enrollment: </b> 908
<br/><b>Study Period: </b> ?-2013.09
<br/><b>My Responsibility: part of the statistical report</b></font></td>
					</tr>					
				</tbody>
			</table>
		</div>
	</div>
</div>

