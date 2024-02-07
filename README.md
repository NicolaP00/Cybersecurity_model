For the cybersecurity exam, we chose to focus on the topic of ML techniques for Intrusion Detection Systems, leveraging the capabilities of ML algorithms to detect malicious anomalies by analyzing data behavior. After documenting and explaining the problem, existing algorithms, and their respective pros and cons, we opted to test several common ML models to compare their performance. We selected the NSL-KDD dataset, an updated version of one of the most widely used IDS datasets, KDDCup99. Our objective is to build and train multiple ML models capable of distinguishing between normal behavior and anomalies. Intrusions are categorized as DoS, Probe, U2R, or R2L. Recognizing the 'no free lunch' theorem, we acknowledge that each ML model has its limitations. Consequently, by the end of the study, we test a hybrid ensemble combining various ML models.

## Files

This repo contains a notebook called Cyber.ipynb, in which all the code is written, and two txt files KDDTrain+ and KDDTest (the used datasets)
