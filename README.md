# Group_1_Tala
FDA Final Project Key Insights

Designed a loan-default prediction engine on 307,000+ historical loan data augmented and 41 conventional borrower features. Enhanced the dataset by dropping irrelevant features and replaced with 16 innovative mobile-based proxy features, including a 'device-score index' based on smartphone and real estate ownership flags - an indicator of higher income and lower default propensity. Because the raw inputs already live in a bank’s customer records, the solution is packaged as a drop-in API that instantly widens credit access for thin-file borrowers.

After exhaustive hyper-parameter tuning across multiple algorithms, XGBoost delivered the strongest performance, identifying fraud recall rate to 25.7 %, and achieved an F1 score of 81.99%, preserving interest income by approving creditworthy applicants. Device-score index and a mobility score as the most predictive signals, providing lenders with transparent, data-driven confidence in every credit decision.
