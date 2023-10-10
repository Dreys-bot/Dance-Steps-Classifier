### 💃🕺Classifying dance and music with the help of Artificial Intelligence !

![](https://github.com/Dreys-bot/Dance-Steps-Classifier/blob/main/results/result.gif)

This project implements deep learning algorithms for the automatic classification of dance videos. By extracting key body features from estimated poses, it captures the style and choreography specific to different genres.
<br> <!-- line break -->

## 📝 Summary of Project

### Data collection
Dance videos were collected for each style (afrobeat, classical, hip-hop). These videos were cut into key frames representing each movement, and the labels were digitally encoded.

### Model conception
A convolution model (CNN) was designed and trained on the data. It comprises:

10 training epochs
Batch size of 32
Training rate of 0.0005
Results displayed every 40 iterations
GPU execution
Training and test loaders
3 classification classes: Afrobeat, Classical, Hip-hop
Adam optimizer
Scheduler decrementing learning rate
CrossEntropyLoss loss criterion

### Results
![](https://github.com/Dreys-bot/Dance-Steps-Classifier/blob/main/Graphs/Accuracy_1kepochs.png)

![](https://github.com/Dreys-bot/Dance-Steps-Classifier/blob/main/Graphs/Losses_1kepochs.png)



