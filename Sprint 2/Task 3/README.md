# YandexPracticum

# S2 T8 L4

1.  Создайте директорию и положите в неё простейший pom.xml.

- Прекод:

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
<modelVersion>4.0.0</modelVersion>
<groupId>ru.yandex</groupId>
<artifactId>simplest-project</artifactId>
<version>1.0-SNAPSHOT</version>
<packaging>pom</packaging>
</project>

2.  Сгенерируйте Maven-враппер с версией, отличной от той, что вы используете.
3.  Запустите любую команду, используя враппер, например ./mvnw verify.
4.  Будет скачана требуемая версия Maven и использована для выполнения команды. Убедитесь в этом, проверив директорию — ~\.m2\wrapper\dists.
5.  Попробуйте воспользоваться враппером ещё раз. В этот раз дистрибутив скачан не будет, а произойдёт использование имеющегося в ~\.m2\wrapper\dists.
