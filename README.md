# Портфолио проектов по машинному обучению и нейросетям

Привет! 👋 Я увлекаюсь глубоким обучением, компьютерным зрением, NLP и смежными областями.

В этом репозитории собраны мои учебные проекты, выполненные в Google Colab.
Все ноутбуки можно открыть в один клик и сразу запустить (там, где это имеет смысл).

## 🧠 Ключевые навыки и инструменты

`Python` `PyTorch` `TensorFlow` `Keras` `Scikit-learn` `Hugging Face` `OpenCV` `YOLO` `GAN` `Autoencoders`
`Transformers` `GPT` `Reinforcement Learning` `Flask` `Streamlit` `pandas` `matplotlib` `Google Colab`

## 📂 Структура проектов

Проекты сгруппированы по типам задач. Кликнув по папке, вы попадёте в раздел, а по значку Colab — сразу откроете ноутбук в интерактивной среде.

### 🔤 NLP (обработка естественного языка)

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Fake News Detection** | Классификация фейковых новостей по заголовку и тексту | LSTM, BERT, TF-IDF | [📔 Ноутбук](nlp/fake_news_detection/Fake_news_Passive_Aggressive.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/fake_news_detection/Fake_news_Passive_Aggressive.ipynb) |
| **Author Identification** | Распознавание автора по отрывку текста | n-grams, TF-IDF, MLP | [📔 Ноутбук](nlp/author_identification/Author_identification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/author_identification/Author_identification.ipynb) |
| **GPT Headline Generator** | Дообучение GPT для генерации заголовков статей | GPT-2, Transformers | [📔 Ноутбук](nlp/gpt_headline_generator/GPT_headline_generator.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/gpt_headline_generator/GPT_headline_generator.ipynb) |
| **Сorporate documentation QA** | Нейро-сотрудник, отвечающий по документации | RAG, LlamaIndex | [📔 Ноутбук](nlp/corporate_documentation_qa/Data_пайплайн_и_поисковая_система_по_корпоративной_нормативной_документации.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/corporate_documentation_qa/Data_пайплайн_и_поисковая_система_по_корпоративной_нормативной_документации.ipynb) |
| **Google doc QA** | Нейро-сотрудник, отвечающий по базе знаний из гугл-документа | RAG, OpenAI | [📔 Ноутбук](nlp/google_doc_qa/Google_doc_QA.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/google_doc_qa/Google_doc_QA.ipynb) |
| **Telegram QA bot** | TG-бот нейро-сотрудник, отвечающий по базе знаний | RAG, OpenAI | [📔 Ноутбук](nlp/telegram_qa_bot/Telegram_QA_bot.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/nlp/telegram_qa_bot/Telegram_QA_bot.ipynb) |

### 📸 Computer Vision

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Dog Breed Classification** | Классификация пород собак по изображению | CNN, Transfer Learning (ResNet) | [📔 Ноутбук](computer_vision/dog_breed_classification/Dog_breed_classification.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/computer_vision/dog_breed_classification/Dog_breed_classification.ipynb) |
| **Watermark Removal Autoencoder** | Удаление водяных знаков с изображений | Autoencoder, U-Net | [📔 Ноутбук](computer_vision/watermark_removal_autoencoder/Watermark_removal_autoencoder.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/computer_vision/watermark_removal_autoencoder/Watermark_removal_autoencoder.ipynb) |
| **GAN comparison fashion** | Сравнения GAN, обученных на Fashion MNIST | Autoencoder, GAN | [📔 Ноутбук](computer_vision/gan_comparison_fashion/GAN_comparison_fashion.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/computer_vision/gan_comparison_fashion/GAN_comparison_fashion.ipynb) |
| **Lung segmentation Unet++** | Сегментация легких с использованием архитектуры Unet++ | Autoencoder, U-Net++ | [📔 Ноутбук](computer_vision/lung_segmentation_unet/Lung_segmentation_unet.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/computer_vision/lung_segmentation_unet/Lung_segmentation_unet.ipynb) |
| **Traffic sign detection** | Обнаружение дорожных знаков | YOLOv11, cv2 | [📔 Ноутбук](computer_vision/traffic_sign_detection/Traffic_sign_detection.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/computer_vision/traffic_sign_detection/Traffic_sign_detection.ipynb) |

