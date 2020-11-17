# Requirements outline DSBA final project 
**Roman Jurowetzki - Daniel Hain**

## Format

* Project report (standard format, not notebook 20-ish pages - max. standard 30 - 2400 characters incl. spaces)
* Functional and self-contained notebook as appendix
* Happy to see GitHub repos (which you can use as your portfolio in the jobmarket)
* Some study relation (but that is debatable and not necessarily required)
* Report is a (semi/non) technical documentation. Think about a corporate censor that you try to inform

## Content

* Problem formulation with some practical and theoretical motivation (no huge literature discussion)
* Methodology (not a critical realist vs positivist discussion but some ideas about what can be concluded potentially)
* Data sourcing and pre-processing strategy
* Overall architecture of the model(s)
* Modelling (incl. finetuning)
* Results
* Discussion / Conclusion

## Scope

* Uses different methods from the course (at least 2 modules) in a creative way
* Downloading data from kaggle/github and running an ML model is probably not enough for a good performance
* Creative combinations of methodologies, please:
    * combine financial data with social media data to look at equity development
    * extract information from text data and create networks. Use network indicators to supplement company data
* Evaluation will focus on correct application and communication of DS methods
* The level of "technicality" is as in the course with emphasis on application and intuition, not on ML engineering / mathematics
* However, you will need to demonstrate insight into statistics on a level that is required to discuss your assignment e.g. interpret and discuss performance indicators, outline strategies for improvement e.g. under/oversampling

## Examples

* [SML Mini project](https://sds-aau.github.io/dsba-cbs/documents/M3_example_housrprice.html): 5 ECTs project on predicting housing prices
* [SML Mini project](https://sds-aau.github.io/dsba-cbs/documents/M1_example_credit.nb.html): 5 ECTs project on predicting credit default
* [SML Mini project](https://sds-aau.github.io/dsba-cbs/documents/M1_example_ATM.nb.html): 5 ECTs project  on predicting ATm withdrawl
* [NLP + DL mini project](https://sds-aau.github.io/dsba-cbs/documents/M3_example_sentimnts.html): 5 ECTS project on sentiment analysis plus Deep Learning predictions.

## Data Scourses

### General

* [Kaggle](https://www.kaggle.com/datasets): ML&DS community & competiton plattform, full of good datasets
* ...

### Networks

* [Stanford Large Network Dataset Collection](http://snap.stanford.edu/data/index.html): Amazing collection of different types of (sometimes rather large) network datasets 
* [The network repository project](http://networkrepository.com/): Really huge collection of network datasets across all realms.
* [Sociopattern](http://www.sociopatterns.org/datasets/): Really interesting collection of social networks

# Further advice

## Managing "bilangual" projects

* Clearly split and define tasks, process steps, deliverables
* Speficy properties of deliverables (data format, variable types)
* Use standardized data exchange fomats (csv, json, HDF5) or specific R-python exchange formats (feather)
* `reticulate` (R) & `rmagic` (Python)
