# emailaddres

Создание временного email 
```bash
tmpmail
```
Выведет временный email, например: yourrandom@mail.com

Просмотр входящих писем
```bash
tmpmail -l
```

Открытие письма
```bash
tmpmail -r 1 -> Открывает письмо с ID 1.
```

Как скачать 
```bash
   sudo apt update
   sudo apt install curl jq
```
```bash
   wget -O tmpmail https://raw.githubusercontent.com/sdushantha/tmpmail/master/tmpmail
   chmod +x tmpmail
   sudo mv tmpmail /usr/local/bin/
```


