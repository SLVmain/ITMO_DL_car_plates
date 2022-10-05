# ITMO_DL_in_practice_01
ITMO practice course

Выложены три блокнота jupiter Notebook с проектом "Распознавание российских номеров машин с видео".

Данные взяты отсюда: https://www.kaggle.com/competitions/vkcv2022-contest-02-carplates 

Это открытая база фото автомобилей с российскими номерами, 25 тысяч изображений, 
для выполнения задачи в дальнейшем случайным образом отобраны 2500 (2000 трейн и 500 валидация).

Очередность блокнотов:
1. f_2_1_plates_YOLO_annotations.ipynb - предобработка данных.
2. f_2_2_YOLO5S_Training_small_data.ipynb - дообучение YOLO на кастомном датасете.
3. f_2_3_yolo5S_plates_inference.ipynb - инференс модели на фото и видео.

Все блокноты воспроизводимые, данные в каждый блокнот подкачиваются прямыми ссылками с yandex диска, 
можно без проблем запускать в google colab.

Реализовано:

1. Детекция номеров с помощью YOLO5S.
2. Распознавание с помощью EasyOCR.

проведены эксперименты с несколькими моделями и параметрами
https://docs.google.com/spreadsheets/d/1K45Hrr3hAPtBvtdRnDXMV9NgRklXNdicz9WxE4VpS7Y/edit?usp=sharing

результирующее видео с распознаванием
https://disk.yandex.ru/i/5CdQyfRJXVj70g
