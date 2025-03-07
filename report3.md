📌 **Отчёт 3 (`report3.md`)**
```md
# Report 3: Управление пользователями и правами доступа

## Основные команды
```sh
sudo adduser max
sudo groupadd bbe_students
sudo usermod -aG bbe_students max
sudo chmod 770 ~/work/project
sudo chown :bbe_students ~/work/project
```
- `adduser` – создание пользователя.
- `groupadd` – создание группы.
- `usermod -aG` – добавление пользователя в группу.
- `chmod` – изменение прав доступа.
- `chown` – смена владельца файла.
```