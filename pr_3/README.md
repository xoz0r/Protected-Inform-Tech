Отчет выполнил студент группы ББМО-01-23 Бакин Д.И.

### Загрузка

```
git clone https://github.com/Ivanhahanov/InformtionsSecurityMethodsAndTools.git
```
![Загрузка](https://github.com/xoz0r/Protected-Inform-Tech/assets/145142526/ee4fe80a-8b48-4f62-8eb5-5fe4bb7dd9c0)

### Развертывание

1. Запустить Honeypot

```
cd Deception
docker-compose up
```
![Развертывание 1](https://github.com/xoz0r/Protected-Inform-Tech/assets/145142526/c88063f3-176f-48dd-bb11-8a2d3a621c16)

Запускаем Honeypot для отслеживания активности злоумышленника

2. Сделать файл исполняемым и запустить

```
chmod +x hackersActivity
./hackersActivity
```
![Развертывание 2](https://github.com/xoz0r/Protected-Inform-Tech/assets/145142526/1664979a-0553-44ce-a253-9eafd63321da)

Запускаем файл, который будет имитировать активность злоумышленника

3. Открыть логи honeypot

```
docker-compose logs -f
```

![Развертывание 3](https://github.com/xoz0r/Protected-Inform-Tech/assets/145142526/f2399abb-9134-4208-8834-45ab31cf60e8)

Наблюдаем за действиями злоумышленника, которые выводит Honeypot
