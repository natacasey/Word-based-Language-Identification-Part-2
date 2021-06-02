![picture](https://github.com/natacasey/Word-based-Language-Identification-Part-2/blob/main/_assets/pipeline%20(2).png)

This project focuses on designing a language identifier that can generalize to unseen domains trained over the large comparable corpus. The project proves that pre-processing data while preserving linguistic nuances of the languages plays a significant role in the ability of a language identifier to perform well even on short texts outside the domain. Accuracy of over 99% is achieved for long texts and accuracy of 97.8% is achieved for truncated three-word texts with a reduced number of stop words.

## Data can be found [here](https://drive.google.com/drive/folders/1JY2CBTMLoj7o2uBwGWWqfEUFrKeOOvZQ?usp=sharing)

## Documentation

All of the documentation can be found in the docs folder.

## Development

- Programming langauge - Pyhon, 3.7.2 
- OS - Windows 10 Home.


## Pipeline
The final pipeline consists of the pre-processing accounting for linguistic nuances, customized CountVectorizer with the maximum features set to 1,000,000, 1-3 word-based n-grams, and Multinomial Naive Bayes. 

## Pipeline's Performance
![picture](https://github.com/natacasey/Word-based-Language-Identification-Part-2/blob/main/_assets/FINAL.PNG)


## Consideration for the future:
The recommendation for future work includes experimenting with the type of word n-grams used for feature representation. Testing the outcomes when using unigrams and bigrams, just unigrams, or just bigrams could reveal a new factor affecting the word-based language identification performance. Increasing the pool of languages where word segmentation is performed using white space could allow us to better understand the capabilities of the pipeline. 
