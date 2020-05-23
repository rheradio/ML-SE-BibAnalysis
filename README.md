# Machine Learning for Software Engineering: a Bibliometric Analysis from 2015 to 2019

Material of the paper:

*Ruben Heradio, David Fernandez-Amoros, Cristina Cerrada, and Manuel J. Cobo*. Machine Learning for Software Engineering: a Bibliometric Analysis from 2015 to 2019. *54th Hawaii International Conference on System Sciences (HICSS), Kauai, Hawaii, US, 2021.*

It includes:
* Data, in [.bib](https://github.com/rheradio/Machine-Learning-for-Software-Engineering-a-Bibliometric-Analysis-from-2015-to-2019/blob/master/scopus_data/ml_se.bib) and [.ris](https://github.com/rheradio/Machine-Learning-for-Software-Engineering-a-Bibliometric-Analysis-from-2015-to-2019/blob/master/scopus_data/ml_se.ris) formats, gathered from Elsevier Scopus by running the following query:
```
TITLE-ABS-KEY("Machine Learning" OR (supervised W/0 learning) 
OR (unsupervised W/0 learning) OR (Support W/0 Vector W/0 
Machine) OR (Latent W/0 Dirichlet W/0 Allocation) OR (Deep W/0 
Learning) OR (Neural W/0 Network) OR (k W/0 nearest W/0 
neighbors) OR (naive W/0 bayes) OR (decision W/0 trees) ) 
AND SRCTITLE("Agile Conf*" OR "Aspect-Oriented Softw* 
Development" OR "Asia-Pacific Softw* Engineer* Conf*" OR 
"IEEE/ACM Int* Conf* on Automated Softw* Engineer*" OR 
"Component-Based Softw* Engineer*" OR "European Conf* on Softw* 
Maintenance and ReEngineer*" OR "Int* Conf* on Evaluation and 
Assessment in Softw* Engineer*" OR "European Conf* on 
Object-Oriented Programming" OR "European Conf* on Softw* 
Architecture" OR "ACM Sigsoft Conf* on the Foundations of 
Softw* Engineer*" OR "Int* Symposium on Empirical Softw* 
Engineer* and Measurement" OR "Int* Conf* on Generative 
Programming and Component Engineer*" OR "IEEE Int* Conf* on 
Engineer* of Complex Computer Systems" OR "Int* Conf* on 
Formal Engineer* Methods" OR "Int* Conf* on Softw* Engineer*" 
OR "IEEE Int* Conf* on Softw* Maintenance" OR "IEEE Int* Conf* 
on Softw* Reuse" OR "Int* Conf* on Softw* Testing, Verification 
and Validation" OR "Int* Symposium on Empirical Softw* 
Engineer*" OR "Int* Symposium on Softw* Reliability Engineer*" 
OR "Int* Symposium on Softw* Testing and Analysis" OR "Int* 
Workshop on Principles of Softw* Evolution" OR "ACM/IEEE Int* 
Conf* on Model-Driven Engineer* Languages and Systems" OR 
"IEEE Int* Working Conf* on Mining Softw* Repositories" OR 
"ACM Conf* On Object Oriented Programming Systems Languages 
and Applications" OR "Int* Conf* on Quantitative Evaluation 
of Systems" OR "Int* Conf* on Quality Softw*" OR "IEEE Int* 
Requirements Engineer* Conf*" OR "Int* Workshop on 
Requirements Engineer*: Foundation for Softw* Quality" OR 
"Simposio Brasileiro de Engenharia de Softw*" OR "Euromicro 
Conf* on Softw* Engineer* and Advanced Applications" OR "Int* 
Symposium on Softw* Engineer* for Adaptive and Self-Managing 
Systems" OR "IEEE Int* Conf* on Softw* Engineer* and formal 
Methods" OR "Int* Conf* on Softw* Engineer* and Knowledge 
Engineer*" OR "Softw* Visualization" OR "Softw* Product Line 
Conf*" OR "ACM Sigsoft Working Conf* on Softw* Reusability" OR 
"Technology of Object-Oriented Languages and Systems" OR "IEEE 
Working Conf* on Reverse Engineer*" OR "Working IEEE/IFIP Conf* 
on Softw* Architecture" OR "ACM Transactions on Programming 
Languages and Systems" OR "ACM Transactions on Softw* Engineer* 
and Methodology" OR "Automated Softw* Engineer*" OR "Empirical 
Softw* Engineer*" OR "IEEE Softw*" OR "IEEE Transactions on 
Softw* Engineer*" OR "IET Softw*" OR "Information and Softw* 
Technology" OR "Int* Journal on Softw* Tools for Technology 
Transfer" OR "Journal of Softw*: Evolution and Process" OR 
"Journal of Systems and Softw*" OR "Requirements Engineer*" 
OR "Softw* and Systems Modeling" OR "Softw* Quality Journal" 
OR "Softw* Testing Verification and Reliability" OR "Softw*: 
Practice and Experience" OR "Int* Journal of Softw* Engineer* 
and Knowledge Engineer*") 
AND (LIMIT-TO (PUBYEAR , 2019) OR LIMIT-TO (PUBYEAR , 2018) 
OR LIMIT-TO (PUBYEAR , 2017) OR LIMIT-TO (PUBYEAR , 2016) 
OR LIMIT-TO (PUBYEAR , 2015)) 
AND (LIMIT-TO (DOCTYPE , "cp") OR LIMIT-TO (DOCTYPE , "ar") 
OR LIMIT-TO (DOCTYPE , "re")) 
AND (LIMIT-TO (SUBJAREA , "COMP")) 
AND (LIMIT-TO (LANGUAGE , "English"))
```
* [Results](https://github.com/rheradio/Machine-Learning-for-Software-Engineering-a-Bibliometric-Analysis-from-2015-to-2019/tree/master/report) of the performed bibliometric analysis.
