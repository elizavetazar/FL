# Formal Languages

## Описание проекта
Проект представляет собой десктопное приложение для визуализации графов и конечных автоматов с возможностью сохранения результата в виде изображения или TeX-кода.

## Инструкция пользователю
При запуске проекта появляется окно, состоящее из области рисования, меню кнопок и меню раскрывающихся вкладок. Меню кнопок позволяет выбирать режим рисования: вершина графа (состояние конечного автомата) или ребро (переход из одного состояния в другое). Это же меню позволяет удалять подвижные объекты сделать выбранное состояние принимающим или непринимающим, а также ввести текст, который отобразится на следующих нарисованных кругах или рядом со следующими нарисованными стрелками. 
Меню раскрывающихся вкладок делится на три блока: сохранение результатов, т.е. работа с файлами (изображениe или TeX-файл), работа с визуалом (изменение цветов контура и заливки состояний, контура стрелок, текстов, толщин линий и так далее) и очищение области рисования от всех объектов.

## Сборка
В директории formal_languages_project/formal_languages находится файл CMakeLists.txt для сборки с помощью утилиты CMake, однако предпочтительной является сборка с помощью утилиты QMake внутри фреймворка Qt.
