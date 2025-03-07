📌 **Отчёт 4 (`report4.md`)**
```md
# Report 4: Подключение по SSH

## Настройка SSH-сервера
```sh
sudo apt update && sudo apt install openssh-server -y
sudo systemctl enable ssh
sudo systemctl start ssh
```
## Подключение к серверу по SSH
```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
ssh-copy-id admin@192.168.X.X
ssh admin@192.168.X.X
```
## Описание команд
- `ssh-keygen` – создание ключей.
- `ssh` – подключение к серверу.
- `ssh-copy-id` – копирование публичного ключа на сервер.
```