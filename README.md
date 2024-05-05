# Задачи по контесту
**Ссылка на ТЗ:** [клик](https://telegra.ph/MyTonWallet-Giveaways-04-27)
## Бекенд
- [x] Создание раздачи
- [x] Получение раздачи по id
- [x] Авторизация пользователя в раздаче
    - [x] Унифицирование пользователя в БД
    - [x] Создание пользователя и обновление всех количества участников розыгрыша + выделение статуса пользователю
    - [x] Валидация через catpcha и signedProof
    - [x] Если раздача instant, то ограничиваем количество тех, кто может регаться
- [x] Мониторинг пополнения раздачи
- [x] Мониторинг завершившихся розыгрышей
- [ ] Выплата пользователям
    - [ ] Jetton
    - [ ] Заменить контракт с WalletV4 на HighloadWalletV3
    - [x] Поллинг
    - [x] Функция выплаты
    - [x] Перемещение секретов в ENV переменную
- [x] Обратные вызовы для выполнения задач
- [x] CORS
- [x] Получить статус пользователя
- [x] Добавить опциональное поле creatorTelegramID
- [x] Если есть поле creatorTelegramID, при оплате отправляем уведомление
- [ ] Создать инструкцию к запуску + несколько нужных переенных

## Фронтенд
- [x] Авторизация
    - [x] Ton Connect with proof
    - [x] Cloudflare Captcha
- [ ] Check in
- [x] Статус участия
    - [x] 404 (розыгрыш не найден)
    - [x] Ожидание задания (awaitingTask)
    - [x] участник, ждем подведения итогов
    - [x] проиграл
    - [x] Получил вознаграждение, ожидает выплаты
    - [x] Получил вознаграждение, выплачено
    - [x] раздача уже завершена

## Бот
- [ ] создание раздачи
- [ ] получение информации о раздаче (статус, количество участников текущее и максимальное, бюджет, адрес контракта)
- [ ] ~уведомление о том, что раздача оплачена~
