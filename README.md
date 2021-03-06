


## Пояснення колонок у файлі-анатоції [[labels-example](labels-example.csv)]

| Назва колонки  | Пояснення |
| :---: | --- |
| Image_name | Назва рентгенограми з директорії **images**|
| Sex | Стать пацієнта: <br> Male - Чоловік <br> Female - Жінка|
| Age | Вік пацієнта|
| Frontal/Lateral| <br> Frontal - Фронтальний [[приклад](im/view1_frontal2PA.jpg)] <br> Lateral - Бічний [[приклад](im/view2_lateral2.jpg)] |
| AP/PA |  Проекції [[детальніше](https://www.radiologymasterclass.co.uk/tutorials/chest/chest_quality/chest_xray_quality_projection)]: <br> Posterior-Anterior (PA) [[приклад](im/view1_frontal2PA.jpg)] <br> Anterior-Posterior (AP) [[приклад](im/view1_frontalAP.jpg)] |
| Device | Назва рентгенівського апарату, яким було зроблено знімок |
| No_Finding | Ренгенограми на яких не виявлено жодних ознак захворювання |


## Типи міток у файлі-анатоції [[labels-example](labels-example.csv)]

| Позначення мітки  | Пояснення |
| :---: | --- |
| 1 | У колонці з патологічним станом ця позначка означає, що на рентгенограмі чітко видно ознаки цього патологічного стану. <br> У колонці *No_Finding* ця позначка означає, що на рентгенограмі немає ознак жодного патологічного стану. |
| Порожня комірка | Порожня комірка у колонці з патологічним станом означає, що на рентгенограмі відсутні ознаки цього патологічного стану. <br> Порожня комірка у колонці *No_Finding* означає, що на рентгенограмі виявлено ознаки щонайменше одного патологічного стану або є підозри на певний патологічний стан. |
| -1| У колонці з патологічним станом ця позначка означає, що ренгенолог не чітко впевнений (є підозри) щодо приналежності виявлених ознак до цього патологічного стану. |


## Приклади

### Приклад \#1

| Image_name | Sex | Age | Frontal/Lateral | AP/PA | Device | No_Finding | Atelectasis| Consolidation | Infiltration | Pneumothorax | Edema | Emphysema | Fibrosis | Effusion | Pneumonia | Pleural_Thickening | Cardiomegaly | Nodule | Mass | Hernia | Tuberculosis  |
| :---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | :---: |:---: | 
| 2020_03_31_000001.png | Female | 68 | Frontal | AP | Siemens Mobilett XP Digital | 1 |  |  |  |  | |  |  |  |  |  | 

 На рентгенограмі *2020_03_31_000001.png* не виявлено ознак жодного патологiчного стану захворювання легень.