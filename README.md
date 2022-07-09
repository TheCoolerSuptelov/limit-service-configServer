# limit-service-configServer
In28Minutes Spring Cloud course. Limit service config server


# Конспект
В application.properties описан репозиторий, в который клауд конфиг идет за пропсами.
URL GET http://localhost:8888/limits-service/default - чтобы достать пропсы из git"а.
Для включения этой магии надо, чтобы в классе стартере приложения была указана аннотация @EnableConfigServer

