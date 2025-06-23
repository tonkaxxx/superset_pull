## Как установить:

1. клонировать репозиторий
```
git clone https://github.com/tonkaxxx/superset_pull.git
cd superset_pull
```

2. создать `inventory.ini` по примеру из `inventory-example.ini`

3. поменять переменные в update_repo.yaml (если нужно)

4. запустить плейбук
```
ansible-playbook -i inventory.ini update_repo.yaml
```