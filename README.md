# Rate my cat - Software Testing - JUnit

This project contains a complete sample application for the book [Mastering Software Testing with JUnit 5]. It consists on a web application in which end uses can rate a list of cats by watching its name and picture. The rate shall be done once per end user using a star mechanism. Optionally, comments can be made per cat. This application has been built using the following technologies:

* Spring Framework, as application framework: Spring Boot, Spring MVC + Thymeleaf, Spring Data JPA, and Spring Test (for integration tests).
* JUnit 5, as testing framework.
* Hamcrest, for improving the readability of assertions.
* Selenium WebDriver, for end-to-end testing.

The screenshots below show the application GUI in action.

![Screenshot 1][Screeshot 1]
![Screenshot 2][Screeshot 2]

## Steps to run

```bash
gradlew bootRun
```

[Screeshot 1]: https://raw.githubusercontent.com/bonigarcia/rate-my-cat/master/doc/rate-my-cat-screeshot-1.png
[Screeshot 2]: https://raw.githubusercontent.com/bonigarcia/rate-my-cat/master/doc/rate-my-cat-screeshot-2.png
[Mastering Software Testing with JUnit 5]: https://www.amazon.com/Mastering-Software-Testing-JUnit-Comprehensive-ebook/dp/B076ZQCK5Q

## References

[Boni Garcia's Rate my Cat](https://github.com/bonigarcia/rate-my-cat)