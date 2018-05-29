# scikit-learn and Keras demos

This repo contains two Jupyter notebooks which demonstrate how to use some features of scikit-learn &amp; Keras.

## Step 1: Make sure you have python3 installed

Instructions here if you need to grab it: https://www.python.org/downloads/

## Step 2: Grab this repo
```
git clone https://github.com/svivek/scikit_learn_keras_demo
cd scikit_learn_keras_demo
```

## Step 3: Install some pre-requisite libraries
`pip3 install -r requirements.txt`

Note: this setup installs the "CPU version" of TensorFlow; if you're running some large model you'll want to use the "GPU version" for much better efficiency. It's a slightly different setup that is outside the scope of this demo, but just something to keep in mind.

We use graphviz for displaying decision trees in the scikit learn
demo. You may need to install graphviz; follow the instructions
[here](https://graphviz.gitlab.io/download/). On a Mac, `brew
install graphviz` does the trick.



## Step 4: Run the Jupyter notebook
`jupyter notebook`
