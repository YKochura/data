


## Пояснення колонок у файлі-анатоції [[labels-example](labels-example.csv)]

| Назва колонки  | Пояснення |
| :---: | --- |
| Image_name | Назва рентгенограми з директорії **images**|
| Sex | Стать пацієнта: <br> Male - Чоловік <br> Female - Жінка|
| Age | Вік пацієнта|
| Frontal/Lateral| <br> Frontal - Фронтальний [[приклад](im/view1_frontal2PA.jpg)] <br> Lateral - Бічний [[приклад](im/view2_lateral2.jpg)] |
| AP/PA |  Проекції [[детальніше](https://www.radiologymasterclass.co.uk/tutorials/chest/chest_quality/chest_xray_quality_projection)]: <br> Posterior-Anterior -- PA [[приклад](im/view1_frontal2PA.jpg)] <br> Anterior-Posterior -- AP [[приклад](im/view1_frontalAP.jpg)] |
| Device | Назва рентгенівського апарату, яким було зроблено знімок |
| No_Finding | Ренгенограми на яких не виявлено жодних ознак захворювання |


## Типи міток у файлі-анатоції [[labels-example](labels-example.csv)]

| Позначення мітки  | Пояснення |
| :---: | --- |
| 1 | У колонці з хворобою ця позначка означає, що на ренгенограмі чітко видно ознаки цієї хвороби. <br> У колонці *No_Finding* ця позначка означає, що на ренгенограмі немає ознак жодної хвороби. |
| Порожня комірка | Порожня комірка у колонці з хворобою означає, що на ренгенограмі відсутні ознаки цієї хвороби. <br> Порожня комірка у колонці *No_Finding* означає, що на ренгенограмі виявлено ознаки щонайменше однієї хвороби або є підозри на певну хворобу. |
| -1| У колонці з хворобою ця позначка означає, що ренгенолог не чітко впевнений щодо приналежності виявлених ознак до цієї хвороби. |


## Приклади

### Приклад \#1

| Image_name | Sex | Age | Frontal/Lateral | AP/PA | Device | No_Finding | Atelectasis| Consolidation | Infiltration | Pneumothorax | Edema | Emphysema | Fibrosis | Effusion | Pneumonia | Pleural_Thickening | Cardiomegaly | Nodule | Mass | Hernia | Tuberculosis  |
| :---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | 
| 2020_03_31_000001.png | Female | 68 | Frontal | AP | Siemens Mobilett XP Digital | 1 |  |  |  |  | |  |  |  |  |  | 

 На ренгенограмі *2020_03_31_000001.png* не виявлено ніяких ознак хвороби.