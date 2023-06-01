# «Глубокое обучение» (Deep Learning)
* образовательный проект по глубокому обучению
* лектор: [Александр Дьяконов](https://dyakonov.org/ag/)
* читался как кафедральный курс на факультете ВМК, МГУ имени М.В. Ломоносова для бакалавров 317 группа (2019-2022)
* часть лекций легла в основу курса программы ОзонМастерс / [AIMasters](https://aimasters.ru/)


### видео
плейлист с записями лекций: https://www.youtube.com/playlist?list=PLaRUeIuewv8BYOrm6HBgJKbGUD-jcBQpW

### эссе-конспекты
https://github.com/Dyakonov/DL/tree/master/ESSE_2021

### семинары
не выложены

[Вопросы для тестов](https://github.com/Dyakonov/BOOKs/blob/main/DLtest_Dyakonov.pdf)

### проекты студентов
не выложены

## темы 2022 года


| тема | видео | программа |
| :-- | :-- | :-- |
| [**Введение**](2022/DL_1NN_01intro_202203a.pdf) | [видео 1](https://youtu.be/7eQJ2WiKTIA), [видео 2](https://youtu.be/rqV0vR5lTUI) | Обзор достижений DL |
| [**Нейронные сети**](2022/DL_1NN_03_nn_202202a.pdf) | [видео 1](https://youtu.be/74o5xVgBdSk), [видео 2](https://youtu.be/XdyQj_BqGLw) | Простейшая нейросеть – 1 нейрон. Функции активации (линейная, пороговая, сигмоида, гиперболический тангенс, softmax, LeakyReLU, ELU, Maxout). Функциональная выразимость нейрона. Теорема об универсальной аппроксимации. Сеть прямого распространения. Обучение. Функции ошибки. Производные на компьютере. Проблема затухания градиента. Обратное распространение градиента.|
| [**Борьба с переобучением в нейронных сетях**](2022/DL_1NN_04learning_202201a.pdf)| [видео 1](https://youtu.be/xVJ5SUJt8cI), [видео 2](https://youtu.be/Zl08fzH3p8k) | Борьба с переобучением в нейронных сетях. Нормировки (Normalization of Data). Инициализация весов (Xavier initialization). Верификация – ранний останов (Early Stopping). Мини-батчи (mini-batches) / Batch-обучение. Продвинутая оптимизация (стохастический градиент с моментом (momentum), метод Нестерова, Adagrad, RMSprop, Adam, AdaDelta). Зашумление. Регуляризация + Weight Decay. Max-norm-регуляризация. Оптимизаторы. Dropout. Inverted Dropout. DropConnect. Обрезка градиентов (Gradient clipping). Батч-нормализация (Batch normalization). Расширение обучающего множества (Data Augmentation). Аугментация: Mixup. Ансамбль нейросетей. Диагностика проблем с НС. Кривые ошибок. Настройка темпа обучения. Transfer Learning. Упрощение НС (Pruning). Layer Normalization. Оптимизация гиперпараметров. Практические советы. |
| [**Свёрточные нейронные сети**](2022/DL_2CV_01cnn_202202a.pdf) | [видео](https://youtu.be/qWPNw4jw_WU) | Что такое изображение. Линейный подход к классификации на несколько классов. Свёрточные нейронные сети (ConvNet, CNN). Что такое свёртка (Convolution): глубина свёртки, отступ (Padding), шаг (stride), Dilation (расширение). 1×1-свёртки (Pointwise Convolutions).  Реализация свёртки. Разреженные взаимодействия (sparse interactions). Pooling (агрегация, субдискретизация / subsampling), виды пулинга, Pooling layer. Устройство слоя свёрточной НС, мотивация. Перевод тензора в тензор. Визуализация признаков. Полносвязный слой. Какие бывают свёртки: Spatial Separable Convolutions,  Group Convolutions, depth-wise convolution, Depth-wise separable convolution. Dropout в свёрточных сетях. |
| **Архитектуры свёрточных нейронных сетей** [**часть 1**](2022/DL_2CV_02archipart1_202201a.pdf), [**часть2**](2022/DL_2CV_03archipart2_202204a.pdf) | [видео 1](https://youtu.be/tLgaFjpMgxg), [видео 2](https://youtu.be/h8p72gUoX-o) | **часть 1 – чемпионы ImageNet и их «родственники»** LeNet, AlexNet, VGG, GoogLeNet / Inception, ResNet, Inception-v2-v4,SENet, Highway Net, Xception. ResNet: почему работает. Классические архитектуры в наши дни. **часть 2 – другие архитектуры** Network in Network (NiN),  Deep Networks with Stochastic Depth, FractalNet, Fractal of FractalNet, DenseNets, ResNeXt, MultiResNet, PolyNet, HyperNets,  EfficientNet, MobileNet,  SqueezeNet, ShuffleNet, FBNet (+NAS), WideResNets, RevNet, iRevNet, NFNets , ConvNeXt.|
| [**Визуализация нейронных сетей и генерация изображений**](2022/DL_2CV_07visualgeneration_202203a.pdf) | [видео 1](https://youtu.be/gpvG5nszwp4), [видео 2](https://youtu.be/N691CDDXDqs) | Зачем наблюдать? За чем можно наблюдать в NN? Визуализация весов: свёртки первого слоя. Визуализация весов / нейронов промежуточных слоёв: «deconvnet». Class Activation Maps (CAM). Guided Backpropagation. Interpretable Convolutional Neural Networks. Grad-CAM. Стандартные средства в признаковых пространствах. Анализ активации нейронов. Чувствительность к удалению (Occlusion sensitivity). «Saliency maps» – градиенты (их модули) по входу. Анализ отдельных нейронов / каналов / слоёв: Class Model Visualisation. Нейроискусство. исследование нейронов, семантические словари. Современные методы: FullGrad. Генерация изображений. Генерация текстур. Генерация пейзажей. Стилизация (перенос стиля). Быстрая стилизация. |
| [**Рекуррентные нейросети**](2022/DL_3NLP_01rnn_202203a.pdf) | [видео 1](https://youtu.be/mxXAwV-8w74), [видео 2](https://youtu.be/TyRcJ113bEo) | RNN (базовый блок). RNN: обучение. RNN: как решать задачи классификации. LSTM. Забывающий гейт (Forget Gate). Входной гейт (Input Gate). Обновление состояния (Cell update). Выходной гейт (Output Gate). Gated Recurrent Unit (GRU). Метод форсирования учителя (teacher forcing). Scheduled sampling. Двунаправленные (Bidirectional) RNN. Глубокие (Deep) RNN. Глубокие двунаправленные RNN. Многонаправленные RNN. Пиксельные RNN. Рекурсивные (Recursive Neural Networks) НС. Exploding / Vanishing gradients. Особенности регуляризации в RNN: Dropout. Особенности регуляризации в RNN: Batchnorm. MI (Multiplicative Integration). Интерпретация LSTM: Sentiment neuron. Применение RNN.  |
| [**Анализ текстов**](2022/DL_3NLP_02texts_202203a.pdf)  | [видео](https://youtu.be/_ijVRGbfcmE)  | Задачи с текстами. Данные. Понимания языка (Language Understanding). Свёрточные модели для текста. Dynamic Convolutional Neural Network. Very Deep Convolutional Networks for Text Classification. Сравнение CNN vs RNN. CNN + LSTM = C-LSTM. CNN + LSTM = LSTM-CNNs-CRF. Модель seq2seq. Обобщения seq2seq. Механизм внимания. Виды внимания. |
| [**Векторные представления слов и текстов**](2022/DL_3NLP_03embeddings_202206a.pdf) | [видео 1](https://youtu.be/VhXY-neJfPY), [видео 2](https://youtu.be/6I7dqJC3tb4)  | Способы представления слов: классические: OHE, counts, LSA, кластеризация, LDA. Вложение слов в непрерывное пространство (embedding). word2vec: CBOW, skip-gram. Negative Sampling. Ближайшие соседи. Операции над представлениями слов. Fasttext. Glove: Global Vectors for Word Representation. Contextualized Word Embeddings. Embeddings in Tag LM. CoVe = Contextual Word Vectors. ELMo: Embeddings from Language Models. FLAIR: Contextual String Embeddings for Sequence Labelling. Представление текстов. Distributed Memory Model of Paragraph Vectors (Doc2Vec / paragraph2vec). The skip-thoughts model. Предтренировка автокодировщика (Autoencoder pretraining). Supervised sentence embeddings. StarSpace. Deep Averaging Network (DAN). Universal Sentence Encoder. DSSM. Случайный кодировщик. InferSent – Supervised sentence embedding. SentenceBERT. TSDAE: предтренировка трансформера без меток с шумоподавляющем автокодировщиком. BERTScore – оценка схожести предложений. Бонус: сексизм в представлениях. |
| [**Трансформер**](2022/DL_3NLP_04transformer_202204a.pdf) | [видео 1](https://youtu.be/92H34uokUl4), [видео 2](https://youtu.be/H9Vvq73-3Kg)  | attention / self- attention – матричная запись. Transformer: Основная идея «Parallelized Attention». Transformer: виды внимания. Особенности обучения трансформера. BERT = Bidirectional Encoder Representations from Transformers. RoBERTa: A Robustly Optimized BERT Pretraining Approach. SpanBERT. ALBERT = A Lite BERT. T5: Text-To-Text Transfer Transformer. ELECTRA = Efficiently Learning an Encoder that Classifies Token Re-placements  Accurately. |
| [**Языковые модели**](2022/DL_3NLP_06languagemodel_202204a.pdf) | [видео 1](https://youtu.be/UgYQPZ47554), [видео 2](https://youtu.be/ysvvAqQjnPw)  | Моделирование языка (Language Modeling). Параметрическое оценивание. Немарковские модели. RNN-моделирование языка. Подходы к генерированию. Beam Search (метод луча). ULMfit. ERNIE (Enhanced Representation through kNowledge IntEgration). GPT / GPT-2 / GPT-3. Нейронная дегенерация текстов. Стратегии семплирования. Unlikelihood training. Извлечение обучающих данных (на примере GPT-2). |
| [**Трансформеры++ (Эффективные трансформеры)**](2022/DL_3NLP_05transformer++_202209a.pdf) | [видео](https://youtu.be/VnUBs9osoxw)  | Позиционное кодирование. Relative Position Representations. Transformer with Untied Positional Encoding (TUPE). Transformer-XL. Compressive Transformer. Universal Transformer. Adaptive Attention Span. Expire-Span Transformer. Memory Transformer. Star-Transformer. Extended Transformer Construction (ETC). Longformer. BigBird. BART: шумоустраняющий seq2seq-автокодировщик на базе seq2seq-трансформера. Sparse Transformer. Reformer: The Efficient Transformer. Routing Transformer. Sinkhorn Transformers. Linear Transformer. Linformer |
| [**Генерация текстов (NLG)**](2020/DL2020_046tokenNLG_09n.pdf) (старая версия слайдов) | [видео](https://youtu.be/gMtfyVoqBh4) (только первой части) | Представление слов: - токенизация на подслова (byte-pair encoding (BPE), wordpiece, unigram language model, sentencepiece), - посимвольный подход (представления слов из анализа символов, Compositional Character Model, Character-Aware NLM), - гибридный подход (действуем на уровне слов, если надо – на уровне символов, Compositional Character Model, 	Character-Aware NLM). С(у/а)ммаризация текста: - seq2seq-подход / + attention, - Pointer-Generator Networks, - Bottom-up summarization, - NLG + RL, - simplification: DRESS (Deep REinforcement Sentence Simplification). Extractive summarization: SummaRuNNer. Abstractive Summarization: TCONVS2S. Суммаризация с BERT: BertSum. Диалоги. Рассказ историй: Storytelling. Рассказ историй по тексту: Hierarchical Neural Story Generation. Генерация поэзии: Hafez, Deep-speare. Проблемы метрики качества для саммаризации / диалогов / описания. Coreference Resolution. Coreference Resolution: Clustering-Based. |
| [**Pytorch**](2022/DL_1NN_10pytorch_202302.pdf) | [видео 1](https://youtu.be/tDJnwc8Hioc), [видео 2](https://youtu.be/c3y--ydWku0)  | Тензоры. Предобработка данных, нейросети |
| [**Детектирование объектов на изображениях**](2020/DL2020_033objectdetection_06n.pdf) | [видео 1](https://youtu.be/6yGXpZmbcA4), [видео 2](https://youtu.be/OrrbaYr3pck) |  Задачи с изображениями: Классификация, Локализация, Детектирование, Сегментация, Преобразование изображений, Восстановление объектов. Классификация изображений – почему нетривиальная задача, решение, проблемы. Детектирование объектов: R-CNN, Spatial Pyramid Pooling (SPP-net), Fast R-CNN, Faster R-CNN, YOLO, SSD. Selective Search. Метрики качества. Non Maximum Suppression (NMS). Сегментация объектов: Mask R-CNN. Feature Pyramid Networks (FPN). Детектирование объектов: R-FCN. FCOS: Fully Convolutional One-Stage Object Detection. |
| [**Сегментация изображений**](2020/DL2020_034segmentation_06n.pdf) | [видео](https://youtu.be/LtaxVmG3Gjo) | Семантическая сегментация: приложения, меры качества, датасеты. Elastic Transform. Классические методы сегментации: кластеризация по цвету. Классические методы сегментации: условные случайные поля (CRF). Классические методы сегментации: графовые методы. Гибридный метод: DL + CRF. Полностью свёрточная сеть – Fully Convolutional Network (FCN). Deconvolution Network. Segnet. U-Net. Тирамису. V-Net. TernausNet. Unet++. GridNet. Расширенные свёртки (Dilated convolutions / Atrous Convolutions). DeepLabv1/2/3/3+. FastFCN. PSP-Net. SharpMask. High-Resolution Representations. Сети с вниманием: DANet. Виды сегментации: семантическая, объектов, паноптическая. Mask R-CNN. |
| [**Самообучение**](2020/DL2020_055selfSV_20n.pdf) | [видео часть 1](https://youtu.be/2i5ZIrFpw5o) |  Self-Supervised Learning: pretext task, downstream task, что такое предствление. Predicting  (spatial) context. Predicting image  rotation. Exemplar. Головоломка (Jigsaw). Кластеризация (DeepCluster). Контекстные кодировщики (Context Encoder) / image inpainting. Раскраска изображений (image colorization). Расщеплённые автокодировщики (Split-brain  autoencoders). Сегментация, порождённая движением (motion segmentation prediction). Разметка окружающими звуками (ambient sounds). Подсчёт примитивов (counting visual primitives). Multi-task Self-Supervised Visual Learning. Temporal coherence of color. Temporal Context-based Learning. Исследование архитектур для самообучения|
| [**Обучение без учителя**](2020/DL2020_051unsup_08n.pdf) |  [видео часть 1](https://youtu.be/F6SllsSVgY8), [видео часть 2](https://youtu.be/iLU9D_mRZ3o) | Автокодировщики (Auto-encoders). Глубокие автокодировщики. Denoising Autoencoder. Сокращающие автокодировщики – Contractive Autoencoders (CAE). Предобучение с помощью автокодировщика (раньше так делали). Sparse Coding. Context Encoders. Использование RBM. Глубокие RBM (Deep Boltzmann Machines). SOM – Самоорганизующиеся карты Кохонена. Сжатие. Генеративная модель. Проблема оценки плотности. Решения для оценки плотности. Авторегрессионные модели. Masked Autoencoder for Distribution Estimation (MADE). Masked Temporal (1D) Convolution. Masked Spatial (2D) Convolution: PixelCNN, PIXELCNN++, PixelSNAIL, PixelRNN. Masked Attention + Convolution. Поток (Glow): real NVP, Glow. Авторегрессионные потоки (Autoregressive Flows) |
| [**Вариационный автокодировщик**](2020/DL2020_052vae_06n.pdf) |  [видео](https://youtu.be/0BC-J9EA-v8) |  Генеративная модель. Variational Autoencoders (VAE). Variational Bayesian Inference. Reparametrizaton trick. Векторная арифметика. Conditional VAE (CVAE). Ladder Variational Autoencoders. Bidirectional-Inference Variational Autoencoder (BIVA). Vector Quantised-Variational AutoEncoder (VQ-VAE). VQ-VAE-2. VAE: Image Colorization. VAE: Forecasting from Static Images. Adversarial Autoencoder. |
| [**Генеративные состязательные сети**](2020/DL2020_053gan_13n.pdf) | [видео](https://youtu.be/obY2JIYAHZk) | Генератор и дискриминатор. Что могут GAN. Adversarial idea. GAN: обучение – min-max-игра. Настройка GAN, советы по настройке GAN. Нестабильность «non-saturating  game». GAN: первые примеры. Обучение GAN: проблемы на практике. Least Square GAN (LSGAN). Hinge loss based GAN. Wasserstein GAN (WGAN). WGAN-GP. Спектральная нормировка (Spectral Normalization): SN-GAN. Maximum Mean Discrepancy (MMD). f-GAN. Relativistic GANs (RGANs). GAN: проблемы – Mode-Collapse. Energy-Based GAN (EBGAN). Как оценивать качество (сгенерированные картинки): Inception score (IS), Mode score (MS), Fr ́echet Inception Distance (FID), Structural similarity (SSIM). Kernel MMD (Maximum Mean Discrepancy). The Wasserstein distance. The 1-Nearest Neighbor classifier. Сравнение метрик качества| 
| [**Генеративные состязательные сети - часть 2**](2022/DL_4UL_04gan2_202301.pdf) | [видео 1](https://youtu.be/wpezm6o8EtM), [видео 2](https://youtu.be/xulKmbotPNA) | Deep Convolutional Generative Adversarial Networks (DCGAN). Условные состязательные сети (сGAN). Pix2pix c условными состязательными сетями (сGAN). pix2pixHD. Проблема отсутствия выборки - CycleGAN. Аугментированная циклическая GAN (Augmented CycleGAN. BiGAN (Bidirectional). BigGAN: Генерация изображений / интерполяция. BigBiGAN = BiGAN + BigGAN. SAGAN (Self-Attention Generative Adversarial Networks). Semi-supervised GAN (SGAN). AC-GAN: auxiliary classifier GAN. CAN: Creative Adversarial Networks. ProGAN (NVIDIA). InfoGAN. Условные GANы (Conditional GANs). Coupled GANs. | 
| [**Генеративные модели: итоги**](2022/DL_4UL_05genlast_202302.pdf) | [видео 1](https://youtu.be/zgBARc5dRKI) | Conditional GANs: Text-to-Image Synthesis. StackGAN: описание 2 изображение. Задача трансляции изображений. MUNIT: идея пространств контента и стиля. Instance Normalization. FUNIT (NVIDIA, 2019). Немного про перенос стиля: AdaIN. StyleGAN – перенос стиля. StyleGAN2: избавление от артефактов. FSGAN – замена лиц. VAE + GAN. Adversarial Autoencoders (AAE). Wasserstein Auto-Encoders. GAN приложения: редактирование. GAN приложения: DCGAN / суперразрешение. GAN приложения: изменение позы. | 
















Следующие лекции (пока без видео):

| тема | программа |
| :-- | :-- |
| [**CNN: дополнение**](2020/DL2020_037priorcolor_03n.pdf) | Дистилляция данных. Базовый алгоритм. Мягкая дистилляция. Дистилляция табличных данных. Deep image prior (DIP). Раскраска изображений. (старая версия слайдов) |
| [**Машинный перевод с помощью НС (Neural Machine Translation)**](2020/DL2020_047NMT_09n.pdf) | Особенности нейросетевого перевода. Метрика качества в переводе и саммаризации: BLEU (Bilingual Evaluation Understudy), GLEU (Google-BLEU), ROUGE: Recall-Oriented Understudy for Gisting Evaluation, METEOR: Metric for Evaluation of Translation with Explicit ORdering, TER (Translation Edit Rate), SARI: System output against references and against the input sentence. Подходы к NMT: Seq2seq, Attention, The Transformer model, Ансамблирование. Convolutional Sequence to Sequence Learning (ConvS2S). GNMT (Google’s Neural Machine Translation System). RNMT+. Языковая модель в NMT. Использование нескольких языков. Редкие пары языков. Проблемы переводчика. |



Следующие лекции (пока без слайдов):

| тема | программа |
| :-- | :-- |
| **Нейронные сети: трюки** | Проблема калибровки. Непараметрические методы калибровки. Решение проблемы дисбаланса классов. Взвешивание. В случайных нейронных сетях есть хорошие подсети. Transfer learning / Адаптация данных (Domain adaptation). Pseudo labelling. |
| **Упрощение сетей** | Распараллеливание. Сжатие (compression) и увеличение скорости (speedup). NAS. Network Prunning. Дистилляция знаний (Knowledge distillation). |
| **Теория и интересные эффекты** | Изменение темпа обучения. Паттерны в данных. Минные поля. Геометрия глобальных минимумов. Двойной спуск. |
| **Lifelong Machine Learning / Continual learning** | Catastrophic forgetting. Неспособность к обобщению. Lifelong Machine Learning / Continual learning. Слабо-размеченные данные. Теория аугментации. Виды multitask. |
| **Надёжность (робастность) нейронных сетей / Состязательные атаки** | ... |
| **Поиск изображений** | Сиамские сети, Triplet Loss. Сиамские сети: Person Re-Identification. Сиамские сети: Street-View to Overhead-View Image Matching. Сиамские сети: Intermediate merging. Сиамские сети: for viewpoint invariance. Сиамские сети:  for cross-modal embedding. FaceNet. |
| **Visual Transformer** | Image Transformer. Sparse Transformer. Image GPT (iGPT). Axial Transformer. Vision Transformer (ViT). Data-efficient image Transformer (DeiT). Bottleneck Transformers (BoTNet). Vision MoE (V-MoE). Image Processing Transformer (IPT). Detection Transformer (DETR). TransGAN. Swin Transformer. Swin Transformer V2. |
| Дифференцируемые структуры памяти. | Дифференцируемые структуры памяти. Neural Turing Machines. Pointer Network. Discrete Read/Write: Reinforcement L.earning Neural Turing Machines. Memory Network «MemN2N». KV-MemNN. |
| Аугментация для текстов | ... |
| Чат-боты | Термины. Meena (Google). Turing-NLG. BlenderBot (Facebook). Switch Transformers. Heterogeneous Graph Transformer. DialoGPT. ConveRT. REALM |
| Обучение с частичной разметкой | .... |
| **Звук и речь** | Что такое звук. Сложности в анализе звука. Задачи со звуком. Признаки в анализе звуков. Генерация признаков. Windowing. Discrete Fourier Transform (DFT). Человеческое восприятие – Nonlinear frequency scaling. mel-scale. Log Mel Power Spectrum. MFCCs = Mel-frequency cepstral coefficients. Cepstral Analysis. PLP = Perceptual Linear Prediction. Dynamic features. PCEN = Per-Channel Energy Normalization. MFCC vs FBANK. Тандемные модели (Tandem models). Музыкальный поиск. |
| **Распознавание речи: классический подход** | Автоматическое распознавание речи Automatic Speech Recognition (ASR). История ASR. WER = Word Error Rate. Мир коммерческих решений в распознавании речи. Свободные системы распознавания речи. CMU Sphinx. PocketSphinx. Kaldi. Mozilla DeepSpeech. Акустическая и лингвистическая модели. Языковая модель (Language Model). Архитектура ASR. Декодирование. Извлечение признаков. Lexical model. Hidden Markov Models and Gaussian Mixture Models. Проблемы контекста. Термины: Monophones, Triphones, Senones.Decision Tree-based State Clustering. HMM-DNN. Time-delay neural networks (TDNNs). TDNN-F. Feed-forward  sequential  memory  networks (FSMN). Model Objective function. From SENONES to CHENONES. |
| **Распознавание речи: end2end-подход** | Напрашивающиеся нейросетевые подходы. CTC (Connectionist Temporal Classification). Разметка (Alignment). RNN-transducer. Listen, Attend and Spell (LAS). Attention-based models. Deep Fusion, Cold Fusion. Spelling correction модель. Wav2Letter. Wav2Letter++. CAPIO. |
| **Синтез речи** | Вокодеры, модели, контекст |
| **Metric Learning** | Contrastive Loss. Triplet Loss. Quadruplet Loss. Structured Loss. Center Loss. Modified SoftMax Loss. SphereFace (A-softmax). CosFace (LMCL). ArcFace. |
| **Капсульные сети** | ... |
| **Графовые НС** | Представление графа. Нейронное распространение (Neural Message Passing). GraphSAGE. PinSage. Generalized Neighborhood Aggregation. Neighborhood Attention: Graph Attention Network (GAT). DEEPGCNS. Jumping Knowledge Connections. Graph Pooling. Использование GNN. Генеративные графовые модели. GGNN (GATED GRAPH NEURAL NETWORKS).  |



# конец

