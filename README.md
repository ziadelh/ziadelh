<div align="center">

<img src="assets/banner.svg" alt="Ziad Elhussein — AI & Machine Learning Engineer" width="100%">

<br>

[**Portfolio site**](https://ziadelh.github.io/) &nbsp;·&nbsp; [**Featured**](#featured--pawlytics) &nbsp;·&nbsp; [**Selected work**](#selected-work) &nbsp;·&nbsp; [**All projects**](#all-projects) &nbsp;·&nbsp; [**Toolbox**](#toolbox) &nbsp;·&nbsp; [**Contact**](#get-in-touch)

![Location](https://img.shields.io/badge/Cairo,_Egypt_·_Remote-141a3a?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Multimodal_ML_·_NLP_·_Audio_·_Vision-0c3b46?style=for-the-badge)
![Open](https://img.shields.io/badge/Open_to-Internships_·_Collaboration-4f46e5?style=for-the-badge)

<br>

<img src="assets/terminal.svg" alt="Terminal card: Ziad Elhussein, AI and ML engineer in Cairo. Focus: multimodal learning, NLP, audio, computer vision. 21 projects. Pawlytics held-out test accuracy: text 63.8%, audio 71.9%, image 73.2%." width="86%">

</div>

## About

I build machine-learning systems **end to end**: collecting and cleaning data, training and honestly evaluating
models, and wrapping them in web apps that people can actually use. My graduation project combined three
deep-learning models — text, audio and image — into one assistant for dog health.

I care about the parts that make ML trustworthy: leak-free splits, class imbalance, reporting **held-out**
results, and being upfront about what a model can't do.

---

## Featured · Pawlytics

<table>
<tr>
<td width="46%" valign="middle">
<a href="https://github.com/ziadelh/pawlytics"><img src="assets/projects/pawlytics.jpg" alt="Pawlytics multi-modal analysis form" width="100%"></a>
</td>
<td valign="top">

### [Pawlytics](https://github.com/ziadelh/pawlytics)
*Graduation project · multimodal AI pet-health assistant*

Describe the symptoms, upload a photo, record a sound — three models run behind an Express + Flask app and
are merged by a rule-based step into one report with likely conditions, an urgency level and next steps.

| Modality | Model | Test accuracy |
|---|---|---|
| Text | Bio_ClinicalBERT · 20 conditions | 63.8 % |
| Audio | YAMNet + MLP · 8 sound classes | 71.9 % |
| Image | EfficientNet-B0 · 9 conditions | 73.2 % |

**[Repository](https://github.com/ziadelh/pawlytics)** · **[Model cards](https://github.com/ziadelh/pawlytics/blob/main/docs/MODEL_CARDS.md)**

</td>
</tr>
</table>

```mermaid
flowchart LR
  A[Browser] --> B[Express + MongoDB]
  B --> C[Flask AI service]
  C --> D[Text model]
  C --> E[Audio model]
  C --> F[Image model]
  D & E & F --> G[Combined report]
```

`PyTorch` · `TensorFlow` · `Hugging Face` · `Flask` · `Node.js` · `Express` · `MongoDB`

---

## Selected work

<table>
<tr>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/artificial-intelligence-mountain-climbing-creature"><img src="assets/projects/artificial-intelligence-mountain-climbing-creature.jpg" alt="Evolved creatures climbing a mountain" width="100%"></a><br>
<b>Mountain-climbing creature</b><br>
<sub>Genetic algorithm that evolves virtual creatures to climb a mountain in a PyBullet physics simulation.</sub><br>
<sub><code>Python</code> · <code>PyBullet</code></sub>
</td>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/fake-news-detection"><img src="assets/projects/fake-news-detection.jpg" alt="Fake news model comparison" width="100%"></a><br>
<b>Fake-news detection</b><br>
<sub>Naive Bayes + TF-IDF vs Word2Vec + logistic regression: 94 % vs 97 % accuracy.</sub><br>
<sub><code>scikit-learn</code> · <code>NLTK</code> · <code>gensim</code></sub>
</td>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/traffic-car-tracking"><img src="assets/projects/traffic-car-tracking.jpg" alt="Cars counted in traffic footage" width="100%"></a><br>
<b>Traffic car tracking</b><br>
<sub>Detects, tracks and counts cars in traffic-camera footage with classical computer vision.</sub><br>
<sub><code>OpenCV</code> · <code>Kalman filters</code></sub>
</td>
</tr>
<tr>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/speech-recognition-assistant"><img src="assets/projects/speech-recognition-assistant.jpg" alt="Word error rate by language" width="100%"></a><br>
<b>Speech-recognition assistant</b><br>
<sub>Offline English / Spanish / Italian recognition with noise filtering and word-error-rate evaluation.</sub><br>
<sub><code>Vosk</code> · <code>Python</code></sub>
</td>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/web-audio-apps"><img src="assets/projects/web-audio-apps.jpg" alt="Music visualiser" width="100%"></a><br>
<b>Web audio apps</b><br>
<sub>Real-time effects processor, audio CAPTCHA and two live visualisers in the browser.</sub><br>
<sub><code>p5.js</code> · <code>Web Audio</code> · <a href="https://ziadelh.github.io/web-audio-apps/">▶ demo</a></sub>
</td>
<td width="33%" valign="top" align="center">
<a href="https://github.com/ziadelh/snooker-game"><img src="assets/projects/snooker-game.jpg" alt="Snooker table" width="100%"></a><br>
<b>Snooker</b><br>
<sub>Physics-based snooker with three game modes and a guided tutorial.</sub><br>
<sub><code>p5.js</code> · <code>Matter.js</code> · <a href="https://ziadelh.github.io/snooker-game/">▶ play</a></sub>
</td>
</tr>
</table>

---

## All projects

### Machine learning & AI

| Project | What it does |
|---|---|
| [**Pawlytics**](https://github.com/ziadelh/pawlytics) | Multimodal dog-health assistant: Bio_ClinicalBERT, YAMNet and EfficientNet-B0 behind Express + Flask. |
| [**Mountain-climbing creature**](https://github.com/ziadelh/artificial-intelligence-mountain-climbing-creature) | Genetic algorithm that evolves virtual creatures to climb a mountain in a PyBullet physics simulation — tree-shaped genome, multi-term fitness, tournament selection. |
| [**Fake-news detection**](https://github.com/ziadelh/fake-news-detection) | Naive Bayes + TF-IDF vs Word2Vec + logistic regression: **94 % vs 97 %** accuracy. |
| [**House-price prediction**](https://github.com/ziadelh/machine-learning-house-prices) | Under-fitting vs over-fitting vs a tuned Keras network with dropout and early stopping. |
| [**Loan approval**](https://github.com/ziadelh/machine-learning-loan-approval) | Decision tree and KNN written from scratch, PCA, nested cross-validation. |
| [**Movie revenue prediction**](https://github.com/ziadelh/movie-revenue-prediction) | Cleaning, statistics and linear / polynomial regression on 9,700 TMDb movies. |
| [**Web scraping & text analysis**](https://github.com/ziadelh/web-scraping-text-analysis) | Scrapes eight articles on virtual reality and compares them: word frequencies, bigrams, word cloud. |

### Computer vision & audio

| Project | What it does |
|---|---|
| [**Traffic car tracking**](https://github.com/ziadelh/traffic-car-tracking) | Detects, tracks and counts cars in traffic-camera footage with frame differencing, background subtraction and Kalman filters (OpenCV). |
| [**Speech-recognition assistant**](https://github.com/ziadelh/speech-recognition-assistant) | Offline multilingual (EN / ES / IT) airport assistant with Vosk — noise filtering and word-error-rate evaluation. |
| [**Audio steganography**](https://github.com/ziadelh/audio-steganography) | Finds a code hidden near 19 kHz and hides a message in least-significant bits (SciPy). |
| [**Media compression tools**](https://github.com/ziadelh/media-compression-tools) | Lossless audio compression with Rice coding built from scratch, plus an automatic film-format checker / converter (ffprobe, ffmpeg). |
| [**Web audio apps**](https://github.com/ziadelh/web-audio-apps) · [▶ demo](https://ziadelh.github.io/web-audio-apps/) | Real-time effects processor, audio CAPTCHA, Meyda visualiser and a voice-controlled visualiser. |
| [**Webcam image processing**](https://github.com/ziadelh/webcam-image-processing) · [▶ demo](https://ziadelh.github.io/webcam-image-processing/) | Live colour channels, thresholding, HSV / YUV conversion and face detection. |

### Apps & games

| Project | What it does |
|---|---|
| [**Vet clinic app**](https://github.com/ziadelh/vet-clinic-app) | Accounts, appointment booking with Google Maps, pet shop with cart and memberships. |
| [**Blog app**](https://github.com/ziadelh/blog-app) | Author and reader views, likes, comments and drafts. |
| [**Snooker**](https://github.com/ziadelh/snooker-game) · [▶ play](https://ziadelh.github.io/snooker-game/) | Browser snooker with Matter.js physics, three game modes and a tutorial. |
| [**Platformer**](https://github.com/ziadelh/platformer-game) · [▶ play](https://ziadelh.github.io/platformer-game/) | Side-scroller with coins, enemies, lives and a scrolling camera. |
| [**Drawing app**](https://github.com/ziadelh/drawing-app) · [▶ try](https://ziadelh.github.io/drawing-app/) | Eight tools, palette, undo, cut & paste, save to image. |
| [**Crypto trading simulator**](https://github.com/ziadelh/crypto-trading-simulator) | C++ console exchange with candlestick plots, built on a 1M-row order book. |
| [**DJ mixing app**](https://github.com/ziadelh/dj-mixing-app) | Two-deck mixer in C++ / JUCE: waveforms, faders, searchable library. |
| [**Porsche fan site**](https://github.com/ziadelh/porsche-website) · [▶ visit](https://ziadelh.github.io/porsche-website/) | Six-page site with slideshow, racing news and a 911 showcase. |

---

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=flat-square&logo=p5dotjs&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-basics-2496ED?style=flat-square&logo=docker&logoColor=white)

**Strengths:** multimodal pipelines · NLP fine-tuning · class-imbalance handling · evaluation (F1, ROC-AUC,
confusion matrices) · model explainability · genetic algorithms · shipping models behind a web UI.

## Right now

- Continuing to develop **Pawlytics**
- Exploring vector search and memory-augmented models
- Learning **React** and getting more comfortable with **Docker**

---

<div align="center">

## Get in touch

**Open to internships, collaboration and project opportunities.**

<br>

<a href="https://www.linkedin.com/in/ziad-elhussein"><img src="assets/btn-linkedin.svg" alt="LinkedIn: ziad-elhussein" height="52"></a>
&nbsp;
<a href="mailto:ziadelhussein@gmail.com"><img src="assets/btn-email.svg" alt="Email: ziadelhussein@gmail.com" height="52"></a>
&nbsp;
<a href="https://ziadelh.github.io/"><img src="assets/btn-website.svg" alt="Portfolio website: ziadelh.github.io" height="52"></a>

</div>
