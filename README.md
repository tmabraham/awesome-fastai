# Awesome fastai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[<img src="https://github.com/fastai/fastpages/blob/master/images/logo.png" align="right" width="100">](https://docs.fast.ai)
> A curated list of awesome projects and resources related [fastai](https://docs.fast.ai)

fastai is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches. 

> Note: Only resources that are related to fastai v2 are presented here.

---
## Contents
- [Libraries](#libraries)
- [Github Repositories](#github)
- [Kaggle Notebooks](#kaggle)
- [Articles](#articles)
- [Community](#community)
- [Other links](#other)

## Libraries

Libraries built with fastai.

### Computer Vision
- [UPIT](https://github.com/tmabraham/UPIT) - a fastai/PyTorch package for unpaired image-to-image translation
- [faststyle](https://github.com/lgvaz/faststyle) - aims to provide an easy and modular interface for image to image problems based on feature loss
- [IceVision](https://github.com/airctic/icevision) - an agnostic computer vision framework, pluggable to any training library 
- [SemTorch](https://github.com/WaterKnight1998/SemTorch) - brings state-of-the-art segmentation architectures into fastai

### Natural Language Processing
- [blurr](https://github.com/ohmeow/blurr/) - a library that integrates HuggingFace Transformers with version 2 of the fastai framework
- [fasthugs](https://github.com/morganmcg1/fasthugs) - use fastai-v2 with HuggingFace's pretrained transformers
- [AdaptNLP]() - a high-level framework and library for running, training, and deploying state-of-the-art NLP models for end-to-end tasks

### Medical Imaging
- [fmi](https://github.com/asvcode/fmi) - additional functionality for use with fastai’s medical imaging module
- [faimed3d](https://github.com/kbressem/faimed3d) - extension to fastai for volumetric medical data

### Fastai extensions
- [fastinference](https://github.com/muellerzr/fastinference) - a collection of inference modules for fastai2
- [fastai_minima](https://github.com/muellerzr/fastai_minima) - minimal fastai code needed for working with pytorch
- [walkwithfastai](https://github.com/walkwithfastai/walkwithfastai.github.io) - fastai extensions and techniques

### Other libraries
- [fastaudio](https://github.com/fastaudio/fastaudio) - an audio module for fastai v2
- [tsai](https://github.com/timeseriesAI/tsai) - state-of-the-art deep learning library for time series and sequences.
- [FasterAI](https://github.com/nathanhubens/fasterai) - a library to make smaller and faster models with fastai
- [self_supervised](https://github.com/KeremTurgutlu/self_supervised) - implementation of popular SOTA self-supervised learning algorithms as fastai callbacks

## Github Repositories<a name="github"></a>

Other Github repositories with useful fastai-related content.

- [fastbook](https://github.com/fastai/fastbook) - the Jupyter notebooks for the current edition of fastai book and course.
- [imagenette](https://github.com/fastai/imagenette) - a smaller subset of 10 easily classified classes from Imagenet, useful for quick prototyping.
- [FastAI.jl](https://github.com/FluxML/FastAI.jl) - a version of the fastai libary for the Julia language
- [Over9000](https://github.com/mgrankin/over9000) - different SOTA optimizers and fastai training script
- [fast_tabnet](https://github.com/mgrankin/fast_tabnet) - TabNet (SOTA neural network for tabular data) for fastai
- [ManifoldMixupV2](https://github.com/nestordemeure/ManifoldMixupV2) - Manifold-Mixup implementation for fastai v2
- [fastai-batch-size-finder](https://github.com/hal-314/fastai-batch-size-finder) - Implementation of OpenAI paper "An Empirical Model of Large-Batch Training" for fastai v2.

## Kaggle Notebooks<a name="kaggle"></a>

Kaggle Notebooks that use fastai. Feel free to fork them and interactively try them out. 

- [Cassava classification - fastai starter](https://www.kaggle.com/tanlikesmath/cassava-classification-eda-fastai-starter)
- [Petfinder Pawpularity - fastai starter](https://www.kaggle.com/tanlikesmath/petfinder-pawpularity-eda-fastai-starter)
- [SETI ET Signal Detection - fastai starter](https://www.kaggle.com/tanlikesmath/seti-et-signal-detection-a-simple-cnn-starter)
- [Combined fastai tabular+vision notebook](https://www.kaggle.com/muellerzr/fastai2-tabular-vision-starter-kernel)
- [HuBMAP PyTorch/fast.ai starter](https://www.kaggle.com/iafoss/hubmap-pytorch-fast-ai-starter)
- [fastai v2 Pipeline tutorial](https://www.kaggle.com/jhoward/fastai-v2-pipeline-tutorial)
- fastai medical imaging tutorials by Jeremy Howard:
  - [Creating a metadata DataFrame](https://www.kaggle.com/jhoward/creating-a-metadata-dataframe-fastai)
  - [Some DICOM gotchas to be aware of](https://www.kaggle.com/jhoward/some-dicom-gotchas-to-be-aware-of-fastai)
  - [DON'T see like a radiologist!](https://www.kaggle.com/jhoward/don-t-see-like-a-radiologist-fastai)
  - [Cleaning the data for rapid prototyping](https://www.kaggle.com/jhoward/cleaning-the-data-for-rapid-prototyping-fastai)
  - [From prototyping to submission](https://www.kaggle.com/jhoward/from-prototyping-to-submission-fastai)

## Articles

Some of the best articles regarding fastai and deep learning.

- [fastai: A Layered API for Deep Learning](https://arxiv.org/abs/2002.04688)
- [Pytorch to fastai, Bridging the Gap by Zach Mueller](https://muellerzr.github.io/fastblog/2021/02/14/Pytorchtofastai.html)
- [fastai and the New DataBlock API by Zach Mueller](https://muellerzr.github.io/fastblog/datablock/2020/03/21/DataBlockAPI.html)
- [The Idea of a Transform by Zach Mueller](https://muellerzr.github.io/fastblog/datablock/2020/03/22/TransformFunctions.html)
- [Keypoint regression with heatmaps in fastai v2 by Elte Hupkes](https://elte.me/2021-03-10-keypoint-regression-fastai)
- [fastai models to torch.jit by Habib Bukhari](https://drhb.github.io/blog/fastai/2020/03/22/Fastai-Jit.html)
- [Speeding Up fastai2 Inference - And A Few Things Learned by Zach Mueller](https://forums.fast.ai/t/speeding-up-fastai2-inference-and-a-few-things-learned/66179)

## Community

Online communities to discuss fastai.

- [fast.ai forums](https://forums.fast.ai) - the **OFFICIAL** fast.ai forums. Any fastai questions should ideally be asked here. Also check if your questions have already been addressed here by a previous post using the search functionality. Finally, feel free to share your work and projects here.
- [fast.ai Discord server](https://discord.gg/XnWJpQYgFn) - the **OFFICIAL** fast.ai Discord server. Useful for more informal discussion of fastai-related content, setting up and participating in study groups, and fastai library development.

## Other links<a name="other"></a> 

Other relevant links.

- [nbdev](https://nbdev.fast.ai) - Create delightful python projects using Jupyter Notebooks. fastai v2 is built with nbdev.
- [nbverbose](https://github.com/muellerzr/nbverbose) - An inplace extension on fastai's nbdev library to support documenting inputs
- [nbagile](https://github.com/muellerzr/nbagile) - making nbdev compatible for agile frameworks and developments
- [fastpages](https://fastpages.fast.ai) - An easy to use blogging platform with extra features for Jupyter Notebooks. A great blogging platform for you to share your fastai journey!
- [fast.ai course](https://course.fast.ai/) - the fastai deep learning course.
- [fastaidocs](https://www.cognitivefactory.fr/fastaidocs/) - a great set of cheatsheets for the fastai v2 API.


## Contribute

Contributions are welcome! Please submit a pull request with a single contribution only. 
