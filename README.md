# HSBC_Hackathon

HSBC - MAYWEEK HACKATHON - DETAILS
1. Background
The electronic Non-Deliverable Forwards market has grown over the past 2 years on EBS, the primary market for FX. Electronic liquidity traded inter-bank has gradually increased. Recently, the platform has opened to non-bank market partic- ipants. As a result, understanding the NDF price formation process in the presence of high frequency participants has become increasingly important as a Tier1 bank market-maker operating in the electronic market.
2. Rules
We consider the Indian rupee traded against the US dollar. The file prices raw.csv contains 231154 market snapshots. Each update contains three ask prices at which market participants are willing to sell and three bid prices at which market par- ticipants are willing to buy. The mid price is the average of the first bid and ask prices, mid = (bid + ask)/2. Fundamental to understanding the mircostructure of this market is modeling the point process associated to the mid. Your challenge is to answer,
The next time the mid price moves will it go up or down?
You should use data from the period before 2017.09.27 to train your best model. Then report the prediction accuracy over the days 2017.09.27, 2017.09.28, 2017.09.29. A reasonable amount of preprocessing is permitted on the data set as seen in the notebook. The out of sample set should contain at least 40000 sample points.
