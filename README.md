# Automated Detection of COVID-19 Cases Using Deep Neural Networks with X-Ray Images

Introducing a new algorithm based on the selection of features extracted from the DensNet169 deep neural network and the LightGBM classification algorithm for the automatic detection of Covid 19 disease from X-ray images

## Dataset

In `DataSet` Folder there is 3 folder 

+ Covid-19    => 125 images
+ No_findings => 625 images
+ Pneumonia   => 625 images

[Dataset references](https://github.com/muhammedtalo/COVID-19)

## Accuracy

| Classification  | Accuracy Score |
| --- | --- |
| Binary class classification (Covid-19 vs. No-finding) | 98.54  |
| Multi class classification (Covid-19 vs. Pneumonia vs. No-finding)  | 91.11  |
