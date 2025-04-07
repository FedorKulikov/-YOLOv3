# Face Detection and Blurring with YOLOv3

## Описание
Данный скрипт на Python обнаруживает лица на изображениях, видео и в потоке с веб-камеры с использованием модели глубокого обучения YOLOv3 (You Only Look Once) и применяет размытие для защиты приватности. Скрипт автоматически обрабатывает разные типы входных данных (веб-камера, изображения, видеофайлы) и выводит результат с размытыми лицами.

##  Возможности
Обнаружение лиц в реальном времени с веб-камеры

Обработка изображений (JPEG, PNG)

Обработка видеофайлов (MP4, AVI, MOV)

Высокая точность обнаружения благодаря YOLOv3

Защита приватности с помощью медианного размытия

Зеленые рамки вокруг обнаруженных лиц

## Требования
Python 3.x

OpenCV (pip install opencv-python)

YOLO weights file (yolov3-wider_16000.weights)

YOLO configuration file (yolov3-face.cfg)

Class names file (face.names)

## Веб-камера
```bash
python main.py --input 0
```

## Обработка изображения
```bash
python3 main.py --input <PATH_TO_IMAGE>
```
## Обработка видео
```bash
python main.py --input <PATH_TO_VIDEO>
```
## Примеры использования

# До:

![xATU2PqTp8oFkna0VycsG65fk7nt_SImrvOCOVK3RV_fBz4hFitXP7JjgAafk5NjTZ37Ie17pKSp5DzDUrSxHeEW](https://github.com/user-attachments/assets/fb5e3d33-c80e-47ed-89da-d83e82612862)


# После:

![nX5UnLIwpjg](https://github.com/user-attachments/assets/b9157e71-4388-4c92-9d52-435d5e1932d2)



