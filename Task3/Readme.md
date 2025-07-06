#### Список требований, которым должны удовлетворить внешние интеграции:
- Передача персональных и биометрических данных собственников в обезличенном или зашифрованном виде
- Использование защищенных каналов связи с авторизацией
- Журналирование и мониторинг критичных действий собственников и самих устройств
- Ограничение доступа к системе (ролевая политика)

#### Протоколы аутентификации и авторизации:
- HTTPS
- OAuth 2.0/OpenID Connect
- JWT с ограниченным сроком жизни

#### Взаимодействие между системами предприятия и внешней платформой:
- Синхронной взаимодействие по REST API в формате JSON
- Веб-сокеты для реального отображения состояния устройств
- MQTT протокол для взаимодействия с самими устройствами

[Диаграмма контекста drawio](https://github.com/Ferret56/architecture-propdevelopment/blob/sprint_7/Task3/smart_house_context_diagram.drawio)  
[Диаграмма контекста png](https://github.com/Ferret56/architecture-propdevelopment/blob/sprint_7/Task3/smart_house_context_diagram.png)


[Диаграмма контейнеров drawio](https://github.com/Ferret56/architecture-propdevelopment/blob/sprint_7/Task3/smart_house_container_diagram.drawio)  
[Диаграмма контекста png](https://github.com/Ferret56/architecture-propdevelopment/blob/sprint_7/Task3/smart_house_container_diagram.png)
