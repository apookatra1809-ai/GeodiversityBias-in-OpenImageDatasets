# Geodiversity Bias in Open Image Datasets 

## About this project
This is my CA2 submission, which critically reviews Shankar et al. (2017), "No Classification without Representation: Assessing Geodiversity Issues in Open Data Sets for the Developing World". The paper looks at whether ImageNet and Open Images, two datasets widely used to train vision models, represent the world fairly.

## Key points from the paper
* Both datasets are heavily skewed towards the US and Western Europe. Six Western countries account for over 60% of Open Images, while China and India each contribute only 1% to 2%.
* Pretrained Inception V3 classifiers perform noticeably worse on images from underrepresented countries such as India, Pakistan, Ethiopia and China.
* Example: Indian "groom" images were often misclassified as chain mail, academic gown or vestment, because the model links "groom" to Western wedding clothing.

## What my report covers
* Sources of bias: sampling bias from internet collected images, hidden subgroups inside single class labels, and measurement bias from using URL metadata to guess image location.
* Impact on metrics: why accuracy and log likelihood scores on Western heavy test sets can hide poor performance elsewhere.
* Mitigation: building locally relevant datasets, working with regional photographers and raters, and using model confidence scores. I also point to the GeoDE dataset as related work.


## How to run
Open FINALIST_WINNER_CA2_FINAL.ipynb in Jupyter or Google Colab and run the cells in order.

## Reference
Shankar, S., Halpern, Y., Breck, E., Atwood, J., Wilson, J. and Sculley, D. (2017). No Classification without Representation: Assessing Geodiversity Issues in Open Data Sets for the Developing World.
