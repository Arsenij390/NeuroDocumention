Данная нейросеть принимает файл формата *.pdf, далее конвертирует постранично в *.png, проверяет, определяет и копирует проверяемый файл в соответствующую папку.

Загружаем папку с нейросетью. Далее переносим все на гуглдиск (Так как я писал код в гугл колабе). Из-за не большой выборки, она может путаться. Например, из за того что в "resume" и в "scientific" были использованы
для обучения изображения с картинкой, и в общем сама выборка при обучении была не большой, нейросеть может путать их. Так и с "email" и с "scintific" тоже путает. 
1. Устанавливаем дополнительные инструменты через *pip*: pdf2image, poppler-utils, PyPDF2 (ОБЯЗАТЕЛЬНО)
2. Прогружаем все блоки по порядку
3. Для подключения к гугл диску используется шестой блок, после импортов. Подключаемся к аккаунту, который используется в гугл диске, все принимаем и после некоторого времени появляется надпись об успешном подключении
4. В блоке "Загрузка модели" загружаем модель с весами с названием 'my_model_v5.h5'
5. Чтобы изменить файл, который нужно проверить: в строке (последний блок) *pdf_file* = ("*name*.pdf") - вместо "*name*" прописываем имя файла, в *pdf_path* указываем путь к ПАПКЕ с файлом.
6. Запускаем и ниже показывается результат.

Работа выполнена студентами РИС-23-1м:
Пронин Арсений
Шеин Виталий
