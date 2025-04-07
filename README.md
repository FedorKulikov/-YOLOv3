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

## Веб-камера
```bash
python main.py --input 0
```

## Обработка изображения
```bash
python main.py --input <PATH_TO_IMAGE>
```
## Обработка видео
```bash
python main.py --input <PATH_TO_VIDEO>
```
## Примеры использования

# До:

![xATU2PqTp8oFkna0VycsG65fk7nt_SImrvOCOVK3RV_fBz4hFitXP7JjgAafk5NjTZ37Ie17pKSp5DzDUrSxHeEW](https://github.com/user-attachments/assets/fb5e3d33-c80e-47ed-89da-d83e82612862)


# После:

![image](https://github.com/user-attachments/assets/12b7f2f9-f6ba-4c27-8c8d-07887cdff56d)


