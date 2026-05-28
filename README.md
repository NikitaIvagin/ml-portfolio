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
| **Dog Breed Classification** | Классификация пород собак по изображению | CNN, Transfer Learning (ResNet) | [📔 Ноутбук](computer_vision/dog_breed_classification/dogs.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| **Watermark Removal Autoencoder** | Удаление водяных знаков с изображений | Autoencoder, U-Net | [📔 Ноутбук](computer_vision/watermark_removal_autoencoder/watermark.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| ... | | | |

### 📊 Табличные данные

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Parkinson’s Disease Detection** | Предсказание болезни Паркинсона по голосовым признакам | MLP, XGBoost, Feature Eng. | [📔 Ноутбук](tabular_data/parkinson_detection/parkinson.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| ... | | | |

### ⏳ Временные ряды

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Apple Stock Forecast** | Прогнозирование котировок акций Apple | LSTM, Prophet | [📔 Ноутбук](time_series/apple_stock_forecast/stock.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |

### 🎮 Обучение с подкреплением

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Policy Gradient Atari** | Обучение агента игре в Atari через Policy Gradient | OpenAI Gym, PyTorch | [📔 Ноутбук](reinforcement_learning/policy_gradient_atari/atari.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| **Chess RL Comparison** | Сравнение алгоритмов RL в задаче игры в шахматы | DQN, A2C, Stable Baselines | [📔 Ноутбук](reinforcement_learning/chess_rl_comparison/chess_rl.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |

### 🎨 Генеративные модели и нейроэволюция

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **Chopin → Mozart Music Generation** | Генерация музыки в стиле Моцарта после обучения на Шопене | LSTM, Music21 | [📔 Ноутбук](generative_models/music_generation_chopin_mozart/music.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| **Genetic CNN/MLP** | Улучшение архитектур CNN и MLP генетическим алгоритмом | PyGAD, Keras | [📔 Ноутбук](neuroevolution/genetic_cnn_mlp/genetic.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |

### 🚀 Деплой и сервисы

| Проект | Описание | Технологии | Ссылки |
|--------|----------|------------|--------|
| **REST API for Neural Network** | Обёртка нейросети в REST API | Flask, Docker | [📔 Ноутбук](deployment/rest_api_neural_network/api.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| **Telegram QA Bot** | Бот, отвечающий на вопросы по пользовательской базе знаний | LangChain, Chroma, aiogram | [📔 Ноутбук](nlp/telegram_qa_bot/bot.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](...) |
| ... | | | |

## 🏆 Избранные проекты

- **Traffic Sign Detection YOLO11** — детекция дорожных знаков с современной версией YOLO.
- **Chess RL Comparison** — анализ алгоритмов RL в сложной среде.
- **Watermark Removal Autoencoder** — применение автоэнкодеров к реальной задаче.
- **Document QA (Neural Employee)** — два проекта нейро-сотрудников - ответы на вопросы из Google Doc и Word-файлов.

## 🚀 Как запустить любой ноутбук

1. Нажмите на кнопку **Open in Colab** рядом с проектом.
2. В Colab выберите: `Среда выполнения` → `Выполнить всё` (или `Среда выполнения` → `Сменить среду выполнения` для GPU/TPU).
3. Для зависимостей: в первой ячейке обычно прописаны `!pip install ...`, либо в папке проекта есть `requirements.txt`.

## 📬 Контакты

Буду рад обратной связи и новым возможностям!

- LinkedIn:
- Email: niki4iv01@gmail.com

## ⭐ Ещё кое-что

Если вам понравилось моё портфолио, поставьте звёздочку ⭐ этому репозиторию — мне будет приятно и полезно для роста.