### 📊 Табличные данные

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Parkinson’s Disease Detection** | Предсказание болезни Паркинсона по признакам | MLP, XGBoost, Feature Eng. | [📔 Ноутбук](tabular_data/parkinson_detection/Parkinson_detection.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/tabular_data/parkinson_detection/Parkinson_detection.ipynb) |
| **Сar price prediction** | Предсказание цены на японские автомобили в зависимости от характеристик | Pandas, MLP | [📔 Ноутбук](tabular_data/car_price_prediction/Car_price_prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/tabular_data/car_price_prediction/Car_price_prediction.ipynb) |
| **Mall customer clustering** | Распределение покупателей ТЦ по группам | Pandas, Autoencoder | [📔 Ноутбук](tabular_data/mall_customer_clustering/Mall_customer_clustering.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/tabular_data/mall_customer_clustering/Mall_customer_clustering.ipynb) |
| **Mushroom toxicity** | Определение токсичности гриба по его параметрам | Pandas, XGBoost | [📔 Ноутбук](tabular_data/mushroom_toxicity/Обнаружение_ядовитых_грибов.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/tabular_data/mushroom_toxicity/Обнаружение_ядовитых_грибов.ipynb) |

### ⏳ Временные ряды

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Apple Stock Forecast** | Прогнозирование котировок акций Apple | LSTM | [📔 Ноутбук](time_series/apple_stock_forecast/Apple_stock_forecast.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/time_series/apple_stock_forecast/Apple_stock_forecast.ipynb) |

### 🎮 Обучение с подкреплением

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Policy Gradient Atari** | Обучение агента игре в Atari через Policy Gradient | OpenAI Gym, PyTorch | [📔 Ноутбук](reinforcement_learning/policy_gradient_atari/Policy_gradient_Atari.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/reinforcement_learning/policy_gradient_atari/Policy_gradient_Atari.ipynb) |
| **Chess RL Comparison** | Сравнение алгоритмов RL в задаче игры в шахматы | DQN, BC, REINFORCE | [📔 Ноутбук](reinforcement_learning/rl_comparison_chess/Реализация_и_сравнение_алгоритмов_обучения_с_подкреплением.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/reinforcement_learning/rl_comparison_chess/Реализация_и_сравнение_алгоритмов_обучения_с_подкреплением.ipynb) |

### 🎨 Генеративные модели и нейроэволюция

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Chopin → Mozart Music Generation** | Генерация музыки в стиле Моцарта после обучения на Шопене | LSTM, pretty_midi | [📔 Ноутбук](generative_models/music_generation_chopin_mozart/Music_generation_Chopin_Mozart.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/generative_models/music_generation_chopin_mozart/Music_generation_Chopin_Mozart.ipynb) |

### 🎨 Генетические алгоритмы

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Genetic CNN/MLP** | Улучшение архитектур CNN и MLP генетическим алгоритмом | Keras, CNN, MLP| [📔 Ноутбук](neuroevolution/genetic_cnn_mlp/Genetic_CNN_MLP.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/neuroevolution/genetic_cnn_mlp/Genetic_CNN_MLP.ipynb) |

### 🚀 Деплой и сервисы

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **REST API for Neural Network** | Обёртка нейросети в REST API | FastAPI | [📔 Ноутбук](deployment/rest_api_neural_network/REST_API_neural_network.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaIvagin/ml-portfolio/blob/main/deployment/rest_api_neural_network/REST_API_neural_network.ipynb) |

## 🏆 Избранные проекты

- **Traffic Sign Detection YOLO11** — детекция дорожных знаков с современной версией YOLO.
- **Chess RL Comparison** — анализ алгоритмов RL в сложной среде.
- **Watermark Removal Autoencoder** — применение автоэнкодеров к реальной задаче.
- **Document QA (Neural Employee)** — два проекта нейро-сотрудников - ответы на вопросы из Google Doc и Word-файлов.

## 🚀 Как запустить любой ноутбук

1. Нажмите на кнопку **Open in Colab** рядом с проектом.
2. В Colab выберите: `Среда выполнения` → `Выполнить всё` (или `Среда выполнения` → `Сменить среду выполнения` для GPU/TPU).
3. Для зависимостей: в начале блокнота обычно прописаны `!pip install ...`.

## 📬 Контакты

Буду рад обратной связи и новым возможностям!

- LinkedIn:
- Email: niki4iv01@gmail.com
- tg: @minusov_ne_vizhu

## ⭐ Ещё кое-что

Если вам понравилось моё портфолио, поставьте звёздочку ⭐ этому репозиторию — мне будет приятно и полезно для роста.
