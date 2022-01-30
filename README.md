# NLU Final Project Report
Implementation of a BiLSTM-CRF in PyTorch to perform Named Entity Recognition.

Due to a bug in `sklearn_crfsuite`, a `scikit-learn` version `<0.24` must be used. The notebook will try to install it automatically.

In the repository there are saved models in the `models` directory; the notebook will load them and skip the training. If you want to retrain them you can simply delete them or rename them.
