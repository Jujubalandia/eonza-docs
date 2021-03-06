---
title: Страница Языковые ресурсы в редакторе Eonza
desc: Документация для страницы Языковые ресурсы в редакторе Eonza.
---
# Языковые ресурсы

Языковые ресурсы позволяют реализовать многозыковую поддержку скрипта. Причем автоматическая подстановка нужного языка будет происходить как в интерфейсе программы, так и во время исполнения скрипта. Такая возможность полезна, если вы планируйте выложить ваш скрипт в публичный доступ. Следует заметить, что если закладка Скрипт пустая, то вы должны давать уникальные имена ресурсам без префикса *_*. Например, *yourscriptname.resname*. На момент написания этой статьи программа Eonza поддерживала только два языка - английский и русский. Поэтому для примера создадим скрипт который будет также поддерживать эти два языка.

**Шаг 1.** Определим на английском языке название скрипта и текст, который он будет выводить. Если ресурс не используется во время выполнения скрипта, то вы можете начинать его имя с символа **_**. В этом случае компилятор будет пропускать такую строку.

*_hello* - Script prints Hello  
*lng.hello* - Hello, world!

%html.editor-language-1%

**Шаг 2.** Переключимся на русский язык и добавим переводы для этих языковых ресурсов.

%html.editor-language-2%

**Шаг 3.** В настройках скрипта укажем его наименование как **#_hello#**.

%html.editor-language-3%

**Шаг 4.** Добавим в скрипт команду Вывод в консоль значения #lng.hello#

%html.editor-language-4%

Сейчас запустим наш скрипт и увидим текст на текущем языке интерфейса. Если мы изменим язык интерфейса в настройках программы и снова запустим скрипт, то увидим, что язык скрипта тоже изменился.

%html.editor-language-5%
%html.editor-language-6%
