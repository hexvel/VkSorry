### VKSorry | LP module
>VKSorry module позволяет управлять разными функциями VK из любого чата.
---
## Навигация
1. [Переменные](#Переменные)
2. [Установка](#Установка)
3. [Команды](#Команды)
>Все ссылки кликабельны.
---
## Переменные
|  *  | Переменная   |      Описание      |  *  |
|:---:|--------------|:------------------:|:---:|
|  *  | `{USER}`     |   Реплай:Ссылка    |  *  |
|  *  | `{PASS}`     |    Пароль от VK    |  *  |
|  *  | `{DATA}`     |   Текст-Вложения   |  *  |
|  *  | `{NONE}`     |   Без параметра    |  *  |
|  *  | `{TEXT}`     | Произвольный текст |  *  |
|  *  | `{LOGIN}`    |    Логин от VK     |  *  |
|  *  | `{ENTER}`    |   Перенос строки   |  *  |
|  *  | `{PARAMS}`   |      Параметр      |  *  |
|  *  | `{COMMAND}`  |      Команда       |  *  |
|  *  | `{CPREFIX}`  |   Префикс команд   |  *  |
|  *  | `{SPREFIX}`  |  Префикс скриптов  |  *  |
|  *  | `{TOKENVKA}` |   Токен VKAdmin    |  *  |
|  *  | `{TOKENVKS}` |   Токен VKSorry    |  *  |
* [⬆️Навигация](#Навигация)
---
# Установка
## Получаем токен [VKAdmin](https://vk.cc/9NCoPi).
- Листаем в самый низ, нажимаем [Разрешить].
- Копируем то-что находится в URL адресе страницы.
### Переходим в личные сообщения с [группой](https://vk.com/lpvks).
- Пишем - `/create`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session created.
- Пишем - `/vka {ENTER} {TOKENVKA}`
- - Получаем - ✅ &#60;VKSLP Module&#62; Token VKA updated.
- Пишем - `/restart`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session restarted.
### Проверяем - `{CPREFIX}` инфо
## Получаем токен [VKSorry](https://vk.com/lpvks).
- Отключаем 2Хфакторную аутентифиакцию.
- Вспоминаем логин и пароль от страницы.
### Переходим в личные сообщения с [группой](https://vk.com/lpvks).
- Пишем - `/stop`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session stopped.
- Пишем - `/vks {ENTER} {LOGIN} {ENTER} {PASS}`
- - Получаем - ✅ &#60;VKSLP Module&#62; Token VKS updated.
- Пишем - `/restart`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session restarted.
### Проверяем - `{CPREFIX}` инфо
* [⬆️Навигация](#Навигация)
---
## Команды
- [ ] [Скрипты](#Скрипты)
  * [Информация](#Информация-скриптов)
  * [Статистика](#Статистика-скриптов)
  * [Автолайк](#Автолайк)
  * [Автопилот](#Автопилот)
  * [Автоприем](#Автоприем)
  * [Автостатус](#Автостатус)
  * [Автоонлайн](#Автоонлайн)
  * [Автоотписка](#Автоотписка)
  * [Автооффлайн](#Автооффлайн)
  * [Автоуведомления](#Автоуведомления)
  * [Авторекомендации](#Авторекомендации)
- [ ] [Функции](#Функции)
  * [Информация](#Информация-аккаунта)
  * [Статистика](#Статистика-аккаунта)
  * [Прочитать сообщения](#Прочитать-сообщения)
  * [Отправка сообщений](#Отправка-сообщений)
  * [Текст аудио](#Текст-аудио)
  * [Демотиватор](#Демотиватор)
  * [Текст в голосовое](#Текст-в-голосовое)
  * [Стикеры](#Стикеры)
  * [Статистика вконтакте](#Статистика-вконтакте)
  * [Пролайкать](#Пролайкать)
  * [Дата регистрации](#Дата-регистрации)
  * [Включить уведомления](#Включить-уведомления)
  * [Отключить уведомления](#Отключить-уведомления)
  * [Добавить в друзья](#Добавить-в-друзья)
  * [Удалить из друзей](#Удалить-из-друзей)
  * [Добавить в чс](#Добавить-в-чс)
  * [Удалить из чс](#Удалить-из-чс)
* [⬆️Навигация](#Навигация)
---
## Скрипты
### Информация скриптов
- `{SPREFIX}` __инфо__ - Информация о состоянии скриптов
---
### Статистика скриптов
- `{SPREFIX}` __стата__ - Статистика работы скриптов
---
### Автолайк
- `{SPREFIX}` __автолайк__ - Включает/Выключает Автолайк
---
### Автоприем
- `{SPREFIX}` __автоприем__ - Включает/Выключает Автоприем
---
### Автоуведомления
- `{SPREFIX}` __автоуведы__ - Включает/Выключает Автоуведомления
---
### Автоотписка
- `{SPREFIX}` __автоотп__ - Включает/Выключает Автоотписка
---
### Автопилот
- `{SPREFIX}` __автопилот__ - Включает/Выключает Автопилот
---
### Авторекомендации
- `{SPREFIX}` __автореки__ - Включает/Выключает Авторекомендации
---
### Автостатус
- `{SPREFIX}` __автостатус__ - Включает/Выключает Автостатус
---
### Автоонлайн
- `{SPREFIX}` __автоонл__ - Включает/Выключает Автоонлайн
---
### Автооффлайн
- `{SPREFIX}` __автоофл__ - Включает/Выключает Автооффлайн
---
* [⬆️Навигация](#Навигация)
---
## Функции
### Информация аккаунта
- `{CPREFIX}` __инфо__ - Профиль аккаунта в боте
---
### Статистика аккаунта
- `{CPREFIX}` __стата__ - Статистика аккаунты
---
### Прочитать сообщения
- `{CPREFIX}` __прочитать__ `всё/лс/группы/беседы` `{NONE}/подробно` - Пометит сообщения как прочитанные
---
### Отправка сообщений
- `{CPREFIX}` __лс__ `{USER}` `{ENTER}` `{DATA}` - Отправит сообщение в лс пользователю
---
### Текст аудио
- `{CPREFIX}` __слова__ - Вернет текст аудиозаписи
---
### Демотиватор
- `{CPREFIX}` __дем__ `{ENTER}` `{TEXT}` `{ENTER}` `{TEXT}` - Создаст демотиватор
---
### Текст в голосовое
- `{CPREFIX}` __озвучь__ `{ENTER}` `{TEXT}` - Озвучит текст
---
### Стикеры
- `{CPREFIX}` __стики__ `{USER}` - Вернет стикеры пользователя
---
### Статистика вконтакте
- `{CPREFIX}` __статавк__ `{NUMBER}` - Вернет Статистику вконтакте
---
### Пролайкать
- `{CPREFIX}` __пролайкать__ `{USER}` - Пролайкает страницу
---
### Дата регистрации
- `{CPREFIX}` __датарег__ `{USER}` - Отобразит дату регистрации 
---
### Включить уведомления
- `{CPREFIX}` __+ув__ `{USER}` - Включит уведомления
---
### Отключить уведомления
- `{CPREFIX}` __-ув__ `{USER}` - Отключит уведомления
---
### Добавить в друзья
- `{CPREFIX}` __+др__ `{USER}` - Добавит в друзья
---
### Удалить из друзей
- `{CPREFIX}` __-др__ `{USER}` - Удалит из друзей
---
### Добавить в чс
- `{CPREFIX}` __+чс__ `{USER}` - Добавит в черный список
---
### Удалить из чс
- `{CPREFIX}` __-чс__ `{USER}` - Удалит из черного списка
---
* [⬆️Навигация](#Навигация)
