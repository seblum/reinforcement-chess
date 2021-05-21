# AI Office Showcase - Emotion Detection

This is the result of the Practice Days on October 1st, 2020 and January 18th to 20th and the most recent version of the Emotion Detection Office Showcase.

## Getting started

* OS choice: this will not work on WSL, as you wom't have access to your webcam there. We tested this on windows. It runs on standard AT Laptops and does not need a GPU to work. It is easier if you install Miniconda for everybody, not only for the current user and add it to your PATH variable.
* Check out the repo.
* Create a new conda env with the environment yaml:


```
# create env
conda create -f environment.yml

# activate env
conda activate aioffice

```

## Run Face detection app

```
# run with default settings
streamlit run opencv_streamlit.py
```

Open the IP given in the console in your browser. This will be something like http://localhost:8501.

To start the video, select the use case you want, either mood detection or mask detection, click on the checkbox "Make it run" and start to dance.
