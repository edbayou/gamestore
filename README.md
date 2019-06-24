# gamestore
Сайт сделан на платформе ASP.NET MVC5 (.NET Framework 4.6.1)
Представляет собой магазин компьютерныз игр
реализован список товаров
и админ панель (CRUD) доступная по адресу //Admin/Index 
(name="admin" password="12345")
В проекте также имеются тесты.
База Данных называется GameStore, а сама таблица Game.
для создания  таблицы Game в базе данных нужно вести SQL запрос из файла SQLQuery/SQLQuery1.sql
для заполнения таблицы данными нужно вести SQL запрос из файла SQLQuery/SQLQuery2.sql

Так же в командной строке NuGet были установлены следующие пакеты

Install-Package Ninject -version 3.0.1.10 -projectname GameStore.WebUI
Install-Package Ninject.Web.Common -version 3.0.0.7 -projectname GameStore.WebUI
Install-Package Ninject.MVC3 -Version 3.0.0.6 -projectname GameStore.WebUI
Install-Package Ninject -version 3.0.1.10 -projectname GameStore.UnitTests 
Install-Package Ninject.Web.Common -version 3.0.0.7 -projectname GameStore.UnitTests
Install-Package Ninject.MVC3 -Version 3.0.0.6 -projectname GameStore.UnitTests
Install-Package Moq -version 4.1.1309.1617 -projectname GameStore.WebUI
Install-Package Moq -version 4.1.1309.1617 -projectname GameStore.UnitTests
Install-Package Microsoft.Aspnet.Mvc -version 5.0.0 -projectname GameStore.Domain
Install-Package Microsoft.Aspnet.Mvc -version 5.0.0 -projectname GameStore.UnitTests
Install-Package EntityFramework -projectname GameStore.Domain
Install-Package EntityFramework -projectname GameStore.WebUI
Install-Package -version 3.0.0 bootstrap -projectname GameStore.WebUI
Install-Package Microsoft.jQuery.Unobtrusive.Validation -version 3.0.0 -projectname GameStore.WebUI
