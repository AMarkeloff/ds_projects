# ds_projects

## **Привет и добро пожаловать!** 

Здесь вы можете познакомиться с моими учебными проектами. Над ними я добросовестно и не покладая рук трудился 8,5 месяцев, когда учился в *Яндекс.Практикуме* на **Специалиста по Data Science**. 

Отмечу, что всё это я сделал, не отрываясь от основной работы, поэтому процесс выполнения проектов был в несколько раз интереснее. Поймёт тот, кто знает.

## Для удобства 

Для удобства навигации по репозиторию я собрал все проекты в одну табличку и подготовил краткое описание к каждому из них. 

**Щёлкайте** на проект, который вас заинтересует, изучайте, вдруг почерпнёте для себя что-то полезное. 

И отдельно для студентов ЯП: пожалуйста, не списывайте, я старался!:)

|**№**| **Название проекта** | **Краткое описание проекта** | **Ключевые слова проекта**|
|:--------------------:| :-------------------- | :--------------------- |---------------------------:|
|1| [Исследование музыкальных предпочтений жителей Москвы и Санкт-Петербурга](https://github.com/AMarkeloff/ds_projects/tree/main/yandex_music)| Вооружившись библиотекой `pandas`, мы на реальных данных посмотрим насколько Питер культурный, а Москва контрастная. Всё это произойдёт на реальных данных Яндекс.Музыки, столь популярного и полюбившегося многим стримингового сервиса. | *Что используем, применяем и даже устраняем*: группировка, сортировка, дубликаты (явные и неявные), логическая индексация, пропуски (а куда же без них!), первые функции|
|2| [Исследование надёжности заёмщиков](https://github.com/AMarkeloff/ds_projects/tree/main/borrowers_reliability)| Влияют ли семейное положение, уровень дохода, наличие детей и цель кредита на его возврат в срок? Попробуем ответить на эти вопросы с помощью `pandas` и `pymystem3` на основе статистики о платежеспособности клиентов банка. | *Нам поможет*: группировка, категоризация, лемматизация, обработка данных, пропуски, дубликаты, декомпозиция|
|3| [Исследование объявлений о продаже квартир](https://github.com/AMarkeloff/ds_projects/tree/main/eda_appartment_sale_announcement)| Как отследить аномалии и мошенническую деятельность на сайте объявлений о продаже недвижимости? На основе архива Яндекс.Недвижимости о продаже квартир в Питере и Ленинрадской области за несколько лет установим параметры для автоматизированной фрод-мониторинг системы. *Помогут справиться*: `pandas`, `matplotlib`, `pyplot` и `seaborn`| *Не обошлось без*: категоризация,  фрод-мониторинг, обработка данных, `histogram`, `boxplot`, `scattermatrix`, `scatterplot` |
|4| [Определение перспективного тарифа для мобильного оператора](https://github.com/AMarkeloff/ds_projects/tree/main/money_making_tariff)|Определим перспективный тариф для телеком-компании на основании данных о годовой активности клиентов. Выводы подкрепим **статистической проверкой гипотез**. *Помогут справиться*: `pandas`, `matplotlib`, `numpy`, `scipy`| обработка данных, описательная статистика, проверка статистических гипотез, статистический тест, критерий Стьюдента, а также `histogram`, `boxplot`|
|5| [Определение перспективных игровых продуктов](https://github.com/AMarkeloff/ds_projects/tree/main/advanced_gaming_products)|Как правильно выбрать перспективный игровой продукт для интернет-магазина компьютерных игр? Решим поставленную задачу с помощью данных о популярности игр и различных платформ до 2016 года. *Набор библиотек*: `pandas`, `matplotlib`, `numpy`, `scipy`, `plotly`, `seaborn`| обработка данных, описательная статистика, проверка статистических гипотез, статистический тест, критерий Стьюдента, агрегированные данные|
|6|[Рекомендация тарифов клиентам мобильного оператора](https://github.com/AMarkeloff/ds_projects/tree/main/tariff_recommendation_model)|Если клиент пользуется утсравшим тарифом, ему нужно помочь оптимизировать свои затраты. На основании данных о поведении клиентов мобильного оператора создадим модель, рекомендующую абоненту один из двух **новых тарифов**. Возьмём с собой: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`|классификация, подбор гиперпараметров, выбор ML модели, `pyplot`, `DecisionTreeClassifier`, `accuracy_score`, `train_test_split`, `RandomForestClassifier`, `LogisticRegression`, `DummyClassifier`, `confusion_matrix`, `classification_report`|
|7|[Отток клиентов банка](https://github.com/AMarkeloff/ds_projects/tree/main/bank_customers_churn)|Не секрет, что в современных реалиях сохранять текущих клиентов банка может быть дешевле, чем привлекать новых. Поможем маркетологам, создадим модель, которая будет прогнозировать уйдёт ли клиент из банка. Берём с собой: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`|классификация, дисбаланс классов, подбор гиперпараметров, выбор ML модели, `pyplot`, `accuracy_score`, `classification_report`, `f1_score`, `roc_curve`, `roc_auc_score`, `train_test_split`,  `DecisionTreeClassifier`, `RandomForestClassifier`, `LogisticRegression`, `StandardScaler`, `shuffle`|
|8|[Выбор наиболее выгодного региона для нефтедобычи](https://github.com/AMarkeloff/ds_projects/tree/main/oil_production_region)|Три потенциальных региона для нефтедобычи. Где может быть получена наибольшая прибыль? Представлены пробы нефти для всех регионов. Известны характеристики каждой скважины в каждом из них. Построим модель, выбирем перспективный регион и оценим риски методом `bootstrap`. Традиционно воспользуемся:  `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`|регрессия, оценка бизнес-рисков, бутстреп, `RandomState`, `train_test_split`, `LinearRegression`, `mean_squared_error`|
|9|[Восстановления золота из золотосодержащей руды](https://github.com/AMarkeloff/ds_projects/tree/main/gold_recovery)|Сделаем модель, предсказывающую коэффициент восстановления золота из руды. Будем использовать данные с параметрами добычи и технологичских стадий очистки. Реальный проект от компании "Цифра", разрабатывающей решения для повышения эффективности промышленных предприятий. Нам помогут:  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `sklearn`|анализ данных, регрессия, кастомные метрики, кросс-валидация, `pyplot`, `stats`, `mean_absolute_error`, `make_scorer`, `cross_val_score`, `KFold` ,`LinearRegression`, `DecisionTreeRegressor`, `RandomForestRegressor`|
|10|[Защита персональных данных клиентов](https://github.com/AMarkeloff/ds_projects/tree/main/personal_information_protection)|Используя линейную алгебру, разработаем алгоритм преобразования данных для защиты персональной информации клиентов страховой  компании. Используем: `pandas`, `numpy`, `matplotlib`, `seaborn`,  `sklearn`|линейная алгебра, регрессия, `pyplot`, `train_test_split`, `r2_score`, линейная регрессия "вручную"|
|11|[Определение рыночной стоимости автомобилей](https://github.com/AMarkeloff/ds_projects/tree/main/car_market_value)|Решим задачу регрессии с помощью численных методов. Построим модель для определения рыночной стоимости автомобиля, используя исторические данные: технические характеристики, комплектации, цены. Нам помогут: `pandas`, `numpy`, `seaborn`, `matplotlib`,` sklearn`, `catboost`, `lightgbm`|градиентный бустинг, регрессия, `CatBoostRegressor`, `CatBoost`, `LinearRegression`, `StandardScaler` , `mean_squared_error`, `r2_score`, `train_test_split`, `pyplot`, `GridSearchCV`, `LGBMRegressor`|
|12|[Прогнозирование заказов такси на следующий час](https://github.com/AMarkeloff/ds_projects/tree/main/taxi_demand_forecasting)|Как привлечь больше водителей в аэропорт в периоды пиковой нагрузки? Попробуем спрогнозировать количество заказов на следующий час для этой цели. Используем исторические данные о заказах такси в аэропортах. Нам однозначно понадобятся: `pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`, `statsmodels.tsa.seasonal`|временные ряды, регрессия, предсказания, `seasonal_decompose`, `LinearRegression` , `DecisionTreeRegressor`, `RandomForestRegressor`, `mean_squared_error`,  `train_test_split`, `pyplot`|
|13|[Модель классификации комментариев](https://github.com/AMarkeloff/ds_projects/tree/main/toxic_comments_classification)|Интернет-магазин запускает новый сервис: пользователи смогут редактировать и дополнять описания товаров. Построим инструмент, который будет идентифицировать токсичные комментарии, чтобы отправить их на модерацию. Стоит присмотреться к:  `pandas`, `numpy`, `seaborn`, `matplotlib`, `re`, `nltk`, `sklearn`|машинное обучения для текстов, задача классификации, `TfidfVectorizer`, `stopwords`, `LogisticRegression` , `DecisionTreeClassifier`, `RandomForestClassifier`, `DummyClassifier`,  `train_test_split`, `pyplot`, `accuracy_score`, `confusion_matrix`, `classification_report`, `f1_score`, `roc_curve`, `roc_auc_score`|
|14|[Определение возраста по фотографии](https://github.com/AMarkeloff/ds_projects/tree/main/age_by_photo)|В нашем распоряжении набор фотографий людей с указанием возраста. Строим модель, которая по фотографии определит приблизительный возраст человека. Зачем: сетевой ритейлер внедряет систему компьютерного зрения для определния возраста покупателей по фото. *Точно понадобятся*: `tensorflow.keras`, `ImageDataGenerator`, `pandas`, `matplotlib`, `seaborn`|регрессия, Обработка изображений, компьютерное зрение, обучение нейронной сети, сверточная и полносвязная нейронные сети|

___

## Спасибо

**Спасибо**, что заглянули на мою страничку, посетили мой репозиторий.
