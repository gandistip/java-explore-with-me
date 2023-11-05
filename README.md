# Event Poster - микросервисное приложение Афиша мероприятий
Java, Spring Boot, PostgreSQL, JPA, Hibernate ORM, Maven, Lombok, Docker, REST API.

## О проекте
Пользователи предлагают мероприятия, могут искать мероприятия по параметрам или формируя подборки и подают заявки на участие мероприятиях.
![](https://github.com/gandistip/event-poster/assets/120060980/5c46a985-a224-4696-872b-ca63867aa3c4)
* API сервиса состоит из 3 частей:
   - публичная - доступна без регистрации любому пользователю сети,
   - закрытая - доступна только авторизованным пользователям,
   - административная - для администраторов сервиса.
* В составе приложения есть микросервис сбора статистики фиксирующий:
   - количество обращений пользователей к спискам мероприятий,
   - количество запросов к подробной информации о мероприятии.

## Эндпоинты
![](https://github.com/gandistip/event-poster/assets/120060980/05777b80-b016-49a3-9b67-cd40cec03bbd)

## Основная сущность - Event (мероприятие)
![](https://github.com/gandistip/event-poster/assets/120060980/6e9d5a02-5c0d-45ad-b7a6-f8b6edf9d432)

## Схема БД:
![](https://github.com/gandistip/java-explore-with-me/assets/120060980/7e77be41-4a12-42a3-ac60-df0d57c0cd0f)

