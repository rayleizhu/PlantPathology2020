

* [sklearn Pipeline + GridSearchCV](https://scikit-learn.org/stable/tutorial/statistical_inference/putting_together.html)

## Keras ImageNet Preprocessing: 

* [source code](https://github.com/keras-team/keras-applications/blob/bc89834ed36935ab4a4994446e34ff81c0d8e1b7/keras_applications/imagenet_utils.py#L42)
* [example](https://www.tensorflow.org/tutorials/images/transfer_learning)


## Keras save best checkpoint
* https://stackoverflow.com/questions/48285129/saving-best-model-in-keras


## release gpu memory in jupyter notebook / kaggle kernel

I found several discussions:

* [Use multiprocessing](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/96876#593086) (not tried)

* [numba](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/96876) (will disable gpu)


* [del model + K.clear_session() + gc.collect()](https://forums.fast.ai/t/how-could-i-release-gpu-memory-of-keras/2023/19) (tried and works for me)


## sklearn BUG: fitting get stuck when using parallel processing for GridSearchCV + Pipeline 

Not compeletely sovled, but I found this only happens when I use specific preprocessing as part of the pipline (e.g. LSA, PCA)

* [Parallel jobs don't finish in scikit-learn's GridSearchCV](https://stackoverflow.com/questions/33042527/parallel-jobs-dont-finish-in-scikit-learns-gridsearchcv)


# reading list

* [marooncn/Defect-Detection-Classifier](https://github.com/marooncn/Defect-Detection-Classifier)

* [defect-detection - github](https://github.com/topics/defect-detection)