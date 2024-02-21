# Биомедицинские нанотехнологии и компьютерное зрение (Computer Vision)

<center><img width='50%' src='img/cell_move_short.gif'></center>

> Репозиторий содержит программный код и датасеты для учебного курса по Computer Vision

<div align='justify'>Применение компьютерного зрения для анализа биомедицинских сигналов и объектов. Представлено 5 практических работ по использованию алгоритмов компьютерного зрения для анализа данных. Рассмотрены базовые принципы обработки изображений. Показана возможно использования различных методов библиотеки OpenCV для определения размеров объектов на изображении. Подробнор рассмотрен процесс трекинга объектов. В дополнение анализируются методы выделения признаков отдельных объектов на изображении. Последняя работа посвящена детекции объектов на изображении.</div><br>

> Перечень практических заданий

1. Фильтрация и преобразование изображений [>>>](lab_1_filter.ipynb)<br>
1.1. Загрузка изображения и цветовые модели¶ <br>
1.2. Фильтрация изображений

2. Поиск объектов на изображении и измерение их линейных размеров [>>>](lab_2_measure.ipynb)<br>
2.1. Определение линейных размеров объекта<br>
2.2. Определение количества элементов на изображении<br>
2.3. Поиск элементов по шаблону и подсчёт их количеств

3. Трекинг объектов на изображении [>>>](lab_3_tracking.ipynb)<br>
3.1 Отслеживание траектории движения на основе вычитания фона (Background Subtraction)<br>
3.2 Отслеживание траектории движения на основе поиска и анализа контуров<br>
3.3 Отслеживание траектории движения на основе анализа среднего значения (Meanshift)

4. Обнаружение и описание признаков на изображении [>>>](lab_4_features.ipynb)<br>
4.1 Определение углов по методу Харриса (Harris Corner Detection)<br>
4.2 Масштабно-инвариантная трансформация признаков (SIFT)<br>
4.3 Извлечение признаков по ускоренному анализу сегмента (FAST)<br>
4.4 Комбинация детектора ключевых точек FAST и бинарных дескрипторов BRIEF (ORB)<br>
4.5 Сопоставление объектов с использованием алгоритма ORB

5. Детекция объектов на основе каскадного классификатора [>>>](lab_5_detection.ipynb)<br>
5.1. Использование классификаторов Хаара для распознования лиц на изображении<br>
5.2. Использование классификаторов Хаара для распознования клеток лейкоцитов<br>
5.3. Создание собственного каскадного классификатора Хаара

> Каждая практическая работа сопровождается заданиями для самостоятельной работы.

