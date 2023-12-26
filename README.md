# Анализ предпочтений пользователей ВК-сообщества "Типичный Ясногорск"

Итак, для начала вы, возможно, захотите узнать, что такое Ясногорск и где это... и это будет абсолютно актуальный вопрос. Ясногорск - это небольшой городок, который находится почти в Тульской области (Россия). Население этих крошечных территорий насчитывает около 20000 человек. Здесь нет большого количества средств массовой информации, как в крупных городах, - только пара местных газет, которые не могут предоставить самую свежую информацию. Однако местные жители всегда знают, где можно получить достоверную информацию о том, что происходит в городе. Это место называется [**Типичный Ясногорск** ](https://vk.com/typical_yasnogorsk)

Это сообщество в социальной сети ВК. Люди, живущие в городе с одноименным названием, могут получать самую свежую информацию обо всем, что в нем происходит. Основной целью этого поверхностного анализа распределения пользователей было показать, насколько разными и интересными являются участники этого сообщества. 

Данные для исследования были получены с помощью VK API (с использованием **Implicit Flow** Token для авторизации). Объемы анализируемых значений могут различаться от переменной к переменной. Размер данных для наблюдаемых категориальных переменных был выбран на основе наличия соответствующего значения для определенных категориальных переменных. Оригинальные данные и графики вы можете найти по этой [ссылке]()

Анализу подвергаются следующие категориальные переменные: 
- Возраст
- Пол
- Возрастные категории 
- Текущий город проживания
- Отношения
- Вредные привычки
- Политические взгляды
- Ценности людей
- Жизненные ценности
- Язык

## 1. Распределение пользователей по возрасту и полу

Первые две категории, которые были "проанализированы" (да, я бы не назвал это прям АНАЛИЗОМ), - это возраст и пол. Для исследования были отобраны все подписчики, указавшие год рождения и пол в своем публичном профиле в VK. Результаты следующие: распределение по полу показало, что в сообществе почти равное количество мужчин и женщин (небольшое преимущество у женщин). Распределение по возрасту показало, что **средний возраст подписчиков составляет 36 лет** и только 25 % подписчиков старше 47 лет. Самому младшему последователю 14 лет, а самому старшему пользователю 122 года, что, вероятно, является шуткой (Рисунок 1).

<image src="/plots/sex_and_age" alt="Распределение пользователей по возрасту и полу">

Также пользователи были разделены по возрастным категориям со следующими возрастными требованиями (Таблица 1). Большинство подписчиков относится к **взрослой категории**, что неудивительно (Рисунок 2). 

#### Таблица 1 - Распределение пользователей по возрастным категориям
| до 12 | 12-18|18-65  |старше 65  |
|:--:|:--:|:--:|:--:|
|  Дети|Подростки  | Взрослые |Пожилые |

<image src="/plots/age_cats" alt="Распределение пользователй по возрастным категориям">

## 2. Распределение пользователей по текущему городу проживания

Следующая категория, которая была рассмотрена, - это распределение пользователей по их текущему месту жительства. Разброс значений был значительным, что и послужило основной причиной того, что на гистограмме были представлены только первые десять городов. Очевидно, что основная часть участников сообщества проживает в [Ясногорске](https://ru.wikipedia.org/wiki/%D0%AF%D1%81%D0%BD%D0%BE%D0%B3%D0%BE%D1%80%D1%81%D0%BA_(%D0%A2%D1%83%D0%BB%D1%8C%D1%81%D0%BA%D0%B0%D1%8F_%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C)) (Рисунок 3). Другие города с серебряной и бронзовой медалями в этом распределении - Тула и Москва, из чего можно сделать вывод, что большинство жителей не любят переезжать далеко от Ясногорска и предпочитают жить рядом. 

<image src="/plots/current_city" alt="Распределение пользователей по их текущему городу проживания">

## 3. Распределение пользователей по их семейному статусу

With regards to followers relation status, significant part of examined users prefers not to say about their relationship (or just does not know hot to work with profile statutes). Subsequently, the widest bar on the diagram is "unknown". However, there are also a lot of followers who preferred to expose their relationship status (and even mentioned their partner). Results of this distribution are demonstrated below (Picture 3)

<image src="/plots/relation.png" alt="Followers Distribution By Their Relation Status">


## 4. Followers Distribution By Bad Habits
Next it would be great to see how healthy community followers are. In order to achieve this there was examination of followers in terms of their bad habits like smoking and drinking alcohol beverages. Distributions were based on followers who mentioned their attitude to smoking and alcohol in own profile. Both charts demonstrated that mostly people are absolutely neutral to these harmful habits (Picture 4).

<image src="/plots/smoking_and_alco.png" alt="Followers Distribution By Their Attitude to Bad Habits">

## 5. Followers Distribution By Political Views

The following chart shows the difference between users when it comes to their attitudes towards politics. The vast majority profess moderate political views. Also, equal number of followers are adepts of socialism, communism, liberalism, while libertarianism has the least popularity among followers (Picture 5)

<image src="/plots/political_views.png" alt="Followers Distribution By Their Political Views">

## 6. Followers Distribution By People and Life Values

Next pie charts can tell everything about our followers' characters. It can be seen that in case of life values the biggest "piece of pie" is taken by family, while such fields as entertainment and fame are insignificant. Also, fields like art and science do not have many adepts as well. Second chart demonstrates that the most part of followers prefers honesty and kindness as their life value and put wealth on a last place.
Taking all things into consideration in can be concluded that most users prefer to follow conservative values during their entire life (Picture 6).

<image src="/plots/life_people_values.png" alt="Followers Distribution By Their Life and People Values">

## 7. Followers Distribution By Languages

As it can be seen Yasnogorsk is multinational town. People from all around the world live there and this point can be proved by the following chart (Picture 7). Turned out that there are so many languages followers can speak, so most popular languages were distinct. 

<image src="/plots/popular_languages.png" alt="Followers Distribution By Their Life and People Values">

 


