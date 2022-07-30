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
| 5      | HW05_Autorncoder_manifold (в семинарах)| Реализовать Conv Autoencoder             | 29.07.22 |

### Программа курса + ссылки на хорошие материалы по теме
#### Feedforward NNs
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
#### CV
10. Свёрточные нейронные сети
   - [Convolution in CNN explained](https://www.youtube.com/watch?v=KTB_OFoAQcc)
   - [Dilated convolutions](https://www.inference.vc/dilated-convolutions-and-kronecker-factorisation/)
11. Transformers practice
   - [Описание различных tokenizers](https://huggingface.co/docs/transformers/tokenizer_summary)
   - [Эффективное использование GPU](https://huggingface.co/docs/transformers/perf_train_gpu_one)
12. Transfer learning
   - [ResNet](https://towardsdatascience.com/understanding-and-visualizing-resnets-442284831be8)
   - [1x1 convolution](https://stats.stackexchange.com/questions/194142/what-does-1x1-convolution-mean-in-a-neural-network)
13. Интерпретация свёрточных нейронных сетей. Перенос стиля
   - [Что выучивает сеть?](https://towardsdatascience.com/understanding-your-convolution-network-with-visualizations-a4883441533b)
   - [Перенос стиля](https://towardsdatascience.com/neural-style-transfer-applications-data-augmentation-43d1dc1aeecc) 
14. Autoencoders. Manifold learning
   - [Transpose Convolutions and Autoencoders](https://www.cs.toronto.edu/~lczhang/360/lec/w05/autoencoder.html)
   - [Denoising Autoencoders](https://medium.com/@garimanishad/reconstruct-corrupted-data-using-denoising-autoencoder-python-code-aeaff4b0958e)
   - [Unsampling: Unpooling and Transpose Convolution](https://medium.com/jun-devpblog/dl-12-unsampling-unpooling-and-transpose-convolution-831dc53687ce)
   - [Что такое manifold. Интуиция, стоящая за этим понятием](https://bjlkeng.github.io/posts/manifolds/)
   - [Manifold learning и скрытые переменные](https://habr.com/ru/post/331500/)
   - [Manifold learning on MNIST -> 2D-representation learned by an autoencoder](https://www.kaggle.com/apapiu/manifold-learning-and-autoencoders/notebook)
15. Генеративно-состязательные сети
   - [GAN explained](https://www.coursera.org/learn/build-basic-generative-adversarial-networks-gans/lecture/gIAJ0/putting-it-all-together)
   - [Deconvolution issue. Checkerboard](https://distill.pub/2016/deconv-checkerboard/)
   - [VAE ultimate guide & intuition](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)
16. Свёрточные сети для текстов
   - [Лекция от МФТИ](https://www.youtube.com/watch?v=egvX1wGCKSg&list=PL4_hYwCyhAvY7k32D65q3xJVo8X8dc3Ye&index=3)
   - [Text Classification using CNN, RNN](https://medium.com/jatana/report-on-text-classification-using-cnn-rnn-han-f0e887214d5f)
   - [CNN for Sentence Classification, Kim paper](https://arxiv.org/pdf/1408.5882.pdf)
