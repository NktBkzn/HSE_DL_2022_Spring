#  Deep Learning HSE весна 2022


### Полезные ресурсы
* Если вы хотите скачать из репозитория конкретную папку или файл, просто вставьте ссылку на неё в [сервис для скачивания](https://minhaskamal.github.io/DownGit/#/home?url=). 

### Домашние задания
| №      | Название                               | Задание                                  | Срок     |
| :---:  |:-------------------------------------  | :--------------------------------------  | :------: |
| 1      | HW01_intro_classification_pytorch.ipynb| Внизу ноутбука расписано по пунктам      | 22.04.22 |
| 2      | HW02_gradient.ipynb                    | Реализовать градиентный спуск            | 29.04.22 |
| 3      | HW03_Weather_forecast_RNN.ipynb        | Обучить RNN                              | 05.06.22 |
| 4      | HW04_Attention_basics.ipynb            | Реализовать вариации Attention           | 14.06.22 |


### Программа курса + ссылки на хорошие материалы по теме
#### Полносвязные сети
01. Введение в нейросети
02. Адаптивные варианты градиентного спуска
   - [Почему momentum работает](https://distill.pub/2017/momentum/)
   - [Bias correction in Adam](https://www.youtube.com/watch?v=-0ZMU-gnm2g)
   - Новомодный optimizer [AdamW](https://arxiv.org/pdf/1711.05101.pdf)
   - [Cyclical Learning Rate](https://medium.com/swlh/cyclical-learning-rates-the-ultimate-guide-for-setting-learning-rates-for-neural-networks-3104e906f0ae)
03. Алгоритм обратного распространения ошибки
04. Инструменты в Python для обучения нейронных сетей
   - [Dataloader/Dateset в PyTorch](https://discuss.pytorch.org/t/making-iterable-objects-using-torch-utils-data-dataloader/16681/2)
   - [Weight initialization](https://www.deeplearningwizard.com/deep_learning/boosting_models_pytorch/weight_initialization_activation_functions/)
   - [Python generators](https://realpython.com/introduction-to-python-generators/)
   - [Iterators vs Generators](https://stackoverflow.com/questions/2776829/difference-between-pythons-generators-and-iterators)
05. Батч-нормализация. Инициализация. Эвристики для обучения сетей
   - [BatchNorm explained](https://towardsdatascience.com/batch-normalization-in-3-levels-of-understanding-14c2da90a338)
   - [Custom weight decay](https://raberrytv.wordpress.com/2017/10/29/pytorch-weight-decay-made-easy/)
   - [Inverted dropout](https://www.coursera.org/lecture/deep-neural-network/dropout-regularization-eM33A)
#### NLP
06. Введение в NLP, Word2Vec, Эмбеддинги
   - [MLE explained](https://towardsdatascience.com/probability-concepts-explained-maximum-likelihood-estimation-c7b4342fdbb1)
   - [Супер NLP guide от Lena Voita](https://lena-voita.github.io/nlp_course.html)
   - [Word2Vec tutorial с математикой и кодом](https://github.com/Yorko/mlcourse.ai/blob/main/jupyter_russian/tutorials/word2vec_demonzheg.ipynb)
07. Рекуррентные нейросети: RNN, LSTM, GRU
   - Stanford CS224N [all lectures](http://web.stanford.edu/class/cs224n/slides/). [Slides on RNN](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture07-fancy-rnn.pdf)
   - [NLTK book](https://www.nltk.org/book/)
   - [Variants of dropout](https://towardsdatascience.com/12-main-dropout-methods-mathematical-and-visual-explanation-58cdc2112293). Pay attention to RNN part
   - [Deep RNNs](https://www.coursera.org/lecture/nlp-sequence-models/deep-rnns-ehs0S)
08. Seq2seq, Attention, ELMO
   - [BERT, ELMO explained](https://jalammar.github.io/illustrated-bert/)
   - [spaCy vs NLTK vs gensim](https://www.kaggle.com/faressayah/nlp-with-spacy-nltk-gensim)
09. Self-Attention. Transformer. BERT.
   - [Transformers explained](https://jalammar.github.io/illustrated-transformer/)
   - [BERT, ELMO explained](https://jalammar.github.io/illustrated-bert/)
   - [Why BERT is called bidirectional?](https://medium.com/dissecting-bert/dissecting-bert-part2-335ff2ed9c73)
   - [Harvard transformer implementation](http://nlp.seas.harvard.edu/2018/04/03/attention.html)