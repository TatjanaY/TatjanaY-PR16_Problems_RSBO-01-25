# Сборник аналитических заданий по Data Science с использованием Python

## 📋 Общие условия выполнения всех заданий

Все 35 заданий выполняются **исключительно с использованием стека Python** с фокусом на библиотеки **Pandas** для обработки данных и **Matplotlib/Seaborn** для визуализации.

### 🔧 Обязательный технологический стек для всех заданий:
- **Python 3.8+** (основной язык программирования)
- **Pandas** - загрузка, очистка, обработка и анализ данных
- **NumPy** - численные вычисления и работа с массивами
- **Matplotlib/Seaborn** - построение всех типов визуализаций
- **Jupyter Notebook** - среда выполнения и оформления отчетов
- **Дополнительные библиотеки по необходимости**: SciPy (статистика), Scikit-learn (машинное обучение), Geopandas (пространственные данные), TextBlob/NLTK (обработка текста)

### 📊 Единая структура каждого из 35 заданий:

1. **Цель задания** - четкая формулировка цели анализа в конкретной предметной области
2. **Набор данных** - описание используемого датасета с прямой ссылкой на Kaggle
3. **Гипотезы для проверки** - ровно 5 конкретных, проверяемых гипотез
4. **Этапы выполнения** - 5 последовательных этапов анализа:
   - **Этап 1**: Загрузка и предобработка данных (ETL) - работа с пропусками, аномалиями, создание признаков
   - **Этап 2**: Разведочный анализ и проверка гипотез 1-4 через специализированные визуализации
   - **Этап 3**: Углубленный анализ для гипотезы 5 (кластеризация, регрессия, прогнозирование)
   - **Этап 4**: Создание комплексного аналитического отчета в Jupyter Notebook
   - **Этап 5**: Заключение с выводами по гипотезам и практическими рекомендациями

### 📈 Требования к визуализациям (единые для всех заданий):
- Для каждой из 5 гипотез создается **минимум одна специализированная визуализация**
- Все графики строятся с помощью **Matplotlib/Seaborn**
- К каждому графику прилагается **краткий вывод** о подтверждении/опровержении гипотезы
- Визуализации должны быть **профессионально оформлены** (подписи осей, легенды, заголовки, разметка)
- **Таблица визуализаций** включается в Этап 2 каждого задания

### 📝 Требования к отчету (единые для всех заданий):
- Отчет выполняется в **Jupyter Notebook**
- Содержит **последовательное выполнение всех 5 этапов** анализа
- Включает **текстовые пояснения** к каждому этапу и результатам
- Содержит **таблицу с визуализациями** для Этапа 2
- Завершается **структурированным заключением** с практическими рекомендациями для предметной области
- **Код должен быть комментирован**, а анализ - воспроизводим

### 🎯 Критерии оценки (общие для всех заданий):
1. **Полнота выполнения** всех 5 этапов (20% за каждый этап)
2. **Корректность и наглядность визуализаций** (20%)
3. **Логичность выводов** по гипотезам (20%)
4. **Качество итогового отчета** - структура, читаемость, оформление (20%)
5. **Практическая ценность рекомендаций** для предметной области (20%)

---

## Сводная таблица вариантов заданий

