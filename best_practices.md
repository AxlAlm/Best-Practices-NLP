

# Data


## Dataset

### Preprocessed formats (CoNLL)
    Be weary of using dataset which come preprocessed. Although it might be convenient that part of all of the preprocessing is done its still the case that preprocessing can be important and hence something you want to make sure if correct and in controll of. Exampel of such format is ConLL. Sometimes the labels in some ConLL tasks are best predictions from previous tasks models which is maybe not the best to develop models upon.

    Even if we know where the preprocessed data is from and how its created it can still be important to implement those steps yourself to both for replication purposes, inference purposes and for comparison between preprocessing methods; e.g. does Stanza/CoreNLP, SpaCy or just a whitespace tokenizer yield the best result.

    An NLP system should always try to replicate a real-world-context, especiallly for evaluation. I.e. the input to the system should be as raw as possible.
    
### Data Augmentation

    - Translating sample to a language then back again can create weak paraphrasing.

    - 


# Deep Learning / Neural Networks


## Shuffling at epoch
    - Make sure you shuffle data at each epoch


## Layers

### RNNS

### CNNs

### Highway layers

### Utility layers


## Layer Dimensionality 

    - LSTM
        https://arxiv.org/pdf/1707.06799v2.pdf


## Activations



## Optimization and Learning Scheduling







## Training Tips

    - Early Stopping
        - Reduce overfitting

    - Gradient Clipping
        Useful in RNNS/LSTM
    
    - Learning Rate scheduling
        - Dynamic Learning rate which reduces based on how well model is learning can be very helpful

    - Dropout
        - reduce overfitting
        - prevent Features co-adapting (a feature can only be useful in the presence of a particular other feature??!?)
        - Many types of dropout, token dropout, word dropout, variational dropout, learned dropout.

    - Batch Normalization?

    - Weight/Paramater Averaging?
        https://pytorch.org/blog/pytorch-1.6-now-includes-stochastic-weight-averaging/
        https://arxiv.org/abs/1803.05407


## Metrics




# Features


## OOV
    

    - Create a vocabulary from a cropus which is not the Dataset itself. E.g. BNC or ...

    - Use Byte-Pair encoding vocabulary instead of token vocabulary


## Word Embeddings


    #### Fine-Tuning
    https://arxiv.org/pdf/2010.05006.pdf


## Byte Pair embeddings





# Segmentation Encoding Schems / Segment Representation Schemes


https://aclanthology.org/W09-1119.pdf
    
https://aclanthology.org/W15-5603.pdf

https://arxiv.org/pdf/1707.06799v2.pdf




# Evaluation and Statistical Significance Testing




# References
