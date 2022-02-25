# COMPARISON-OF-TEMPORAL-SEGMENT-NETWORK-METHOD-AND-SLOWFAST-METHOD-FOR-VIDEO-ACTION-RECOGNITION.
Human activity recognition has gained a lot of importance in recent years due to its application in various areas such as Surveillance, Health, Security, etc. In this project, I will address the action recognition classification using the Temporal Segment Network method and Slow fast method and compare their performance on the test videos. In the TSN Method we use the segment-based sampling of a single video and in the end, we do the aggregation of segments and In the SlowFast Method we use slow pathway and fast pathway to extract the spatial semantics, temporal information respectively. In this project I will be using the UCF101-24 dataset for training and testing both the models. The implementation of the method had been done using the mmaction2.
Method	 Top1 acc	Top5 acc	Class acc
TSN(RBG)	88.13	  97.47	      88.06
slowfast	75.82	  92.47	     75.50

