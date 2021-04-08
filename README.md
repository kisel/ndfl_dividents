# Инструмент для помощи в заполнении декларации 3-НДФЛ на сайте https://lkfl2.nalog.ru/lkfl/ по доходу с дивидендов иностранных компаний с подписанной формой W-8BEN

## Это ПО написано для личного пользования и автор не несёт ответственности за ошибки в поданных с помощью него декларациях! Обязательно вручную проверяйте введённые в автоматическом режиме данные!!!

## На данный момент поддерживается отчётность только от брокера Tinkoff, но в будущем функционал может быть расширен.

## Инструкция к приминению:

Запросите в чате поддержки Тиньков отчётность по дивидендам иностранных компаний за нужный год в формате *.xlsx*

Полученный файл `dividends.XLSX` откройте в Microsoft Excel или загрузите в Google docs.

Далее инструкция для [Google Sheets](https://docs.google.com/spreadsheets/u/0/), в Microsoft Excel всё можно сделать по подобию:

Создайте новую пустую таблицу
В левом верхнум углу нажмите "Файл" => "Импортировать" => "Загрузить" => "Выбрать файл с вашего устройства" => выберите файл с отчётностью `dividends.XLSX` => кликните "Заменить таблицу"
Выделите верхние четыре ряда и удалите их как на скриншоте
<img width="1191" alt="Screenshot 2021-04-08 at 22 11 14" src="https://user-images.githubusercontent.com/9252654/114083343-83a50800-98b7-11eb-84e7-0f0bb5484d3a.png">

Найдите все остальные строки не относящиеся к дивидендам и также удалите их
<img width="1051" alt="Screenshot 2021-04-08 at 22 13 22" src="https://user-images.githubusercontent.com/9252654/114083559-cff04800-98b7-11eb-84f0-87b026de865d.png">
<img width="1169" alt="Screenshot 2021-04-08 at 22 15 36" src="https://user-images.githubusercontent.com/9252654/114083716-0332d700-98b8-11eb-9a4a-4f7ac47c1806.png">
Удалите картинку "Тиньков" в верхнем левом углу

*Убедитесь, что вы случайно не удалили из отчёта строки, относящиеся к выплатам по дивидендам!*

Загрузите файл обратно на компьютер в формате CSV. "Файл" => "Загрузить" => "В формате с запятой как разделитель"


Установите язык программирования Elixir https://elixir-lang.org/install.html

Установите Chrome Driver https://sites.google.com/a/chromium.org/chromedriver/downloads

Скачайте этот репозиторий себе на компьютер.
