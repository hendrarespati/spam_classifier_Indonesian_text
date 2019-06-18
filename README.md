
# Spam classifier for Indonesian Text Message
=================

Repo for spam classifier in indonesian text using Naive Bayes methods 


**Naive-Bayes** is a simple technique for constructing classifiers: models that assign class labels to problem instances, 
represented as vectors of feature values, where the class labels are drawn from some finite set.

In machine learning, naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naive) independence assumptions between the features.


for this repo i have succeeded make naive bayes classifier model with accuracy 92,5%, sensitivity 93%. and specificity 92%

![](https://cdn.glitch.com/5f119f1f-ebe3-480c-a9f7-0dace9bbf33a%2FWhatsApp%20Image%202019-06-19%20at%2001.16.18.jpeg?v=1560881889531)

i'm also found that words like “anda”,“atau”,“bonus”,“http”, “kuota”, “kartu”,“paket”, 
“registrasi”, “ketik”. “kirim” from above sample appearing in a sentence seem to be classified as spam


For text mining and stemming Indonesian text i'm using Nazief Algorithm, to install run:

```
install.packages("katadasaR")
```

Find out more about [katadasaR](https://github.com/nurandi/katadasaR).


**Screenshot**




![](https://cdn.glitch.com/5f119f1f-ebe3-480c-a9f7-0dace9bbf33a%2Funnamed-chunk-10-1.png?v=1560880479539)