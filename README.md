# Rashomon
This repository hosts information related to a sculpture exhibit, called Rashomon by Chuck Ginnever, in the courtyard of the Food Sciences building at ISU. 

There are 15 identical sculptures, and the rule is that they need to be oriented in 15 different positions, resting on different surfaces. 

Based on the sketch, these are the current configurations:

1. BC, NU
2. DE, K
3. AF, FM
4. HJS, LT
5. FM, FH, MO
6. MOPU
7. CDQP, U
8. KLS, D
9. ABCDE
10. AE, IK
11. DPTLS
12. HIJ, KS
13. PTO, H
14. A, MNU
15. AF, HI, FH

Each week two of the sculptures will be rotated into each others configuration. We will photo the sculptures each week, and at the end of the exhibit, the images will be combined into a video. 

Weekly rearrangements:

- Week 1: 1 <--> 9
- Week 2: 8 <--> 14
- Week 3: 4 <--> 5
- Week 4: 7 <--> 15
- Week 5: 2 <--> 13
- Week 6: 6 <--> 11
- Week 7: 3 <--> 10
- Week 8: 6 (now ED, K) <--> 12 (now DP, TL)
- Week 9: 2 <--> 8
- Week 10: 9 <--> 12
- Week 11 (June 11): 3 <--> 4
- Week 12 (june 17) 13 <--> 14
- Week 13 (june 24) 5 <--> 7
- Week 14 (July 1) 1 <--> 6
- Week 15 (July 9) 10 <--> 11
- Week 16 (July 16) 7 (4) <--> 13 (8)
- Week 17 (July 23) 14 <--> 15
- 
The sketch (sketch.jpg) was made to get a virtual representation of the sculptures, so that we could experiment with configurations. 

We also measured the distances from some of the vertices to others, and estimated the remaining vertex to vertex distance. These are in the file distances-new.csv. The goal with this file is to use multidimensional scaling to automatically reconstruct the shapes. So far, not a complete success. The current best rendering is stored in mds3.xml. The two .moc files show movies of the current configuration. The file heatmap.png is a representation of the inter-vertex distances, which we have used to get better estimates of some of the distances. 

Final configurations

1. BC, NU
2. DE, K
3. AF, FM
4. HJS, LT
5. FM, FH, MO
6. MOPU
7. CDQP, U
8. KLS, D
9. ABCDE
10. AE, IK
11. DP, PT, TL, LS
12. HIJKS
13. PTO, H
14. A, MNU
15. AF, HI, FH
