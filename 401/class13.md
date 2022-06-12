Reading
Related data in Spring (only read section “3. One-to-Many Relationship”)

Baeldung: Spring Integration Testing

Testing is an integral part of enterprise software development. This chapter focuses on the value added by the IoC principle to unit testing and on the benefits of the Spring Framework’s support for integration testing. (A thorough treatment of testing in the enterprise is beyond the scope of this reference manual.)

Dependency injection should make your code less dependent on the container than it would be with traditional Java EE development. The POJOs that make up your application should be testable in JUnit or TestNG tests, with objects instantiated by using the new operator, without Spring or any other container. You can use mock objects (in conjunction with other valuable testing techniques) to test your code in isolation. If you follow the architecture recommendations for Spring, the resulting clean layering and componentization of your codebase facilitate easier unit testing. For example, you can test service layer objects by stubbing or mocking DAO or repository interfaces, without needing to access persistent data while running unit tests.

True unit tests typically run extremely quickly, as there is no runtime infrastructure to set up. Emphasizing true unit tests as part of your development methodology can boost your productivity. You may not need this section of the testing chapter to help you write effective unit tests for your IoC-based applications. For certain unit testing scenarios, however, the Spring Framework provides mock objects and testing support classes, which are described in this chapter.