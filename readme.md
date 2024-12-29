### DockerRun
```sh
sh scripts/build.sh && exit # Сборка проекта
```
```sh
sh scripts/start.sh && exit # Запуск проекта
```
```sh
sh scripts/stop.sh && exit # Остановка проекта
```
<details class="block"><summary>Docker mirrors</summary>

- Добавить зеркала для Docker (Windows: `%USERNAME%\.docker\daemon.json`)
```text
"registry-mirrors": [
    "https://huecker.io",
    "https://dockerhub.timeweb.cloud",
    "https://daocloud.io",
    "https://mirror.gcr.io"
]
```

### Homeworks

Домашняя работа 14. Промежуточная аттестация

```console

docker exec -it laravel bash
php artisan db:seed
npm i
nmp run build

```


