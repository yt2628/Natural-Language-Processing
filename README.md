# Natural Language Processing

## Goal
In this project, I will use natural language processing to generate insights into students' notes, in three steps: process a set of documents, run a sentiment analysis of these documents, and then build topic models of those documents. The documents used are student notes that the class HUDK4050 made.

## Tasks
* Understand the basic process of natural language proceessing and the role of pre-processing text
* Generate a word cloud for frequent words
<img width="650" alt="wordcloud" src="https://user-images.githubusercontent.com/47013908/95770939-30475980-0c88-11eb-96ce-cc3774d02b95.png">
* Conduct a simple sentiment analysis to a set of documents
* Understand and apply a latent dirichlet allocation (LDA) to a set of documents

## Packages Required
```
install.packages("tm")
install.packages("SnowballC")
install.packages("wordcloud")
install.packages("ggplot2")
install.packages("topicmodels")
```
## Background
The use of natural language processing has exploded over the last decade. Appilcations that require machines to understand natural human speech patterns are abundant and substantial improvements in these systems has increased their utility. Within the educational space NLP is used to interpret human speech for the prupose of understanding human problems and recently an online tutor passed a limited version of the [Turing Test](https://en.wikipedia.org/wiki/Turing_test) when it was [indistinguishable from teaching assistants in a college class](http://www.news.gatech.edu/2017/01/09/jill-watson-round-three).


## References

* [Nadkarni, P. M., Ohno-Machado, L., & Chapman, W. W. (2011). Natural language processing: An Introduction. Journal of the American Medical Informatics Association: JAMIA, 18(5), 544–551.](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3168328/)

* [Robinson, A. C. (2015). Exploring Class Discussions from a Massive Open Online Course (MOOC) on Cartography. In J. Brus, A. Vondrakova, & V. Vozenilek (Eds.), Modern Trends in Cartography (pp. 173–182). Springer International Publishing.](http://link.springer.com.ezproxy.cul.columbia.edu/chapter/10.1007/978-3-319-07926-4_14)

* [McNamara, D. S., Crossley, S. A., & Roscoe, R. (2013). Natural Language Processing in an Intelligent Writing Strategy Tutoring System. Behavior Research Methods, 45(2), 499–515.](http://link.springer.com.ezproxy.cul.columbia.edu/article/10.3758/s13428-012-0258-1)

[Crash Course. (2017). Natural Language Processing.](https://www.youtube.com/watch?v=fOvTtapxa9c)

[Raval, S. (2016). Sentiment Analysis in 4 Minutes.](https://www.youtube.com/watch?v=AJVP96tAWxw)

[Knispelis, A. (2016). LDA Topic Models.](https://www.youtube.com/watch?v=3mHy4OSyRf0)

~~[Jurafsky, D. & Manning, C. (2016). What is Sentiment Analysis? Stanford: Palo Alto, CA](https://www.youtube.com/watch?v=sxPBv4Skj98)
[Knispelis, A. (2016). LDA Topic Models.](https://www.youtube.com/watch?v=3mHy4OSyRf0)~~ 
