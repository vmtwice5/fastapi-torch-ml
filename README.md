# FastAPI - Torch - Machine Learning

Minimal machine learning API, inspired by [fastai MOOC](https://course.fast.ai/) and [cougar-or-not api](https://github.com/simonw/cougar-or-not)

`app/main.py` is a small API built with [fastapi](https://fastapi.tiangolo.com/). It takes an image url or file and runs it through a pretrained model for classification between buffalo, elephant, rhino, or zebra.

`export.pkl` is a resnet34 model, pretrained with the [fastai framework](https://github.com/fastai/fastai) using kaggle [African Wildlife](https://www.kaggle.com/biancaferreira/african-wildlife) dataset. See `african_wildlife.ipynb` for training details.


