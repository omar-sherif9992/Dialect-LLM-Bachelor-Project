<div id="top"></div>

<h1 align="center">Hi <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px">, I am Omar Sherif Ali </h1>
<h4 align="center">Supervised by : <a href='https://github.com/mervatkheir'>Professor Mervat Mustafa Fahmy Abuelkheir</a></h1>

<h3 align="center">Computer Science & Engineering</h3>
<h6 align="center">"Language is the bridge that connects minds, and NLP is the compass guiding us to understand and unlock its infinite potential."</h6>

<br>

<h1 align="center">Welcome to my Bachelor Thesis</h1>

<div align="center">
    <img src="https://cdn-icons-png.flaticon.com/512/1242/1242157.png?w=826&t=st=1684776646~exp=1684777246~hmac=ac152735fe07887cc6ac63d137e4eb28e58381758e7cdc641c1448824d183caf" alt="Logo" width="80" height="80">
<br/>
<img src="https://cdn-icons-png.flaticon.com/512/732/732110.png?w=826&t=st=1684776825~exp=1684777425~hmac=d862fad36432a9768c4e6f3e00c6eb0b09c6cd140380a321effe4f084064ab95" alt="Logo" width="60" height="60">
<br/>

<img src="https://cdn-icons-png.flaticon.com/512/323/323324.png?w=826&t=st=1684777864~exp=1684778464~hmac=067f753b35d957d4276ea81451a4d79e11c6101a6f450beb45e59643359fda64" alt="Logo" width="80" height="80">
<img src="https://cdn-icons-png.flaticon.com/512/260/260309.png?w=826&t=st=1684777687~exp=1684778287~hmac=efa931409d0be09c733c7650b48631b54f6c1c522895479ee4102f6f2b79b9bd" alt="Logo" width="80" height="80">
<img src="https://cdn-icons-png.flaticon.com/512/648/648953.png?w=826&t=st=1684776952~exp=1684777552~hmac=336fe32c54d4f4c6feb727076f57d09aa9aab680c797e7ef2fc47064c974c411" alt="Logo" width="80" height="80">
<img src="https://cdn-icons-png.flaticon.com/512/865/865018.png?w=826&t=st=1684777116~exp=1684777716~hmac=972db3c9570b0f3d5e61e2282918f86f48a73a76399c1c7dc5e7946809e734e0" alt="Logo" width="80" height="80">
<img src="https://cdn-icons-png.flaticon.com/512/538/538759.png?w=826&t=st=1684777213~exp=1684777813~hmac=b23ef3f3653c2a954bde5410ff1d205739ae96c990ff0b0f91f6c56f15d35201" alt="Logo" width="80" height="80">

  <h3 align="center">Egyptian Tweet Sentiment Analysis , Forecasting and Topic Modeling</h3>

  <p align="center">
The aim of the Bachelor project is to innovate a new way for Arabic (Egyptian-Dialect) Sentiment Analysis, Forecasting, and Topic Modeling using Machine Learning, Deep Learning, and Transformers!
    <br />
    <br />
	  📄<a href="https://github.com/omar-sherif9992/Bachelor-Thesis/blob/master/Bachelor_Thesis.pdf" download target="_blank"><strong>View the Thesis »</strong></a>
    <br />
	  
	      <a href="https://docs.google.com/presentation/d/1ocnuHE1hyZdBHtY9c_Gr4bYPGiyaEVlAmYpUGlL795I/edit?usp=sharing">Presentation</a>
    <a href="mailto:osa.helpme@gmail.com?subject=UnExpected%20Error%20Occured&body=Sorry%20for%20the%20inconvenience%2C%20Please%20describe%20Your%20situation%20and%20emphasis%20the%20Endpoint%20!%0A">Report Bug</a>
   	      ·
    <a href="mailto:osa.helpme@gmail.com?subject=I%20want%20to%20be%20a%20Contributor%20to%20Bachelor Thesis&body=Dear%20Omar%20Sherif">Be a Contributer</a>
  </p>
</div>
<img src="./thesis images/methodology.png" alt="model architechture" width="100%" height="18%">

## 💡 Description

In recent years, social media platforms have become increasingly popular for individuals to express their thoughts and opinions on various topics and situations. Monitoring sentiment and understanding the evolution of topics is crucial for governments to identify negative sentiments and respond promptly. In this study, we developed a sentiment analysis ensemble model architecture consisting of 4 different Transformers namely: MARBERT,CaMel-bert-DA, CaMel-bert-Mix, and Alanzi. This ensemble architecture was followed by a final classification layer, consisting of a three-layer feed-forward neural network. The output of each transformer applied on its logits a formula, and the resulting logits were then summed before applying the softmax activation function. Evaluating the model’s performance on the sentiment analysis test dataset, an impressive test accuracy of 83%. To analyze the temporal trends of sentiment, we applied the LSTM model using a sliding window to time-stamped tweets related to English News, which generated significant discussions on social media. That is then translated to Arabic by a translation model. we plotted the sentiment arc and observed our results with the original results. We explored the effectiveness of BERTopic, a topic modeling technique, in comparison to LDA and NMF techniques. By employing various pre-trained Arabic language models as embeddings, we conducted topic modeling and aspect-based analysis. The results highlight that BERTopic and NMF achieved comparable and competitive outcomes, demonstrating their capability to capture meaningful topics effectively. However, LDA exhibited poor performance in generating coherent and informative topics. These findings emphasize the superiority of BERTopic and NMF over LDA in topic modeling tasks.

