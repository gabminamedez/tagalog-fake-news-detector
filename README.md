# tagalog-fake-news-detector
This is a Tagalog Fake News Detector model developed via Transfer Learning. In partial fulfillment of the course CSC715M (Natural Language Processing) in De La Salle University - Manila.

# Motivation
The spread of fake news has become one of the more prominent concerns in today's society given the undeniable shift to the digital age. Pieces of information meant to sway public opinion by intentionally fabricating content have become so widespread that it has affected issues ranging from simple ones to ones that may even harm democracies of nations. This issue certainly does not discriminate, particularly in the Philippines where social media usage is overwhelming. There have been several endeavors to combat fake news in natural language processing by detecting it, however, there remain minimal literature and resources regarding the prediction of fake news i the Tagalog language. This project aims to shed some light in the conversation by adopting a pretrained BERT model and developing a new Tagalog fake news detector through neural networks via transfer learning.

## Dataset
The dataset used in the project is the Filipino Fake News data, which features 2,306 data points with a perfect split of real and fake Tagalog news.

## Model Architecture
A pretrained and freezed Tagalog BERT model was used as the base model, superimposed by a Dropout Layer, a ReLU activation function, two dense layers, and a Softmax activation layer.

## Results
The model featured a 71% accuracy over 481 test data.

## Future Work
I was unable to do further experiments due to logistical problems involving my machine. Future work shall highlight model experiments to determine the optimal hyperparameters and overall architecture. Furthermore, I will try to expand upon the current dataset.

## Built With
- Numpy
- Pandas
- Scikit
- PyTorch

## Acknowledgements
- Cruz et al. for the first of its kind Filipino Fake News dataset (Github: [Tagalog-fake-news](https://github.com/jcblaisecruz02/Tagalog-fake-news)).
- Cruz & Cheng for the pretrained Tagalog BERT model (Github: [Filipino-Text-Benchmarks](https://github.com/jcblaisecruz02/Filipino-Text-Benchmarks)).
