---
title: Закладка Настройки - документация Eonza
desc: Документация по закладке Настройки программы Eonza.
img:
   settings-scripts: settings-scripts.png
   settings-personal: settings-personal.png
   settings-constants: settings-constants.png
   settings-security: settings-security.png
---
# Настройки

Здесь вы можете указать различные настройки для более комфортной работе с программой Eonza. Чтобы изменения настроек вступили в силу, вам необходимо нажать на кнопку Сохранить.

## Скрипты

**Вставлять исходный код**  
При запуске скрипты программа генерирует из скрипта программу на [скриптовом языке программирования Gentee](https://ru.gentee.org/) и компилирует её в байт-код. После этого, она отправляет этот байт-код на исполнение. Если вы хотите иметь возможность видеть сгенерированные исходный текст на языке Gentee, то отметьте этот чекбокс. В этом случае, исходный текст будет доступен как во время выполнения, так и после завершения работы скрипта. Эта возможность может быть полезна в случае возникновения ошибок при выполнения скрипта.

**Уровень лога**  
Укажите уровень лога по умолчанию для всех запускаемых скриптов.

%html.settings-scripts%

## Персональные

Страница с персональными настройками.

**Язык**  
Вы можете указать предпочитаемый язык интерфейса программы и выполняемых скриптов.

%html.settings-personal%

## Глобальные константы

Вы можете определить глобальные константы, которые можно использовать во всех скриптах. Подстановка значений происходит как у переменных, но слева к имени константы добавляется точка. Например, если вы хотите вставить значение константы *myconst* в какой-то скрипт, то укажите *#.myconst#*.

%html.settings-constants%

## Безопасность

Здесь расположены настройки, которые помогут защититься от несанкционированного доступа к программе. Вы можете установить пароль для подключения к Eonza. Программа не хранит пароль в явном виде, поэтому утерянный пароль невозможно восстановить. В этом случае, можно сделать [сброс пароля](restore-password.html) с помощью параметра командной строки.

**Текущий пароль**  
Если вы хотите установить новый пароль, то вам необходимо указать текущий пароль. Если пароль отсутствует, то данное поле скрыто.

**Пароль**  
Укажите пароль для доступа к программе. Если вы хотите отключить вход по паролю, то укажите *Текущий пароль*, а этот параметр оставьте пустым.

**Не просить пароль при запуске**  
По умолчанию, при запуске программы пользователь должен заново вводить пароль в браузере. Отметьте этот чекбокс, если вы не хотите вводить пароль после каждого запуска. Следует заметить, что если вы отметите этот чекбокс, то вам всё равно нужно будет ввести пароль один раз при следующем запуске.

%html.settings-security%

Для выхода из программы выберите пункт *Выйти* в выпадающем меню в правом верхнем углу. В этом случае, выход будет осуществлён для всех подключенных устройств и браузеров.

%html.logout%