<img src="./thesis images/Model_architecture.drawio.png" alt="model architechture" width="100%" height="18%">

## Pipeline

- **Tweet Collecting & Merging & Pre-processing & Analysis & Correctness Investigation**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AP-xbKQhJsfKsqKKFjfL6faWUHEkkttq?usp=sharing)

- **Machine Learning Sentiment Analysis**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18F75YeaO0hSJgZjciiit6-ziIRABujTy?usp=sharing)

- **Deep Learning Sentiment Analysis**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Z2HouT1JXS27tO2sil8i_t9n18siaD4Q?usp=sharing)

- **Pure Transformers Sentiment Analysis**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-xwuOBEUC7fyXCuPdrDmUE9VX8AmUEeu?usp=sharing)

- **Customized Transformers & Ensemble Model Sentiment Analysis & Website**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nn91vLfiwN-JASkuUdzVnXB5-lSj3XIn?usp=sharing)

- **Sentiment Forecasting**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SJKG2zJagVmVA9IQwGFBiZqsxlbXT29F?usp=sharing)

- **Aspect-Based & Topic Modeling**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I7riFSfE2zfUsE83Gri2x6RBkShR0uD7?usp=sharing)

- **Zero Shot Classification**
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BOOFa9enDKo5m8Y4HMXB3mCgW2c6Rzes?usp=sharing)

## Sentiment Analysis Website

<img src="./thesis images/website.png" alt="model architechture" >

### 💻️ Languages & Libraries Used

- [Python](https://www.python.org/)
- Data Analysis and Visualization
  - [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)
  - [Matplotlip](https://matplotlib.org/)
  - [Seaborn](https://seaborn.pydata.org/)
  - [Word Cloud Fa](https://pypi.org/project/wordcloud/)
- Machine Learning
  - [Sckitlearn]()
- Deep Learning
  - [Tensorflow](https://pypi.org/project/tensorflow/)
  - [Pytorch](https://pypi.org/project/pytorch/)
- Transformers
  - [Hugging Face](https://huggingface.co/models)
- Topic Modeling
  - [Gensim](https://pypi.org/project/gensim/)
  - [Bertopic](https://pypi.org/project/bertopic/)

<p align="right">(<a href="#top">back to top</a>)</p>

### ⚠️ Disclaimer

Users who will Use this Data should only use it for Practice and <strong>not for Commercial Purposes !</strong>

<p align="right">(<a href="#top">back to top</a>)</p>

### Author: <i>Omar Sherif Ali - OSA</i>

<p align="right">(<a href="#top">back to top</a>)</p>

<div align="center">
<h2> Connect with me <img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="100px"> </h2>
<a href="https://github.com/omar-sherif9992">
	<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/omar-sherif-2152021a3/">
	<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="mailto: omar.sherif9992@gmail.com">
	<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://www.youtube.com/channel/UCt0eXFStNA2oX5AqMjIBprw">
	<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
</a>
</div>
<br>
<div align="center">
<a href="https://www.youtube.com/channel/UCt0eXFStNA2oX5AqMjIBprw">
	<img src="https://github-readme-streak-stats.herokuapp.com/?user=omar-sherif9992"></a>

<p  align="center">Made with ❤️ by Omar Sherif Ali - OSA.</p>
<p  align="center">© OSA - 2022</p>
<p align="right">(<a href="#top">back to top</a>)</p>

### Daily Progress

#### First Week

| Date       | Day       | Progress                                                                                                   | Resources                                      |
| ---------- | --------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| 2023-03-01 | Saturday  | reading in OReily Sckitlearn book ,revisied Python and searching for extra resources                       | book                                           |
| 2023-03-01 | Sunday    | reading in OReily Sckitlearn book and searching for extra resources                                        | book                                           |
| 2023-03-01 | Monday    | Learned NLP,Tokenization,stemmation,lemmetization,count vectorizer                                         | Udemy course on Python                         |
| 2023-03-01 | Tuesday   | Discovered Pandas and done 5 notesbooks for practice on kaggle and finished Data cleaning course in Kaggle | Kaggle                                         |
| 2023-03-01 | Wednesday | learned TF-IDF+ notebooks excercise and finished Machine Learning Beginner Kaggle Course                   |
| 2023-03-02 | Thursday  | Digging deep in models and their hyperparameters and participating in kaggle competition                   | Kaggle competition on house prices             |
| 2023-03-03 | Friday    | understand feature engineering and importance, imputers ,Worked on project proposal                        | Medium article on best practices for ML models |

#### Second Week

| Date       | Day       | Progress                                                                                | Resources                                  |
| ---------- | --------- | --------------------------------------------------------------------------------------- | ------------------------------------------ |
| 2023-03-01 | Saturday  | Understand more models SVMs,KNN and ensemble models XGBoost                             | Coursera course on Python for Data Science |
| 2023-03-01 | Sunday    | Finished Kaggle ML interediate course,categorial encoding,and search for more resources | Kaggle                                     |
| 2023-03-01 | Monday    | ROC,AUC,Conersion matrix,Covariance matrix                                              |                                            |
| 2023-03-01 | Tuesday   | Learned about standardization and done a project on all previously learned models       | Coursera course on Python for Data Science |
| 2023-03-01 | Wednesday | Activation functions and Sentiment analysis                                             |                                            |
| 2023-03-02 | Thursday  | Model Interpretation(Model-agnostics),text summarization,random walk                    |                                            |
| 2023-03-03 | Friday    |                                                                                         |                                            |
