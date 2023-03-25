# FaceID Backend

Проект - бэкэнд для обработки времени прихода и ухода с работы по лицу.
Фото лица делается из мобильного приложения.

Подробности смотреть в [Wiki](https://github.com/smart48ru/FaceIDBackend/wiki) проекта.

Конфигурационный файл ищется по пути `$./cfg/config.yaml`. Пример конфига:

```yaml
---
api:
  host: "127.0.0.1"
  port: 8080
  program_key: "ProgAuthDevKey"
  admin_key: "AdminAuthDevKey"
  read_time_out: 40
  write_time_out: 20
  read_head_time_out: 50
db:
  enable: false
  host: "127.0.0.1"
  port: 5432
  user: "devUser"
  password: "devUserPassword"
  dbname: "faceid"
  ssl_mode: false
```
