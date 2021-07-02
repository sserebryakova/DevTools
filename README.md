# Панели DevTools.
## Панель Elements.
Отредактировала DOM и CSS-свойства.

![DevTools](images/1.png)
![DevTools](images/2.png)

## Панель Console.
Вывывела ошибки (Errors) и предупреждения (Warnings).
![DevTools](images/3.png)
![DevTools](images/4.png)
Комментарий: Ошибка 404 - браузеру не удалось обнаружить на сервере указанный URL.

## Панель Sources. 
Определила какие ресурсы загружаются сайтом. Сделала prettyprint для одного из CSS/HTML/JS-файлов.

![DevTools](images/5.png)

Комментарий: Вкладка Page показывает файлы, которые используются на данной странице - файлы стилей, код на JavaScript, изображения, шрифты, json-файл,  сам исходный код.

## Панель Network
* Определила время загрузки страницы.

![DevTools](images/6.png)
* Определила какие из элементов грузятся дольше всего.

![DevTools](images/7.png)

* Для собственно страницы (HTML-файла) выяснила HTTP-заголовки запроса и ответа.

![DevTools](images/8.png)
![DevTools](images/9.png)

* Определила, сколько времени клиент ждал ответа (параметр Waiting (TTFB)).

![DevTools](images/10.png)

* Проверила загрузку сайта на медленном интернете.

![DevTools](images/11.png)

* Сделала скриншоты и посмотрела процесс загрузки.

![DevTools](images/12.png)

## Панель Performance.
Запустила профайлинг и затем посмотрела в Summary, на что было потрачено время.

![DevTools](images/13.png)
Комментарий: 101168 ms – загрузка скриптов. 62 ms — загрузка системных файлов. 10057 ms — бездействие пользователя.


## Панель Memory.
Сделала Heap Snapshot и посмотрела, сколько памяти заняла страница. 

![DevTools](images/14.png)

## Панель Application.
Проверила и почистила сookie.

![DevTools](images/15.png)

![DevTools](images/16.png)

## Панель Security.
Проверила, всё ли подключено через HTTPS, нет ли проблем с сертификатами.

![DevTools](images/17.png)

![DevTools](images/18.png)

## Панель Lighthouse.
Запустила проверки, посмотрела отчет анализа загружаемой страницы.

![DevTools](images/19.png)

# Device Toolbar.
Через DevTools в Chrome провела проверку сайта на совместимость с готовым пресетом iPad.

![DevTools](images/20.png)
Оформила баг-репорты.

# Построила XPath для объектов.
### Заголовок «Все организации».

![DevTools](images/21.png)

*Абсолютный путь -/html/body/div[2]/div/div[2]/div[3]/div[1]/div/div/div[1]/div/div/div/div[1]/div/h1.*

*Относительный путь - //*[@id="container"]/div[1]/div/div/div[1]/div/div/div/div[1]/div/h1.

### Кнопка «Экспорт».

![DevTools](images/22.png)

*Абсолютный путь - /html/body/div[2]/div/div[2]/div[3]/div[1]/div/div/div[2]/div[1]/a.*
*Относительный путь - //*[@id="container"]/div[1]/div/div/div[2]/div[1]/a.

### Кнопка «Создать организацию».

![DevTools](images/23.png)

*Абсолютный путь - /html/body/div[2]/div/div[2]/div[3]/div[1]/div/div/div[2]/div[2]/div/a.
Относительный путь - //*[@id="container"]/div[1]/div/div/div[2]/div[2]/div/a.
