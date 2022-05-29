# Восстановления золота из золотосодержащей руды

**Промышленность** - одна из перспективных сфер применения машинного обучения. Данный проект непосредсвенно связан с *реальным производственным процессом*. Реальный кейс от компании "Цифра" и за это нельзя не сказать спасибо!

Предскажем **коэффициент восстановления золота из золотосодержащей руды**, учитывая большое количество различных параметров добычи и технологического процесса очистки.

Моё базовое образование - техническое. Поэтому было приятно выполнить проект такого рода: в котором объединяются технология  и машинное обучение. Надеюсь, в нашем будущем таких задач будет становиться больше, и они будут приносить пользу, выведут промышленность на новый уровень.

На первый взгляд может показаться, что данных в этом проекте неимоверное количество. Но постепенный, пошаговый анализ приводит к тому, что начинаешь в них ориентироваться и понимать что к чему относится.

Перечиваю этот проект и думаю: а всё начилось с простенького проекта Яндекс.Музыка. А здесь и технология, и функциональная часть, и кросс-валидация двумя способами, всё как положено. 

## Библиотеки и инструменты

 `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `sklearn`, `pyplot`, `stats`, `mean_absolute_error`, `make_scorer`, `cross_val_score`, `KFold`, `LinearRegression`, `DecisionTreeRegressor`, `RandomForestRegressor`

## Описание данных

В нашем распоряжении три набора данных: обучающий (**14149** объектов), тестовый (**5290** объектов) и полный (**19439** объектов).

В *обучающем* и *полном* наборах данных по **87 признаков**, в *тестовом* - **53 признака**. 

Количество строк (объектов) обучающего и тестового наборов данных в сумме дают в точности количество строк в полном наборе данных.

**Технологический процесс**

- *Rougher feed* — исходное сырье
- *Rougher additions* (или reagent additions) — флотационные реагенты: Xanthate, Sulphate, Depressant
- *Xanthate* — ксантогенат (промотер, или активатор флотации);
- *Sulphate* — сульфат (на данном производстве сульфид натрия);
- *Depressant* — депрессант (силикат натрия).
- *Rougher process* (англ. «грубый процесс») — флотация
- *Rougher tails* — отвальные хвосты
- *Float banks* — флотационная установка
- *Cleaner process* — очистка
- *Rougher Au* — черновой концентрат золота
- *Final Au* — финальный концентрат золота

**Параметры этапов**

- *air amount* — объём воздуха
- *fluid levels* — уровень жидкости
- *feed size* — размер гранул сырья
- *feed rate* — скорость подачи

**Наименование признаков**

`[этап].[тип_параметра].[название_параметра]`

*Пример*: `rougher.input.feed_ag`

Возможные значения для блока `[этап]`:
- *rougher* — флотация
- *primary_cleaner* — первичная очистка
- *secondary_cleaner* — вторичная очистка
- *final* — финальные характеристики

Возможные значения для блока `[тип_параметра]`:
- *input* — параметры сырья
- *output* — параметры продукта
- *state* — параметры, характеризующие текущее состояние этапа
- *calculation* — расчётные характеристики
