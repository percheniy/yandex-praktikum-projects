# yandex-praktikum-projects
Проекты, выполненные в ходе курса Data Science на Яндекс.Практикум.

## Список проектов:
### 1. [*Исследование надежности заемщиков*](../tree/master/reliability-research)
**Описание проекта:**
Кредитный отдел банка предоставил статистику о платёжеспособности клиентов. Цель - определить, влияет ли семейное положение, количество детей а также зароботок клиента на факт погашения кредита в срок. Исследование необходимо для построения модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

**Результат:**

**Инструменты и техники:**
Pandas, PyMystem3, Python, лемматизация, предобработка данных

**Статус проекта:**
Закончен

### 2. [*Исследование объявлений о продаже квартир*](../tree/master/real-estate-market-research)
**Описание проекта:**
В ходе проекта использованы данные сервиса Яндекс.Недвижимость, а именно архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Цель - научиться определять рыночную стоимость объектов недвижимости. Это позволит построить автоматизированную систему, которая отследит аномалии и мошенническую деятельность.

**Результат:**

**Инструменты и техники:**
Matplotlib, Pandas, Python, визуализация данных, исследовательский анализ данных, предобработка данных

**Статус проекта:**
Закончен

### 3. [*Определение перспективного тарифа для телеком компании*](../tree/master/tariff-for-telecom-company)
**Описание проекта:**
Оператор сотовой связи предлагает клиентам два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, оператору необходимо понять, какой тариф приносит больше денег. Цель - проанализировать поведение клиентов и сделать вывод — какой тариф лучше. Для этого произведен предварительный анализ тарифов на небольшой выборке клиентов. В распоряжении были данные 500 пользователей оператора: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год.

**Результат:**

**Инструменты и техники:**
Matplotlib, NumPy, Pandas, Python, SciPy, описательная статистика, проверка статистических гипотез

**Статус проекта:**
Закончен

### 4. [*Изучение рынка игр*](../tree/master/online-store-advertising-campaign)
**Описание проекта:**
Из открытых источников доступны исторические данные о продажах магазина компьтерных игр: оценки пользователей и экспертов, жанры и платформы. Цель - выявить определяющие успешность игры закономерности. Это поможет продвинуть потенциально популярный продукт и спланировать рекламные кампании.

**Результат:**

**Инструменты и техники:**
Matplotlib, NumPy, Pandas, Python, исследовательский анализ данных, описательная статистика, предобработка данных, проверка статистических гипотез

**Статус проекта:**
Закончен

### 5. [*Рекомендация тарифов для оператора мобильной связи*](../tree/master/tariff-recommendation-modeling)
**Описание проекта:**
Оператор мобильной связи хочет построить систему, способную проанализировать поведение клиентов и предложить новый тариф: «Смарт» или «Ультра». Цель - построить модель для задачи классификации с максимально большим значением accuracy, которая выберет подходящий тариф.

**Результат:**

**Инструменты и техники:**
Pandas, scikit-learn, Python, обучение модели, исследование модели, тестирование модели

**Статус проекта:**
Закончен

### 6. [*Предсказание оттока клиентов*](../tree/master/bank-customer-churn-modeling)
**Описание проекта:**
Банк столкнулся с проблемой - стали уходить клиенты. Маркетологи решили, что сохранять текущих клиентов дешевле, чем привлекать новых. Цель - спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Необходимо построить модель с достаточным значением F1-меры (как минимум 0.59), а для построенной модели измерить AUC-ROC, и сравнить её значение с F1-мерой. В распоряжении исторические данные о поведении клиентов и расторжении договоров с банком.

**Результат:**

**Инструменты и техники:**
Numpy, scikit-learn, Python, Pandas, предобработка данных, масштабирование признаков, взвешивание классов, измерение метрик F1 и AUC-ROC, downsampling

**Статус проекта:**
Закончен

### 7. [*Выявление прибыльного региона добычи для нефтяной компании*](../tree/master/oil-company-modeling)
**Описание проекта:**
Нефтяной компании необходимо решить, где бурить новую скважину. В распоряжении пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Цель - построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.

**Результат:**

**Инструменты и техники:**
Pandas, scikit-learn, Numpy, Seaborn, Scipy, Bootstrap, предобработка данных, исследовательский анализ данных, обучение модели, исследование модели

**Статус проекта:**
Закончен

### 8. [*Прототип модели машинного обучения для промышленного предприятия*](../tree/master/gold-recovery)
**Описание проекта:**
Цель проекта - подготовка прототипа модели машинного обучения для промышленного предприятия, которая поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В распоряжении данные с параметрами добычи и очистки. 

**Результат:**

**Инструменты и техники:**
Pandas, scikit-learn, Numpy, СatBoost, Matplotlib, предобработка данных, исследовательский анализ данных, обучение модели, исследование модели, кросс-валидация, масштабирование признаков

**Статус проекта:**
Закончен
