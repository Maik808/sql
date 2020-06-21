## SQL
### Начало работы.
* Запустить контейнер с mysql командой `docker-compose up`
* Запустить приложение командой:
    ```
    java -jar artifacts/app-deadline.jar -P:jdbc.url=jdbc:mysql://localhost:3306/app -P:jdbc.user=app -P:jdbc.password=pass
    ```
* Запустить автотесты.
* Для повторного запуска тестов предварительно нужно перезапустить контейнер и приложение.
