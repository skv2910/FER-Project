# Facial Expression Recognition|Coursera Guided Project
**Introduction:**
Facial expressions are the universal way for people to communicate. In this project, we build a deep-learning model for detecting facial expressions.
The dataset consists of (48,48) pixels, grayscale images of seven different expressions. (Anger, Disgust, Fear, Happy, Sad, Surprise, and Neutral).
**Modeling**
We build a 5-layer network, it consists of 3 convolutional layers  with 32,32 and 64 filters respectively, and a max pooling layer after each convolutional layer with kernal size of (3,3) and stride 2, RelU activation funciton was used. And after that 2 FC layers was used and to improve the performance at the end of FC layer droupout layer was also used.
An accuracy of 65.9% was observed with the best model.
**Refrences**
[1] https://cs230.stanford.edu/projects_winter_2020/reports/32610274.pdf

