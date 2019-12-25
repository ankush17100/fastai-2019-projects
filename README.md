# fastai-2019-projects
Projects and scripts learned in fastai with comments and experimentations of my own.

**Oxford-IIIT Pet Dataset Classification**

This Dataset contains 12 Cat breeds and 25 Dog breeds for a total of 37 breeds. Published in 2012, it was a very difficult problem then. Researchers used complex models which were specific to this problem and still got only 59.21. I used transfer learning to try and clasify this dataset. Using resnet34 I got around 90% accuracy and using resnet50 I got around 95% accuracy.

**Create Dataset Using Google Images**

I Used a small javascript code to save the URLs of images returned in google images search and then fastai functons to verify those images and then make a model on it. I made a model to classify images of Isla Fisher and Amy Adams, since they are so similar that apparently once Amy Fisher put Amy Adams' face in place of her in her family Christmas photo and noone found out, [source](https://timesofindia.indiatimes.com/entertainment/english/hollywood/news/Isla-Fisher-used-Amy-Adams-photo-for-family-holiday-card/articleshow/55510725.cms). 
