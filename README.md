# Определение перспективного тарифа для телеком-компании

---

<p align="center">
  <img src="https://www.protarif.info/news/thumbnails/b7ffcce08ddd1f9d9c3bf5dff6ccc580.jpeg" width=800 height=500 />
</p>

---
Клиентам компании «Мегалайн» предлагают два тарифных плана: ***«Смарт»*** и ***«Ультра»***. Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

<br/>

***Тариф «Смарт»***:
1. Ежемесячная плата: 550 рублей
2. Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
3. Стоимость услуг сверх тарифного пакета:
    * минута разговора: 3 руб.
    * сообщение: 3 руб.
    * 1 Гб интернет-трафика: 200 руб.
 
<br/>

***Тариф «Ультра»***:
1. Ежемесячная плата: 1950 рублей
2. Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
3. Стоимость услуг сверх тарифного пакета:
    * минута разговора: 1 руб.
    * сообщение: 1 руб.
    * 1 Гб интернет-трафика: 150 руб.

<br/>

*Примечания:* 
* «Мегалайн» всегда округляет вверх значения минут и мегабайтов. Если пользователь проговорил всего 1 секунду, в тарифе засчитывается целая минута
* Для веб-трафика отдельные сессии не считаются. Вместо этого общая сумма за месяц округляется в бо́льшую сторону. Если абонент использует 1025 мегабайт в этом месяце, с него возьмут плату за 2 Гб
* Если в тарифе, к примеру, 100 минут разговора в месяц, то со 101 минуты будет взиматься плата

---

### Задачи исследования:

1. Изучение общей информации о предоставленных датасетах
2. Предобработка данных - приведение к нужным типам, поиск и исправление имеющихся ошибок 
3. Расчет и добавление в таблицу:
    * количества сделанных звонков и израсходованных минут разговора по месяцам
    * количества отправленных сообщений по месяцам
    * объема израсходованного интернет-трафика по месяцам
    * помесячной выручки с каждого пользователя 
4. Анализ показателей - описание поведения клиентов оператора, исходя из выборки. Сколько минут разговора, сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц?:
    * подсчет среднего количества, дисперсии и стандартного отклонения
    * построение гистограмм
    * описание распределений
5. Проверка гипотез:
    * средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются
    * средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов
6. Формирование общего вывода

---
