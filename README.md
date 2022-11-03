# Кеширование Redis/memcached

---
### Задание 1. Кэширование.
*Приведите примеры проблем, которые может решить кэширование.*

Кэширование может ускорить загрузку веб-страниц с огромным количеством медиафайлов, или веб-приложений, которые часто открываются и занимают много (по современным меркам) времени.
Кэширование может может ускорить большие и тяжелые запросы из БД, например выполнение каких-либо представлений с кучей JOIN, где объем строк может исчисляться миллионами, а слишком долгий ответ будет нерелевантен, поэтому кэширование может помочь.
На крупнейших онлайн-ресурсах, где объем покупок может достигать тысяч в секунду, трафик может проваливаться, что негативно скажется на репутации магазина. Либо информация о количестве ходовых товаров в наличии будет запаздывать, и нужен оперативный ответ сервера. Здесь также поможет кэширование.

---
### Задание 2. Memcached.
*Установите и запустите memcached.*
*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

![memcached](https://github.com/INRI03/Redis-Memcached/blob/main/02.png)

---
### Задание 3. Удаление по TTL в Memcached.
*Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.*
*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

![memcached_keys](https://github.com/INRI03/Redis-Memcached/blob/main/03.png)

---
### Задание 4. Запись данных в Redis.
*Запишите в redis несколько ключей с любыми именами и значениями.*
*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

![redis_keys](https://github.com/INRI03/Redis-Memcached/blob/main/04.png)
