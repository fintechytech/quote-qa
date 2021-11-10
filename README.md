# Приложение котировок

Тестовое задание для QA

## Описание

Перед вами приложение с биржевыми котировками, требуется, используя известные вам инструменты провести его автоматическое тестирование.

Приложение доступно по адресу [https://fintechytech.github.io/quote/](https://fintechytech.github.io/quote/)

Техническое задание на это приложение [описано в этом документе](Requirements.md).

## Задание


1. Протестировать что приложение доступно и корректно загружается вместе со своими ресурсами (страница не падает, health-check)
2. Протестировать что приложение показыает данные в таблице (таблица с ячейками не пустая)
3. Протестировать что приложение сортирует таблицу при нажатии на заголовок




### Инструменты

Вы можете использовать любые известные вам интрументы и фреймворки для выполнения задания, с условием что они открытые (не проприетарные) и работают на linux.
Желательно подготовить docker образ для быстрого запуска всех тестов. Если вы владете стеком python + selenium будет лучше выполнить задание на нём

### Формат сдачи

Исходный код авто-тестов нужно упаковать в zip архив и прислать HR'у от которого вы получили это задание, в архиве должно быть минимальное описание как запустить тесты и Dockerfile если вы решили упаковать тесты в docker образ.

### Коментарии

* Начните выполнение заданий с первого, помните что важнее качество выполнения заданий, а не количество. 
* В первую очередь будет проверяться подход к тестированию и его полнота, так что можете не тратить время на оформление и документацию кода, однако код всё же должен быть читаемым и понятным
* Приложение не тестировалось раньше, так что вы возможно сможете найти в нём баги, однако специально никаких ошибок расставлено не было.
* Все тесты должны проходить независимо друг от друга, падения одного не должны приводить к остановке тестирования, тоесть если вы обнаружили ошибку в одном из пунктов, тесты должны продолжать идти и выдавать все найденные ошибки, а не только первую, если конечно найденная ошибка не приводит к невозможности протестировать все остальное.
* Время на выполнение заданий не ограничено, но будет приниматься во внимание в разумных пределах. Если вы решите сделать дополнительные задание, то мы конечно учтем что на их выполнение ушло больше времени.

### Дополнительные задания

Можете их пропустить, но если вам интересно с какими задачами у нас предстоит работать, далее можно с ними познакомиться:

1. Протестировать что приложение отвечает своим основным функциональным требованиям (см. [ТЗ](Requirements.md))
2. Протестировать что приложение отвечает своим дополнительным функциональным требованием (см. [ТЗ](Requirements.md)
3. Протестировать что приложение работает без нежелательных предупреждений, ошибок или логирование, не делает лишних запросов.
4. Протестировать что приложение отвечает своим нефункциональным требованиям (см. [ТЗ](Requirements.md)


