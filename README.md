# Full Stack Deep Learning Study
### 가짜연구소 3기
#### 2021년 7월 21일 ~ 진행중

강의 : [https://fullstackdeeplearning.com/](https://fullstackdeeplearning.com/)  
코드 : [https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2021-labs](https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2021-labs)


## 1. Requirement(fullstack)
```
python=3.6
numpy
pillow
matplotlib
h5py
smart_open
toml
nltk
pip install boltons wandb pytorch_lightning==1.1.4
pip install torch==1.7.1+cu101 torchvision==0.8.2+cu101 torchaudio==0.7.2 -f https://download.pytorch.org/whl/torch_stable.html
```


## 2. Contents  
Lab 1: Intro: Formulate problem, structure codebase, train an MLP for MNIST.  
Lab 2: CNNs: Introduce EMNIST, generate synthetic handwritten lines, and train CNNs.  
Lab 3: RNNs: Using CNN + LSTM with CTC loss for line text recognition.  
Lab 4: Transformers: Using Transformers for line text recognition.  
Lab 5: Experiment Management: Real handwriting data, Weights & Biases, and hyperparameter sweeps.  
Lab 6: Data Labeling: Label our own handwriting data and properly store it.  
Lab 7: Paragraph Recognition: Train and evaluate whole-paragraph recognition.  
Lab 8: Continuous Integration: Add continuous linting and testing of our code.  
Lab 9: Deployment: Run as a REST API locally, then in Docker, then put in production using AWS Lambda.  
Lab 10: Monitoring: Set up monitoring that alerts us when the incoming data distribution changes.  
