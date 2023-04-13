# TestContainers, Kubernetes, облака
## TestContainers. Интеграционное тестирование

![Test containers](https://www.pvsm.ru/images/2017/11/27/integracionnye-testy-dlya-Java-s-pomoshyu-TestContainers-menshe-bezumiya-bolshe-poryadka-i-vsyo-eto-avtomaticheski.png "Test containers")

Интеграционное тестирование Spring Boot @ConditionalOnProperty приложения с помощью TestContainers

Два образа для разных окружений   

Настройки devApp:
- server.port=8080
- profile.dev=true

Настройки prodApp:
- server.port=8081
- profile.dev=false