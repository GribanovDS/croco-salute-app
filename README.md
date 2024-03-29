# Описание приложения "Слова для Крокодила"

Это всем знакомая игра в Крокодила, разработанная специально для семейства виртуальных помощников "Салют", созданных в "Сбере". В нее ежедневно заходят около 100 пользователей таких устройств, как: SberBox, SberBox Time, SberBox Top и SberBox Portal.

![Фото](https://github.com/GribanovDS/croco-salute-app/assets/74065724/4fca5b52-da87-4d74-934b-76348467333e)


Для более детального ознакомления с смартапом перейдите по [ссылке](https://apps.sber.ru/salute-apps/1e6553a2-fd60-4698-8c9f-4164c4ba49f9/)

## Инструкция по использованию

Игра "Слова для Крокодила" проста и легка в использовании. Вы должны объяснить слово, используя жесты, мимику и другие способы, не используя слова и звуки, которые напоминают это слово. Другие пользователи должны угадать, что вы объясняете.

## Гипотеза по улучшению приложения

Я выдвинул гипотезу о том, что изменение дизайна логотипа и внутренней карточки игры в каталоге приложений может увеличить метрики приложения, такие как **Daily Active Users (DAU)**, **Monthly Active Users (MAU)** и **Customer Retention Rate (CRR)**. Я решил провести эксперимент и провести изменения в дизайне. Эксперимент показал, что мои ожидания оправдались, и метрики приложения действительно улучшились.

Благодаря изменениям в дизайне, я смог увеличить **DAU** и **MAU**, а также увеличить **CRR**, что привело к тому, что "Слова для Крокодила" попали в **топ-100** приложений Салют за **декабрь 2022 года**. Как результат, я смог увеличить число пользователей, а также получить прибыль за разработку приложения.

## Стэк технологий

В приложении "Слова для Крокодила" используются следующие технологии:

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - язык программирования, который используется для разработки приложения;
- [TypeScript](https://www.typescriptlang.org/docs/) - язык программирования, который используется для разработки приложения; 
- [Dialute](https://github.com/Dikower/Dialute) - библиотека для создания интерфейсов на языке JavaScript;
- [Svelte](https://svelte.dev/docs) - фреймворк для создания пользовательских интерфейсов;
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) и [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - языки разметки и стилей, которые используются для создания веб-страниц.
- [SmartMarket](https://developers.sber.ru/docs/) - документация для разработки смартапов для ассистентов "Салют"

Для разработки приложения "Слова для Крокодила" я использовал эти технологии вместе с другими инструментами и библиотеками, чтобы создать удобный и понятный интерфейс для пользователей. Если вы хотите узнать больше о каждой из этих технологий, я рекомендую посетить официальные сайты и документацию.

## Установка

1. Клонируйте репозиторий на свой компьютер.
2. Установите Dialute с помощью команды `npm install -g dialute`.
3. Установите пакет с виртуальными ассистентами "Салют" с помощью команды `npm install @sberdevices/assistant-client`.
4. Установите себе клиент [ngrok](https://ngrok.com).
6. Перейдите в папку `app` и напишите `npm run dev`
   ```
   cd app
   npm run dev
      ```
6. Перейдите в папку `hook` и напишите `npm run dev`
   ```
   cd hook
   npm run dev
   ```
 7. Запустите сервер ngrok на 8000 порту командой `./ngrok http 8000`
 8. Перейдите по полученной ссылке!
