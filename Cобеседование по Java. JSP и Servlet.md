# Cобеседование по Java. Разбор вопросов и ответов.


[//]: # (<a href="https://mc.yandex.ru/pixel/8711235002931986822?rnd=%aw_random%">)

[//]: # (    <img src="https://mc.yandex.ru/pixel/8711235002931986822?rnd=%aw_random%" />        )

[//]: # (  </a>&nbsp;&nbsp;)

[//]: # (<a href="https://mc.yandex.ru/watch/92801430">)

[//]: # (    <img src="https://mc.yandex.ru/watch/92801430" />        )

[//]: # (  </a>&nbsp;&nbsp;)

[//]: # ()
[//]: # ()
[//]: # (Нажмите ★, если вам нравится проект. Ваш вклад сердечно ♡ приветствуется.)

[//]: # ()
[//]: # (Если вам интересно мое резюме: https://github.com/DEBAGanov)




JSP (оглавление)

1.   Что такое jsp и зачем он нужен?
2.   Расскажите об этапах жизненного цикла jsp.
3.   Расскажите о методах жизненного цикла jsp.
4.   Как закомментировать код в jsp?
5.   Какие есть способы вставки java кода в jsp страницу?
6.   Почему не рекомендуется использовать скриптовые элементы в jsp?
7.   Какие неявные, внутренние объекты есть на jsp странице?

8.   Что вы знаете о PageContext?
9.   Как можно запретить использование скриптов и java кода на jsp странице?
10.  Что вы знаете о jsp тегах?
11.  Что вы знаете о языке выражений jsp (JSP Expression Language – EL)?
12.  Назовите неявные, внутренние объекты JSP EL и их отличия от объектов jsp.
13.  Как узнать http метод использую JSP EL?
14.  Что такое JSTL (Jsp Standard tag library)?
15.  На какие категории можно разделить JSTL теги, приведите примеры.
16.  Что вы знаете о написании пользовательских jsp тегов?
17.  Как можно обработать ошибки jsp страниц?
18.  Как происходит обработка ошибок с помощью jstl?
19.  Как деактивировать использование EL на JSP?
20.  Можно ли использовать javascript на jsp странице?
21.  Всегда ли создается объект сессии на jsp странице, можно ли отключить его создание?
22.  Как можно расширить функциональность jsp?




Servlet (оглавление)

277. Какова структура веб-проекта?
278. Что такое сервлет?
279. Что такое контейнер сервлетов?
280. Каковы задачи, функциональность контейнера сервлетов?
281. Что вы знаете о сервлет фильтрах?
282. Зачем нужны слушатели в сервлетах?
283. Когда вы будете использовать фильтры а когда слушатели?
284. Как обработать исключения, выброшенные другим сервлетом в приложении?
285. Что такое дискриптор развертывания?
286. Как реализовать запуск сервлета с запуском приложения?
287. Что представляет собой объект ServletConfig?
288. Что представляет собой объект ServletContext?
289. В чем отличия ServletContext и ServletConfig?
290. Что такое Request Dispatcher?
291. Как можно создать блокировку (deadlock) в сервлете?
292. Как получить адрес сервлета на сервере?
293. Как получить информацию о сервере с сервлета?
294. Как получить ip адрес клиента на сервере?
295. Что вы знаете о классах обертках (wrapper) для сервлетов?
296. Каков жизненный цикл сервлета и когда какие методы вызываются?
297. Какие методы необходимо определить при создании сервлетов?
298. В каком случае вы будете переопределять метод service()?
299. Есть ли смысл определить конструктор для сервлета, как лучше инициализировать данные?
300. В чем отличия GenericServlet и HttpServlet?
301. Как вызватьиз сервлета другой сервлет этого же и другого приложения?
302. Что вы знаете и в чем отличия методов forward() и sendRedirect()?
303. Стоит ли волноваться о “многопоточной безопасности” работая с сервлетами?
304. Что такое servlet scope (область видимости – время жизни) и какие вы знаете?
305. Что вы знаете и зачем нужны методы java.net.URLEncoder.encode() и decode()?
306. Зачем нужны и чем отличаются методы encodeUrl() и encodeRedirectUrl()?
307. Что такое «сервлет»?
308. В чем заключаются преимущества технологии сервлетов над CGI (Common Gateway Interface)?
309. Какова структура веб-проекта?
310. Что такое «контейнер сервлетов»?
311. Зачем нужны сервера приложений, если есть контейнеры сервлетов?
312. Как контейнер сервлетов управляет жизненным циклом сервлета, когда и какие методы вызываются?
313. Что такое «дескриптор развертывания»?
314. Какие действия необходимо проделать при создании сервлетов?
315. В каком случае требуется переопределять метод service()?
316. Есть ли смысл определять для сервлета конструктор? Каким образом лучше инициализировать данные?
317. Почему необходимо переопределить только init() метод без аргументов?
318. Какие наиболее распространенные задачи выполняются в контейнере сервлетов?
319. Что вы знаете о сервлетных фильтрах?
320. Зачем в сервлетах используются различные listener?
321. Когда стоит использовать фильтры сервлетов, а когда слушателей?
322. Как реализовать запуск сервлета одновременно с запуском приложения?
323. Как обработать в приложении исключения, выброшенные другим сервлетом?
324. Что представляет собой ServletConfig?
325. Что представляет собой ServletContext?
326. В чем отличия ServletContext и ServletConfig?
327. Для чего нужен интерфейс ServletResponse?
328. Для чего нужен интерфейс ServletRequest?
329. Что такое Request Dispatcher?
330. Как из одного сервлета вызвать другой сервлет?
331. Чем отличается sendRedirect() от forward()?
332. Для чего используются атрибуты сервлетов и как происходит работа с ними?
333. Каким образом можно допустить в сервлете deadlock?
334. Как получить реальное расположение сервлета на сервере?
335. Как получить информацию о сервере из сервлета?
336. Как получить IP адрес клиента на сервере?
337. Какие классы-обертки для сервлетов вы знаете?
338. В чем отличия GenericServlet и HttpServlet?
339. Почему HttpServlet класс объявлен как абстрактный?
340. Какие основные методы присутствуют в классе HttpServlet?
341. Стоит ли волноваться о многопоточной безопасности работая с сервлетами?
342. Какой метод HTTP не является неизменяемым?
343. Какие есть методы отправки данных с клиента на сервер?
344. В чем разница между методами GET и POST?
345. В чем разница между PrintWriter и ServletOutputStream?
346. Можно ли одновременно использовать в сервлете PrintWriter и ServletOutputStream?
347. Расскажите об интерфейсе SingleThreadModel.
348. Что означает URL encoding? Как это осуществить в Java?
349. Какие различные методы управления сессией в сервлетах вы знаете?
350. Что такое cookies?
351. Какие методы для работы с cookies предусмотрены в сервлетах?
352. Что такое URL Rewriting?
353. Зачем нужны и чем отличаются методы encodeURL() и encodeRedirectURL()?
354. Что такое «сессия»?
355. Как уведомить объект в сессии, что сессия недействительна или закончилась?
356. Какой существует эффективный способ удостоверится, что все сервлеты доступны только для пользователя с верной сессией?
357. Как мы можем обеспечить transport layer security для нашего веб приложения?
358. Как организовать подключение к базе данных, обеспечить журналирование в сервлете?
359. Какие основные особенности появились в спецификации Servlet 3?
360. Какие способы аутентификации доступны сервлету?
361. Что такое Java Server Pages (JSP)?
362. Зачем нужен JSP?
363. Опишите, как обрабатываются JSP страницы, начиная от запроса к серверу, заканчивая ответом пользователю.
364. Расскажите об этапах (фазах) жизненного цикла JSP.
365. Расскажите о методах жизненного цикла JSP.
366. Какие методы жизненного цикла JSP могут быть переопределены?
367. Как можно предотвратить прямой доступ к JSP странице из браузера?
368. Какая разница между динамическим и статическим содержимым JSP?
369. Как закомментировать код в JSP?
370. Какие существуют основные типы тегов JSP?
371. Что вы знаете о действиях JSP (Action tag и JSP Action Elements).
372. Взаимодействие JSP - сервлет - JSP.
373. Какие области видимости переменных существуют в JSP?
374. Какие неявные, внутренние объекты и методы есть на JSP странице?
375. Какие неявные объекты не доступны в обычной JSP странице?
376. Что вы знаете о PageContext и какие преимущества его использования?
377. Как сконфигурировать параметры инициализации для JSP?
378. Почему не рекомендуется использовать скриплеты (скриптовые элементы) в JSP?
379. Можно ли определить класс внутри JSP страницы?
380. Что вы знаете о Языке выражений JSP (JSP Expression Language – EL)?
381. Какие типы EL операторов вы знаете?
382. Назовите неявные, внутренние объекты JSP EL и их отличия от объектов JSP.
383. Как отключить возможность использования EL в JSP?
384. Как узнать тип HTTP метода используя JSP EL?
385. Что такое JSTL (JSP Standard tag library)?
386. Из каких групп тегов состоит библиотека JSTL?
387. Какая разница между <c:set> и <jsp:useBean>?
388. Чем отличается <c:import> от <jsp:include> и директивы <%@include %>?
389. Как можно расширить функциональность JSP?
390. Что вы знаете о написании пользовательских JSP тегов?
391. Приведите пример использования собственных тегов.
392. Как сделать перенос строки в HTML средствами JSP?
393. Почему не нужно конфигурировать стандартные JSP теги в web.xml?
394. Как можно обработать ошибки JSP страниц?
395. Как происходит обработка ошибок с помощью JSTL?
396. Как конфигурируется JSP в дескрипторе развертывания.
397. Можно ли использовать Javascript на JSP странице?
398. Всегда ли создается объект сессии на JSP странице, можно ли отключить его создание?
399. Какая разница между JSPWriter и сервлетным PrintWriter?
400. Опишите общие практические принципы работы с JSP.






