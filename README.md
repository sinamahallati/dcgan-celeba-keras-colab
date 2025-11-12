# DCGAN on CelebA (Keras • Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sinamahallati/<REPO_NAME>/blob/main/dcgan_celeba_colab.ipynb)

Colab-ready notebook to train a DCGAN on **CelebA (64×64)**.
Includes a **speed mode**: mixed precision, XLA, cached `tf.data`, and limited steps per epoch.  
Saves a sample grid every epoch and a final **progress GIF**.

## Features
- Keras/TensorFlow 2
- Mixed precision + XLA
- `tf.data` cache & prefetch
- Configurable `MAX_FILES` & `STEPS_PER_EPOCH`
- GIF of training progress

## Quickstart
1. Open the notebook in Colab (badge above) → **Runtime > Change runtime type > GPU**.
2. Download CelebA from Kaggle (two options provided in the notebook).
3. Run cells top to bottom. Outputs appear in `/content/dcgan_samples/` and `dcgan_progress.gif`.

## Repo Structure (suggested)
