<p align="center">
  <a href="" rel="noopener">
 <img width=300px height=300px src="https://imgur.com/2AVEzXQ.png" alt="Project logo"></a>
</p>

<h3 align="center">Project Title</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Rationale](#rationale)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Improvements](#improvement)


## 🧐 About <a name = "about"></a>
A convolutional neural network that attempts to predict the aggressiveness of soccer players (classification). Data : 15000 soccer players' facial profiles and their corresponding aggressiveness rating. Data was obtained from the following Kaggle dataset :  https://www.kaggle.com/karangadiya/fifa19

## Rationale <a name = "rationale"></a>

While reading this article: https://www.vocativ.com/culture/sport/shape-soccer-players-face-predicts-performance/index.html, I was wondering if I could replicate such results using a convolutional neural network by taking in the players' faces as input, and predicting how aggressive each player is.


## 🏁 Getting Started <a name = "getting_started"></a>
Clone the repository! Players' pictures are in the "faces" folder

### Prerequisites
Anaconda; Python, Jupyter Notebook

Install <a href= "https://www.anaconda.com/distribution/">Anaconda</a> and the rest are all installed together

```
jupyter notebook
```

in the Anaconda terminal to open up the jupyter notebook

If you can't seem to open up jupyter notebook on github, go to https://nbviewer.jupyter.org/ and paste the github link in there.

Install numpy in the terminal

```
conda install numpy
```


Install pandas

```
conda install pandas
```

Install matplotlib

```
conda install -c conda-forge matplotlib
```

Install tensorflow

```
conda create -n tensorflow_env tensorflow
 	
  conda activate tensorflow_env
```

## 🎈 Usage <a name="usage"></a>

Run the nip_project.ipynb on your jupyter notebook terminal. To obtain a training and test set. Then run nip_project_model.ipynb to build on the model.

## 🚀 Improvements <a name = "improvement"></a>

Utilize transfer learning with a good pre-trained model. Limitations: Current dataset has 15000 faces; most transfer learning cases have lesser data. Can still try in the future if I have a better computer.

