# EuroPythonChallenge2016
This is the repo that contains the databases for the Europython Challenge 2016 proposed by Plethora

Machine Tool Mining Challenge

Data description:

This dataset comprises real world machine data gathered from a machine tool working unload in an empty cycle. There is no material removal taking place, but the control instructions are sent to the controller to move each of the 3 axis servo-drive. From each servo-drive, RPM, power and temperature is taken. 
Additionally, vibration is measured from each servo-drive where 5 fundamental amplitudes (acceleration) [axis::x-amp#) are measured at their corresponding frequency [axis::x-freq#].

•	The dataset contains a collection of CSV files. 
•	There are three folders comprised: rpm_and_power, temperature and vibration
•	Every folder contains data gathered during 5 days.
•	Data was captured in real-time and synchronization of timestamps is not assured as different sensors were used.
•	Alignment of data and possible errors in capturing are reflected in the datasets as no filtering was used in the generation of the datasets.
•	Datasets are to be considered as raw as they possibly can be.
•	Data healing, handling, mining alignment or visualization are a few of the ideas that potential contestants could focus in solving for participating in the contest.

Requirements and conditions

1.	The data set can be cloned from GitHub: https://github.com/PlethoraEG/EuroPythonChallenge2016
2.	By downloading the data set, you agree to use it for research purposes, no commercial use is granted.
3.	You can use the data set for any future research work, however is mandatory to cite the source as follows:
Disclosure and research use: The machine tool dataset used is property of Ikergune and its use is granted for research only, it can be obtained from: https://github.com/PlethoraEG/EuroPythonChallenge2016
4.	All code must be pure Python; partially developed solutions using other programming languages will not be taken into consideration.
5.	A minimum of one and maximum of three scripts (not including dependences) are to be delivered by the participants in a zip file to the following email address: machinetool.challenge@ikergune.com
6.	Deadline is 31st of October 2016, midnight (CET)
7.	You can use any open SDK or well-known library, e.g. Scikit learn, etc., or you can chose to use your own, in such case you must provide it in order to run the script, if your script is not runnable, your contribution will not be taken into account.
8.	By sending your contribution to the challenge you explicitly grant Ikergune any exploitation rights of your work (if applicable). 

Prizes
Ikergune will select an international board of evaluators whose identities will remain in secret. The jurors will choose between the submissions one winner and a second and third place that will receive the following prizes:

Winner:  Macbook Air 11” 
Second prize: Ipad mini 
Third prize: Paid subscription to Europython 2017, only the attendance will be covered (no plane tickets, or hotel)

•	The evaluation board decision will be final.
•	There will be a minimum of 30 valid submissions for the challenge to be considered open, bellow that mark the organizers will declare the challenge deserted and hence no prizes will be given. 
•	The winners will be contacted by the organization the 1St of December of 2016 and their names will be announced by the EuroPython organization through their social networks.

Challenge goal
The contestants are invited to participate with their scripts with their own original ideas. The organizers will provide the datasets with the intention of evaluating creativity, usefulness and good coding practices.

Data mining over the datasets, visualization and visual analytics, time series synchronization of the data sets, etc. are just few of the ideas for developments that contestants are invited to participate with.

