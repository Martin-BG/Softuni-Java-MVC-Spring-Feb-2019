# Java MVC Frameworks - Spring - Feb 2019
[**Java MVC Frameworks - Spring** course at SoftUni - February 2019](https://softuni.bg/trainings/2295/java-mvc-frameworks-spring-february-2019)

## Projects

### [**Real Estate Agency**](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/tree/master/01.%20Spring%20Boot%20Introduction/Exercises/Real%20Estate%20Agency)

[Simple](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/01.%20Spring%20Boot%20Introduction/01.%20Spring%20Boot%20Introduction%20-%20Exercises.pdf) Spring Boot application using Spring Data.
* [Customized MySQL dialect](https://stackoverflow.com/a/54993738/7598851) - changed default charset and collation 
* [Optimized](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/01.%20Spring%20Boot%20Introduction/Exercises/Real%20Estate%20Agency/src/main/java/org/softuni/realestate/domain/enities/BaseUuidEntity.java) UUID primary keys representation in database - use BINARY(16) type instead of VARCHAR(36)
___
### [**EXODIA**](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/tree/master/02.%20Spring%20Essentials/Exercises/exodia)

[Simple](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/02.%20Spring%20Essentials%20-%20Exercise.pdf) Spring Boot application, custom security, MD to PDF conversion and file download, Thymeleaf templating and fragments.
* Password hashing with [Jargon2](https://github.com/kosprov/jargon2-api)
* Thymeleaf [templating](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/tree/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/resources/templates) and fragments
* Simple security by custom class/method [annotation](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/annotations/AuthenticatedUser.java) and [interceptor](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/web/interceptors/AuthenticatedInterceptor.java)
* Convert MD to PDF format with [Markdown2Pdf](https://mvnrepository.com/artifact/eu.de-swaef.pdf/Markdown2Pdf)
* [PDF file](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/web/controllers/DocumentController.java) download
* Custom [@Layot](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/annotations/Layout.java) annotation and [Interceptor](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/web/interceptors/ThymeleafLayoutInterceptor.java) for templating and fragments insert
* Implemented Builder Pattern for [AuthenticatedInterceptor](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/web/interceptors/AuthenticatedInterceptor.java) and [ThymeleafLayoutInterceptor](https://github.com/Martin-BG/SoftUni-Java-MVC-Frameworks-Spring-Feb-2019/blob/master/02.%20Spring%20Essentials/Exercises/exodia/src/main/java/org/softuni/exodia/web/interceptors/ThymeleafLayoutInterceptor.java):
