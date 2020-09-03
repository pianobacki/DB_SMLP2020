readme

DataImageSac.rda
DataImageFix.rda

Data from scene viewing experiment. 
participants viewed 60 images under 4 different conditions. 2x2 design

2 body conditions: sitting with the head fixed by a chin rest; standing 
2 task conditions: free viewing task; guess time the image was taken

DataImageSac.rda: sacadic events during  image presentation
DataImageFix.rda: fixational events during image presentation 

important columns 

VP	subject number
trial	trial number
Img	image number
fcx	 fixation cross x-coordinate
fcy	fixation cross y-coordinate
quest	 factor task 0-FreeViewing 4-GuessTime
sample	sample number of this trial
SacAmpl	saccade amplitude in degree
SacPeak	peak velocity of saccade
fd fixation duration in ms
FixXPosMed	median position of fixation x
FixYPosMed	median position of fixation y
FixXPosMean	mean position of fixation x
FixYPosMean	mean position of fixation y
nthfix	ordinal number of fixation in this trial
revnthfix	reverse ordinal number of fixation in this trial
body	factor body gesture 1-stittingchinrest 2-standing
filterout	events which are filtered by multiple parameters
cond	combinations of factors 1-FV_Sitting 2-FV_Standing 3-Guesstime_Sitting 4-GuessTime_Standing