# Word-based-Language-Identification-Part-2
This project focuses on designing a language identifier that can generalize to unseen domains trained over the large comparable corpus. The project proves that pre-processing data while preserving linguistic nuances of the languages plays a significant role in the ability of a language identifier to perform well even on short texts outside the domain. Accuracy of over 99% is achieved for long texts and accuracy of 97.8% is achieved for truncated three-word texts with a reduced number of stop words.

## Documentation

All of the documentation can be found in the docs folder.

## Development

- Programming langauge - Pyhon, 3.7.2 
- OS - Windows 10 Home.


## Pipeline
The final pipeline consists of the pre-processing accounting for linguistic nuances, customized CountVectorizer with the maximum features set to 1,000,000, 1-3 word-based n-grams, and Multinomial Naive Bayes. 

## Pipeline's Performance
![picture](https://github.com/natacasey/Word-based-Language-Identification-Part-2/blob/main/_assets/FINAL.PNG_


## Consideration for the future:
Accuracy of predictions for the neutral class could be improved by addressing the multipolarity issue of the neutral class reviews
