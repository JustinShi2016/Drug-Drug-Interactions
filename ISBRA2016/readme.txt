The codes are used to produce the model proposed in ISBRA 2016 and its extension submitted to BMC Bioinformatics.
Jia-Xin Li, Jian-Yu Shi* et al. Predicting Combinative Drug Pairs via Integrating Heterogeneous Features for Both Known and New Drugs. Lecture Notes in Bioinformatics, 9683, pp. 297¨C298, 2016 

BMC Bioinformatics
TTILE: Predicting Combinative Drug Pairs towards Realistic Screening via Integrating Heterogeneous Features
AUTHORS: Jian-Yu Shi, Li Jia-Xin, Ke Gao, Peng Lei and Siu-Ming Yiu

DrugNames.txt	-- 245 Drug names coded by STITCH
DrugPairIndex_original.txt	-- the 239 pairwise ids of drug Combinations
DrugHavingAttributes.mat	-- the matlab data contains the following variables

  Name                            Size  

  ATC_Profile                   245x14		ATC features
  DDI_Interact                  245x245		DDI 
  DDI_Profile                   245x922		DDI extra 
  DTI_Profile                   245x357		Target features 
  DrugPairIndexRearranged      2530x2 		the first 239 rows denote the positive samples (drug combinations)  
  FeatureMat_SE                2530x7888	Side effect features
  LabelOfPair                  2530x1		the labels of samples   
  PCA_SE                       2530x234		Side effect features handled by PCA 