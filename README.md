# master-diploma

## Overview
Этот проект разрабатывался в рамках дипломной работы.
Задача состояла в том, чтобы обучить нейронную сеть детектировать запрещенные предметы на рентгеновских снимках багажа.
В качестве детектора использовалась нейронная сеть YOLOv5. 


## Данные
Для решения задачи был использовае высококачественный набор данных для обнаружения запрещенных рентгеновских объектов под названием OPIXray, который содержит 8885 рентгеновских изображений 5 категорий широко распространенных запрещенных предметов – «режущих предметов». Изображения собраны в аэропорту, и аннотированы вручную профессиональными инспекторами.

<a href="https://github.com/OPIXray-author/OPIXray">Ссылка на датасет</a>

<a href="https://github.com/ultralytics/yolov5">Ссылка на репозиторий YOLOv5</a>

### OPIXray dataset
<p align=center>
    <img src="images/samples.png" width="60%" height="60%"/>
</p>

## Предсказание модели
<p align=center>
    <img src="images/output.png" width="60%" height="60%"/>
</p>

## Результаты
<p align=center>
    <img src="images/results.png" width="60%" height="60%"/>
</p>

### Confusion matrix
<p align=center>
    <img src="images/confusion_matrix.png" width="60%" height="60%"/>
</p>

### F1
<p align=center>
    <img src="images/F1_curve.png" width="60%" height="60%"/>
</p>

### Precision
<p align=center>
    <img src="images/P_curve.png" width="60%" height="60%"/>
</p>

### Recall
<p align=center>
    <img src="images/R_curve.png" width="60%" height="60%"/>
</p>

### PR_curve
<p align=center>
    <img src="images/PR_curve.png" width="60%" height="60%"/>
</p>
