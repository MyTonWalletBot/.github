# MyTonWallet Giveaways
This project consists of 3 parts - backend (API), frontend (dapp) and Telegram bot. Startup instructions are provided separately in each repository.
> [!NOTE]
> To run the frontend, simply bring up a web server that distributes files from the repository, no additional build is required.

> [!WARNING]
> Bot works *on testnet* now. Wallet address: `EQDWdmk-I5CYgHMd0BFhniOKrhzqXfendEhCaO2Q6vHF56ej`

The task assigment of the contest (the specification) was fully implemented.

## Backend
Link - [backend](https://github.com/MyTonWalletBot/backend)


## Frontend
Link - [dapp](https://github.com/MyTonWalletBot/dapp)

## Telegram bot
Link - [bot](https://github.com/MyTonWalletBot/bot)

## Contacts
If you have access-related errors or any questions, you can contact me in Telegram: https://t.me/difhel

<details>
  <summary>My to-do list for this contest (not important to check)</summary>
  
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
- [x] Выплата пользователям
    - [x] Jetton
    - [x] Заменить контракт с WalletV4 на HighloadWalletV3
    - [x] Поллинг
    - [x] Функция выплаты
    - [x] Перемещение секретов в ENV переменную
- [x] Обратные вызовы для выполнения задач
- [x] CORS
- [x] Получить статус пользователя
- [x] Добавить опциональное поле creatorTelegramID
- [x] Если есть поле creatorTelegramID, при оплате отправляем уведомление
- [x] Создать инструкцию к запуску + несколько нужных переенных

## Фронтенд
- [x] Авторизация
    - [x] Ton Connect with proof
    - [x] Cloudflare Captcha
- [x] Check in
- [x] Статус участия
    - [x] 404 (розыгрыш не найден)
    - [x] Ожидание задания (awaitingTask)
    - [x] участник, ждем подведения итогов
    - [x] проиграл
    - [x] Получил вознаграждение, ожидает выплаты
    - [x] Получил вознаграждение, выплачено
    - [x] раздача уже завершена

## Бот
- [x] создание раздачи
- [x] получение информации о раздаче (статус, количество участников текущее и максимальное, бюджет, адрес контракта)
- [x] ~уведомление о том, что раздача оплачена~
</details>
