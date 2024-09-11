# Transfer Learning Project  

##Описание  
Этот репозиторий посвящен проектам, связанным с использованием методов переноса обучения (Transfer Learning) для задач компьютерного зрения. В репозитории представлены различные подходы и модели, такие как:

* Перенос стилей с использованием нейросетей.  
* Работа с предобученными моделями IMAGENET.  
* Использование моделей VGG19 для решения задач классификации изображений.  
* Применение TFHub для загрузки и использования различных предобученных моделей.  
Проект демонстрирует, как можно эффективно использовать предобученные модели для решения задач на новых данных с минимальной дообучаемой настройкой.

## Структура проекта  

* Jupyter Notebook'и с примерами работы с нейросетями:
    - Style_Transfer.ipynb: Jupyter Notebook с реализацией переноса стилей между изображениями с использованием нейросетей.
      
* Пример использования предобученной модели IMAGENET для классификации изображений:  
    - GB_TL_IMAGENET.ipynb  
      
* Реализация дообучения модели VGG19 для классификации на кастомных данных:  
  - GB_TL_VGG19(unsuccessful).ipynb  
  - GB_TL_VGG19_ver2.ipynb  

* Работа с предобученными моделями через TensorFlow Hub:  
  - GB_TL_TFHub_ver_1.ipynb
  - GB_TL_TFHub_ver_2.ipynb
  - GB_TL_TFHub_ver_3.ipynb
    
* Основы работы с фреймворком Huggingface и библиотекой Transformers:  
  - GB_TL_Huggingface&Transformers.ipynb
  - GB_TL_Sentiment_Analysis.ipynb

* Исходные изображения используемые в проектах и результаты их преобразования:
  - 3d render, abstract pink blue neon background, cosmic landscape, northern polar lights, esoteric rectangular portal, virtual reality, ultraviolet spectrum, rocks.jpg
  - a person sitting on the ground reading a book.jpg
  - a red lantern in the middle of a park.jpg
  - an orange tree in a field with a blue sky in the background.jpg
  - result.png
  - silver baubles on red wall.jpg
  - stylized_image 2.jpg
  - stylized_image 3.jpg
  - stylized_image.jpg

## Используемые технологии
* PyTorch, TensorFlow и Keras: Основные библиотеки для работы с нейросетями.  
* TensorFlow Hub: Для загрузки и использования предобученных моделей.  
* VGG19 и IMAGENET: Предобученные модели для классификации изображений и переноса обучения.  

## Установка и запуск:  
1. Клонируйте репозиторий:

  ```git clone https://github.com/NickAllenov-DE/Transfer_Learning.git```

  
2. Установите необходимые зависимости:  

  ```pip install -r requirements.txt```
   
3. Откройте Jupyter Notebook:  

  ```jupyter notebook```
  
4. Откройте соответствующий файл .ipynb для изучения кода и выполнения примеров.  

## Примеры использования  
### Перенос стиля   
Запустите ноутбук Style_Transfer.ipynb, чтобы выполнить перенос стиля между двумя изображениями.  
Этот ноутбук использует CNN для захвата стиля одного изображения и применения его к другому.

### Классификация изображений
Ноутбуки GB_TL_IMAGENET.ipynb и GB_TL_VGG19_ver2.ipynb показывают, как дообучить предобученные модели для выполнения классификации изображений на новых данных.

## Контакты  
Автор: Николай Алленов  
Email: AllenovNS@gmail.com  
