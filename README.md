## Как установить:

1. установить ansible и настроить ssh ключ на сервере

2. клонировать репозиторий
```
git clone https://github.com/tonkaxxx/superset_pull.git
cd superset_pull
```

3. создать `inventory.ini` по примеру из `inventory-example.ini`

4. поменять переменные в update_repo.yaml (если нужно)

5. запустить плейбук
```
ansible-playbook -i inventory.ini update_repo.yaml
```