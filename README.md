# SETI Signal Classification
SETI is an acronym for the Search for Extraterrestrial Intelligence. It is an effort to detect evidence of
technological civilizations that may exist elsewhere in the universe. 7 type of SETI signals are present in the dataset:
+ brightpixel
+ narrowband
+ narrowbanddrd
+ noise
+ squarepulsednarrowband
+ squiggle
+ squigglesquarepulsednarrowband

Our objective is to differenciate those signals properly.
[Dataset]( https://www.kaggle.com/datasets/tentotheminus9/seti-data?datasetId=57000) is available at Kaggle. This dataset is a smaller version of [Machine Learning for the Search for Extraterrestrial Intelligence Hackathon & Code Challenge](https://www.seti.org/machine-learning-search-extraterrestrial-intelligence-hackathon-code-challenge) dataset. 


### Traditional machine learning results
| Model  | Accuracy |
| :-------------: | :-------------: | 
| KNN+ResNet101 | 30.71%  | 
| KNN+VGG16  | 52.38%  |

### Deep learning results
| Model  | Training epoch | Accuracy |  
| :-------------: | :-------------: | :-------: |
| VGG16 | 50  | 85.71% |
| EfficientNetV2S -fine tuned | 20 | 86.29%|
| Swin-T -fine tuned | 20 | 81% |
