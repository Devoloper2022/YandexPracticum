# YandexPracticum

# S2 T8 L3

- Создайте мультимодульный Gradle-проект с двумя модулями — model и service. Напомним, что в отличие от Maven, в дочерних модулях на родительский ссылаться необязательно. Достаточно указать субмодули в файле settings.gradle родительского проекта.
- В модуле model создайте какой-нибудь record-класс. Например, Phone:

```
public record Phone(
    String manufactorer,
    String model,
    BigDecimal price
) {}
```

- Не собирайте модуль, так как мы хотим убедиться, что он подключится к другому модулю и без этого.
- Подключите модуль model зависимостью в service. Убедитесь, что класс-модель из модуля model доступен, хоть и не был добавлен в локальный репозиторий.
- Напишите простейший код по выводу в консоль нескольких инстансов класса-модели из модуля model.
- Соберите весь проект.
- По желанию: создайте циклическую зависимость, добавив в модуль model зависимость на service. Попробуйте собрать проект.
