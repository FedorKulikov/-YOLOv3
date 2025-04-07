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

![face_before](https://github.com/user-attachments/assets/ba5c6cdf-4630-4012-a2fd-667ece5f7f48)

# После:

![face_after](https://github.com/user-attachments/assets/d49bc22b-2f9b-4dc3-b84c-b638dcf4e94d)




