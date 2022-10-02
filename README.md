# minica 🔑🔒🛡️

Самый простой генератор самоподписанных сертификатов

Оригинальный репозиторий автора:
[https://github.com/jsha/minica](https://github.com/jsha/minica)

Сертификаты генерируются на 2 года и 30 дней. Максимальный срок согласно политики Apple

## Сборка

`go build -o ./dist/minica`

или установка

`go install`

## Использование

`minica --domains domain.com --cn host.cloud`

Сгенерирует корневой ключ и сертификат в minica-key.pem и minica.pem, 
затем сгенерирует и подпишите ключ конечного домена и сертификат, сохранив их в ./domain.com/

