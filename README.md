haproxy_hw  
## Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»  
# Задание 1  

Запустите два simple python сервера на своей виртуальной машине на разных портах  
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке  
Настройте балансировку Round-robin на 4 уровне.  
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.  

https://github.com/neo-13th/haproxy_hw/blob/main/haproxy.cfg  

![n2](https://github.com/neo-13th/haproxy_hw/assets/150372172/8618888c-5a06-4ae7-b9f8-ae55c6b2cca5)  


# Задание 2  
Запустите три simple python сервера на своей виртуальной машине на разных портах  
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4  
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local  
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.  

https://github.com/neo-13th/haproxy_hw/blob/main/haproxy2.cfg  

 ![n4](https://github.com/neo-13th/haproxy_hw/assets/150372172/ca51370d-9f93-47a5-9033-a3e249634bd8)  


