# Client-server with C#
Learning how to create simple client-server app (C#, WPF, WCF, MySQL, Entity Framework)


## Description

All development has been produced using Visual Studio 2019 and MySQL Workbench 8

Client's solution (.sln) located in `ObserverClient` directory, as well as project (WPF).<br>
Server's solution - in `ObserverService` directory (WCF) <br>
Server console application stored in `ObserverServiceHost` directory.

I havent build release version yet, so all functionality in Debug.

There's a sql script (`CreateDB.sql`) that creates a mysql database. </br>
Usage: </br>
```mysql -u <username> -p < CreateDB.sql```



Dependencies:
 - MySQL .Net Connector
 - Entity Framework
 - MailKit
 - WinForms (Only for DateTimePicker)
 - Twilio (SMS-notifier, still in progress)

## Useful links

### WPF
  * [WPF Lessons](https://metanit.com/sharp/wpf/1.php)
  * [MVVM + WPF](https://habr.com/ru/post/338518/)
  *[UWP - технология для создания приложений под Win10](https://metanit.com/sharp/uwp/1.1.php)
  * [Quick start with WPF](https://habr.com/ru/post/427325/)
  
  * [Компоненты, которых не хватает в WPF](https://github.com/xceedsoftware/wpftoolkit)
  * [Syncfusion's DateTimePicker](https://help.syncfusion.com/wpf/datetimepicker/getting-started)
  * [DateTimePicker](https://github.com/xceedsoftware/wpftoolkit/wiki/DateTimePicker)
  * [Installation](https://github.com/xceedsoftware/wpftoolkit/wiki)

  * [Подключение DateTimePicker из WinForms в WPF](https://ru.stackoverflow.com/questions/489988/datetimepicker-и-wpf)
  * [TimePicker](https://jobijoy.blogspot.com/2007/10/time-picker-user-control.html)
  * [Another TimePicker](http://jesseliberty.com/2009/03/28/toolkit-control-–-timepicker/)
  * [One another DateTimePicker](https://gist.github.com/qwertie/1150228)
  * [DateTimePicker for WPF like in WinForms](https://www.codeproject.com/Articles/132992/A-WPF-DateTimePicker-That-Works-Like-the-One-in-Wi)

### Filter
  * [Filter DataGrid](https://stackoverflow.com/questions/15568325/filter-a-datagrid-in-wpf)
  * [Filter list](https://stackoverflow.com/questions/10745900/filter-a-list-by-another-list-c-sharp)
  
### WCF  
  * [IIS Architecture](https://habr.com/ru/post/189086/)
  * [WCF(RIA Services) - helps spend less time with data-sending side](https://habr.com/ru/post/203820/)
  * [Simple client-server WCF example](https://vc.ru/dev/177588-prostoy-i-nadezhnyy-c-klient-server-ispolzuya-wcf)
  * [One other client-server example](http://www.devowl.net/2017/07/WCF-service-csharp-client-server.html)
  * [Пример создания WCF сервиса работающего внутри службы Windows](https://habr.com/ru/post/331952/)
  * [Создание WCF(Rikrop) client-server архитектуры](https://habr.com/ru/post/246961/)
  * [Видео уроки (плейлист) по созданию приложений](https://youtu.be/QmfPmqMk9Xs?list=PL6n9fhu94yhVxEyaRMaMN_-qnDdNVGsL1)
  * [Создание простого сервиса](https://sohabr.net/habr/post/264889/#exeTestClient)

  * [WCF Internal ERROR](https://social.msdn.microsoft.com/Forums/vstudio/en-US/dc5f5b05-ff50-48dc-bf17-b39e60575af1/wcf-error-the-server-was-unable-to-process-the-request-due-to-an-internal-error?forum=wcf)
  
  * [Using array in WCF](https://social.msdn.microsoft.com/Forums/en-US/43b6cb9b-8253-46da-b3e7-26e9c975c929/how-to-use-array-in-wcf?forum=wcf)
  * [Sending large files in WCF](https://www.codeproject.com/Questions/365160/how-to-send-byte-array-more-tha-20kb-to-wcf-servic)
  * [Load files over HTTP](https://www.codeproject.com/Articles/166763/WCF-Streaming-Upload-Download-Files-Over-HTTP)
  * [WCF & WPF Chat App](https://www.codeproject.com/Articles/19752/WCF-WPF-Chat-Application)

### Additional
  * [REST vs SOAP](https://habr.com/ru/post/131343/)
  * [Changing between pages](https://stackoverflow.com/questions/24932864/change-between-pages-in-wpf)

### Database
* [Визуальное проектирование БД в MySQL WorkBench](https://habr.com/ru/post/175985/)
* [Как работает РБД](https://habr.com/ru/company/mailru/blog/266811/)
* [WCF Service + DB](https://tekslate.com/example-create-wcf-service-data-base)
* [WPF + EF](https://metanit.com/sharp/wpf/19.3.php)
* [WCF + WPF + EF](https://stackoverflow.com/questions/10806081/good-example-of-combining-wpf-wcf-entity-framework)
* [Dynamic MySQL Connection for EF](https://stackoverflow.com/questions/20277677/dynamic-mysql-database-connection-for-entity-framework-6)
* [Connect to MySQL DB](https://stackoverflow.com/questions/21618015/how-to-connect-to-mysql-database)
* [Connect C# to MySQL](https://www.codeproject.com/Articles/43438/Connect-C-to-MySQL)

### JSON
* [JOIN in EF](https://stackoverflow.com/questions/21051612/entity-framework-join-3-tables)
* [JSON](https://docs.microsoft.com/ru-ru/dotnet/standard/serialization/system-text-json-how-to?pivots=dotnet-5-0)
* [Jquery + Json + EF + WCF](https://stackanswers.net/questions/sending-array-of-objects-to-wcf)

### SMTP
* [Работа с SMTP](https://metanit.com/sharp/net/8.1.php)