| № | Название проекта | Ключевые темы | Библиотеки | Ссылка на датасет |
|---|------------------|---------------|------------|-------------------|
| 1 | [Анализ данных пассажиров «Титаника»](./problem1.md) | EDA, обработка пропусков, визуализация, категориальные данные | Pandas, Matplotlib | [Titanic Dataset](https://www.kaggle.com/c/titanic/data) |
| 2 | [Анализ потребительского поведения на данных Olist](./problem2.md) | EDA, временные ряды, географический анализ, правило Парето | Pandas, Matplotlib | [Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) |
| 3 | [Анализ рыночных данных для электронной коммерции](./problem3.md) | EDA, сезонность, тепловые карты, ABC-анализ | Pandas, Matplotlib | [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| 4 | [Анализ оттока клиентов в телекоммуникационной компании](./problem4.md) | EDA, обработка категориальных данных, тепловые карты, группировка | Pandas, Matplotlib | [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) |
| 5 | [Анализ эффективности маркетинговых кампаний банка](./problem5.md) | EDA, временные ряды, обработка текста, тепловые карты | Pandas, Matplotlib | [Bank Marketing Dataset](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset) |
| 6 | [Оптимизация цепочки поставок и анализ портфеля продуктов ритейлера](./problem6.md) | EDA, анализ запасов, ABC-анализ, тепловые карты | Pandas, Matplotlib | [Retail Sales & Inventory Data](https://www.kaggle.com/datasets/manjeetsingh/retaildataset) |
| 7 | [Анализ данных здравоохранения и клинический дашборд](./problem7.md) | Медицинская статистика, визуализация, тепловые карты, EDA | Pandas, Matplotlib, Seaborn | [Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) |
| 8 | [Анализ эффективности цифрового маркетинга и клиентского опыта](./problem8.md) | Текстовая аналитика, визуализация, облака слов, временные ряды | Pandas, Matplotlib, Seaborn | [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) |
| 9 | [Анализ управления персоналом и прогнозная аналитика кадровых показателей](./problem9.md) | Классификация, кластеризация, визуализация, анализ оттока | Pandas, Matplotlib, Seaborn, Scikit-learn | [IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) |
| 10 | [Анализ городской инфраструктуры и данных умного города](./problem10.md) | Геопространственный анализ, кластеризация, временные ряды | Pandas, Geopandas, Matplotlib, Seaborn | [NYC 311](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9), [NYC Bike Share](https://www.citibikenyc.com/system-data) |
| 11 | [Финансовый анализ и стресс-тестирование портфеля](./problem11.md) | Временные ряды, оптимизация портфеля, риск-метрики, корреляции | Pandas, NumPy, Matplotlib, Seaborn, SciPy | [yfinance](https://pypi.org/project/yfinance/) (S&P 500 stocks) |
| 12 | [Анализ эффективности логистики и цепочек поставок](./problem12.md) | Генерация данных, оптимизация, классификация, временные ряды | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn | Синтетический датасет |
| 13 | [Анализ эффективности рекламных кампаний в digital-маркетинге](./problem13.md) | Атрибуция, кластеризация, временные ряды, интерактивная визуализация | Pandas, Scikit-learn, Matplotlib, Seaborn | Синтетический датасет |
| 14 | [Анализ клиентского опыта и предиктивная аналитика оттока](./problem14.md) | Классификация, кластеризация, SHAP, генерация признаков | Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn | Синтетический датасет |
| 15 | [Анализ производительности и предиктивное обслуживание промышленного оборудования](./problem15.md) | Временные ряды, кластеризация, регрессия, классификация | Pandas, Scikit-learn, Matplotlib, Seaborn | [AI4I Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification) или синтетический |
| 16 | [Анализ эффективности розничной сети и мерчандайзинга](./problem16.md) | Кластеризация, статистические тесты, тепловые карты, регрессия | Pandas, Scikit-learn, SciPy, Matplotlib, Seaborn | Синтетический датасет |
| 17 | [Анализ энергопотребления и прогнозирование нагрузки в умных сетях](./problem17.md) | Кластеризация, прогнозирование, обнаружение аномалий, временные ряды | Pandas, Scikit-learn, Matplotlib, Seaborn | [London Smart Meters](https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london) |
| 18 | [Анализ производительности и надежности IT-инфраструктуры](./problem18.md) | Классификация, кластеризация, NLP, временные ряды, мониторинг | Pandas, Scikit-learn, Matplotlib, Seaborn | Синтетический датасет |
| 19 | [Анализ результатов клинических исследований](./problem19.md) | Статистический анализ, визуализация, кривые Каплана-Майера, ANCOVA | Pandas, SciPy, Statsmodels, Matplotlib, Seaborn, Lifelines | Синтетический датасет |
| 20 | [Стратегический анализ рынка и конкурентной среды](./problem20.md) | Кластеризация, корреляционный анализ, тональность, временные ряды | Pandas, Scikit-learn, Matplotlib, Seaborn, TextBlob/VADER | [yfinance](https://pypi.org/project/yfinance/), [Financial News](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news) |
| 21 | [Анализ спортивных результатов и тактических паттернов в футболе](./problem21.md) | EDA, кластеризация, регрессия, визуализация, группировка | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn | [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) |
| 22 | [Анализ музыкальных предпочтений и трендов на стриминговых платформах](./problem22.md) | EDA, кластеризация, временные ряды, NLP, рекомендательные системы | Pandas, Scikit-learn, Matplotlib, Seaborn, Spotipy | [Spotify Tracks Dataset](https://www.kaggle.com/datasets/mrmorj/spotify-tracks-dataset) |
| 23 | [Анализ экологических данных и изменения климата](./problem23.md) | Временные ряды, регрессия, корреляция, статистическое моделирование, геовизуализация | Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn, Statsmodels | [Climate Change Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data) |
| 24 | [Анализ рынка труда и тенденций трудоустройства](./problem24.md) | Текстовая аналитика, кластеризация, временные ряды, геопространственный анализ | Pandas, Scikit-learn, Matplotlib/Seaborn, NLTK, Geopandas | [Job Dataset](https://www.kaggle.com/datasets/mohamedharris/job-dataset) |
| 25 | [Анализ рынка недвижимости и факторов стоимости жилья](./problem25.md) | Геопространственный анализ, регрессия, кластеризация, временные ряды, прогнозирование | Pandas, Scikit-learn, Matplotlib/Seaborn, Geopandas, Folium | [King County House Sales](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) |
| 26 | [Анализ эффективности образовательных программ и успеваемости студентов](./problem26.md) | EDA, кластеризация, регрессия, статистический анализ, визуализация | Pandas, Scikit-learn, Matplotlib/Seaborn, Statsmodels | [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) |
| 27 | [Анализ данных о питании и пищевых привычках](./problem27.md) | EDA, кластеризация, корреляционный анализ, визуализация питательных профилей | Pandas, Scikit-learn, Matplotlib/Seaborn, NetworkX | [McDonald's Nutrition Dataset](https://www.kaggle.com/datasets/mcdonalds/nutrition-facts) |
| 28 | [Анализ общественного транспорта и городской мобильности](./problem28.md) | Временные ряды, кластеризация, геовизуализация, регрессия, анализ сезонности | Pandas, Scikit-learn, Matplotlib/Seaborn, Geopandas | [CTA Ridership Dataset](https://www.kaggle.com/datasets/chicago/cta-ridership) |
| 29 | [Анализ киноиндустрии и кассовых сборов](./problem29.md) | Кластеризация, регрессия, временные ряды, текстовая аналитика, финансовая аналитика | Pandas, Scikit-learn, Matplotlib/Seaborn, TextBlob/NLTK | [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) |
| 30 | [Анализ эффективности электронной коммерции и поведения покупателей](./problem30.md) | RFM-анализ, кластеризация, геоанализ, временные ряды, анализ ассоциаций | Pandas, Scikit-learn, Matplotlib/Seaborn, NetworkX, Plotly | [Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) |
| 31 | [Анализ энергоэффективности зданий и потребления ресурсов](./problem31.md) | Регрессия, кластеризация, корреляционный анализ, геопространственная визуализация | Pandas, Scikit-learn, Matplotlib/Seaborn, Geopandas | [Energy Efficiency Dataset](https://www.kaggle.com/datasets/elikplim/eergy-efficiency-dataset) |
| 32 | [Анализ энергетического потребления и возобновляемых источников энергии](./problem32.md) | Временные ряды, кластеризация, корреляция, регрессия, геовизуализация | Pandas, Scikit-learn, Matplotlib/Seaborn, Statsmodels | [Global Energy Consumption Dataset](https://www.kaggle.com/datasets/unitednations/global-energy-consumption) |
| 33 | [Анализ видеоигровой индустрии и игровых предпочтений](./problem33.md) | EDA, кластеризация, регрессия, временные ряды, текстовая аналитика | Pandas, Scikit-learn, Matplotlib/Seaborn, NetworkX | [Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings) |
| 34 | [Анализ рынка видеоигр и игровых предпочтений](./problem34.md) | Кластеризация, регрессия, временные ряды, геоанализ, текстовая аналитика | Pandas, Scikit-learn, Matplotlib/Seaborn, TextBlob/NLTK | [Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales) |
| 35 | [Анализ рынка электронной коммерции и поведения онлайн-покупателей](./problem35.md) | RFM-анализ, кластеризация, геоанализ, временные ряды, анализ ассоциаций | Pandas, Scikit-learn, Matplotlib/Seaborn, NetworkX | [Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) |

---

**Удачи в выполнении заданий!** Каждое задание представляет собой законченный аналитический проект, который можно добавить в портфолио Data Scientist.