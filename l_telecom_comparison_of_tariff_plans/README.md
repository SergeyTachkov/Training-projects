<b>Определение перспективного тарифа для телеком-компании</b><br/>
Сфера проекта: <b>телеком</b><br/><br/>
Задание: Компания — федеральный оператор сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Надо сделать предварительный анализ тарифов на небольшой выборке клиентов. Есть данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Надо проанализировать поведение клиентов и сделать вывод — какой тариф лучше. <br/><br/>
Используемые инструменты, библиотеки и навыки: <b>`Matplotlib` `Math` `Pandas` `NumPy` `Python` `SciPy` `Описательная статистика` `Проверка стат.гипотез`</b><br/><br/>
Данные: необходимо использовать данные о пользователях, данные о звонках, данные о сообщениях,  данные об интернет-сессиях, данные о тарифах. Все данные в файлах .csv формата.<br/><br/>
<b>Структура проведенного исследования: </b><br/>
1. Изучение данных из представленного файла данных.<br/>
1.1. Выставление окружения и импорт библиотек.<br/>
1.2. Импортируем основной файл данных локально и применяем кострукцию except для тренажера<br/>
1.2.1. Отсмотрим последовательно все датасеты<br/>
1.2.2. Описание данных, начальное.<br/>
1.3. Краткие выводы по структуре/<br/>
2. Изучение данных конкретных столбцов и предобработка данных.<br/>
2.1. Таблица users.csv<br/>
2.2. Таблица calls.csv<br/>
2.3. Таблица messages.csv<br/>
2.4. Таблица internet.csv<br/>
2.5. Помесячная выручка с каждого пользователя<br/>
3. Исследовательский анализ данных.<br/>
3.1. Портрет среднего клиента по каждому тарифу.<br/>
3.2. Сезонность и изменение экономики по месяцам.<br/>
3.3. Посмотрим распределение возраста аудитории каждого тарифа и как средний возраст менялся по месяцам.<br/>
3.4. Гистограммы распределения<br/>
3.5. Краткие выводы по разделу 3. <br/>
4. Проверка гипотез.<br/>
4.1. Cредняя выручка пользователей тарифов «Ультра» и «Смарт» <br/>
4.2. Проверка гипотезы - средняя выручка пользователи из Москвы отличается от выручки пользователей из других регионов.<br/>
5. Выводы.

