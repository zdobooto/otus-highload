# locustio (http-тесты)

Установка locustio

```bash
pip3 install locustio
```

Если ссылка для теста такая
[http://10.51.21.56:8080/zabbix/index.php?enter=guest](http://10.51.21.56:8080/zabbix/index.php?enter=guest)

то запускать нужно так

```bash
locust -f locust_zabbix.py --host=http://10.51.21.56:8080
```

После этого для запуска тестирования через web-интерфейс открываем [http://localhost:8089](http://localhost:8089), выставляем желаемые параметры и запускаем тест.