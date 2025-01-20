  

## Платформы разработки

  

- **.NET Core**: использует ASP.NET

- **.NET Framework**: использует WCF

  

## Процесс разработки

  

1. Создание в конфигураторе

2. Настройка пространства имен

3. Реализация бизнес-логики

4. [[authentication-methods|Настройка аутентификации]]

  

## Вызов веб-сервиса

  

### Клиентская часть

```javascript

var config = {

    serviceName: "ClassName",

    methodName: "MethodName",

    callback: CallbackFunction,

    data: PayloadWithParameters,

    scope: Context

};

```

  

### Браузер

- Шаблон: `[Адрес системы]/ServiceModel/[Название]/[Метод]`

  

[[web-services-overview|← К обзору веб-сервисов]]