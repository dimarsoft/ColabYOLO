# ColabYOLO
Notebooks with YOLO works

Постбоработка пробная:
https://github.com/dimarsoft/ImageViewerApp/blob/master/folder_viewer.py

Позже перенесу в отдельный код.

надо научится обрабатывать видео файл и наложить на него результаты и постобработку:
- боксы, центр человека, в каске он, в жилете

22.02.2023 - 01.03.2023
- обучение моделей v7, v8
- инференс на тестовых видео.
  можно указать путь к папке и обработает все файлы в ней.
  если указать save_txt, то лейблы буду сохранены в тектовый файл.
  их можно использовать для самстоятельного наложения рамок и доп. информации
- сделано наложение на видео: рамок, турникета, центр человека + окуржность разным цветов (до турникета и после)
  
01.03.2023 - 10.03.2023

- использование обученной ранее модели
- инференс с со встренным треком
1. https://colab.research.google.com/drive/1P1LzwUlmzageoRUsLbVpEkNJFGiun_Ab?usp=sharing
2. https://github.com/dimarsoft/yolov8_tracking
https://colab.research.google.com/drive/1MmykLWRJ6zaLNJpcm3ElsTKMm8LKtRNK?usp=sharing

- наложение трека на видео
botsort
https://drive.google.com/drive/folders/1bEtNFCUE2iI8zPFZQIhdAFZvCiz1Clr0?usp=sharing
strongsort
https://drive.google.com/drive/folders/19aXhkW4sSnuGzw2LQNv4QDmZa1cvuDrr?usp=sharing

- реализация алгоритма подсчета перехода через турникет и фиксация нарушений

https://colab.research.google.com/drive/1gPusnV9qaHTlSn9LjPEzJh3CoAVE6Trc?usp=sharing

