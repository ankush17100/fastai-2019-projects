# fastai-2019-projects
Projects and scripts learned in fastai with comments and experimentations of my own. This is for my own learning purpose and for showcasing the things I worked on.

**Oxford-IIIT Pet Dataset Classification**

[Oxford-IIIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/) by [O. M. Parkhi et al., 2012](http://www.robots.ox.ac.uk/~vgg/publications/2012/parkhi12a/parkhi12a.pdf). This Dataset contains 12 Cat breeds and 25 Dog breeds for a total of 37 breeds. Published in 2012, it was a very difficult problem then. Researchers used complex models which were specific to this problem and still got only 59.21. I used transfer learning to try and clasify this dataset. Using resnet34 I got around 90% accuracy and using resnet50 I got around 95% accuracy.

**Create Dataset Using Google Images**

I Used a small javascript code to save the URLs of images returned in [google images](http://images.google.com) search and then fastai functons to verify those images and then make a model on it. I made a model to classify images of Isla Fisher and Amy Adams, since they are so similar that apparently once Amy Fisher put Amy Adams' face in place of her in her family Christmas photo and noone found out, [source](https://timesofindia.indiatimes.com/entertainment/english/hollywood/news/Isla-Fisher-used-Amy-Adams-photo-for-family-holiday-card/articleshow/55510725.cms). I downloaded 300 photos of each actor and then split those photos in training split of 80% and validation split of 20% and I got around 80% accuracy in the validation split. The reason for such low accuracy is that google search returns any popular image that mentions the actor so images such as that actor with other people are also returned which is a bad data point and brings down model performance.

**SGD**

Here I demonstrated the problem of linear regression and implemented it in pytorch and then I made an animation to show the algorithm optimise it.

**Head-Pose**

In this project I did Image regression in finding the center of the head in the images. The Dataset used is [Biwi head pose dataset](https://data.vision.ee.ethz.ch/cvl/gfanelli/head_pose/head_forest.html#db)

**Camvid**

In this project I use the camvid dataset and use the `unet_learner` from fastai and having resnet34 as the downward model in the unet - the settings is also called a dynamic unet. I achieved around 93% accuracy calculated according to the guidelines in the original dataset papet. I also did progressive resizing in this.

**Camvid_Tiramisu**

In this project I used the camvid dataset again but I used a smaller version, a version that was used in the 100 layer tiramisu paper that I got from this [github link](https://github.com/alexgkendall/SegNet-Tutorial). Using the same approach as in the previous(above) notebook, I got around 93% accuracy in this dataset too.

Made with :blue_heart: by Ankush
