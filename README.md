# CleanArchitecture.Identity
Продолжение лабораторного проекта CleanArchitecture по видео Platinum DEV: [Разработка Web API на ASP.NET Core 5 и .NET 5 "Web Api профессионально".](https://www.youtube.com/playlist?list=PLEtg-LdqEKXbpq4RtUp1hxZ6ByGjnvQs4)

Проект разделен на 3 части:
- [CleanArchitecture.Backend](https://github.com/barbado-vl/CleanArchitcture.Backend) - основной web api c моделью, логикой, тестами и RESTful API.
- CleanArchitectue.Identity - web api для аутентифкации и авторизации, использующий IdentityServer4.
- [CleanArchitectue.Frontend](https://github.com/barbado-vl/CleanArchitecture.Frontend) - простенький интерфейс для пользователя, чтобы протестировать работу всего приложения.

Вынесли Аутентификация и Авторизация в отдельный Web API сервис, чтобы не нагружать другие Web API дополнительными функциями, логикой, схемами данных.

Тип архитектуры: ASP.NET Core MVC.

Используем протокол OpenIdConnect. Его реализация -- пакет IdentityServer4.

Реализованные задачи:
- IdentityServer4.
- База Данных.
- Модель.
- Cookie.
- Controllers.
- Views.
- Styles.
- Валидация.

