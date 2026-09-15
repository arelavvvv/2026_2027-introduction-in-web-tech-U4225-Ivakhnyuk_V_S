# Отчет по второй лабораторной
## Ход работы

После конфигурации prometheus запускаем node-exporter

![alt text](image.png)

Запускаем prometheus предварительно добавив node-exporter в сеть контейнеров

![alt text](VLi2nzgtWY.png)

Запускаем grafana, добавляем prometheus как источник, указав ip назначенный ему в сети monitoring

![alt text](24wJ6EaMxR.png)

Результат добавления метрики node_cpu_seconds_total представлен на скриншоте ниже

![alt text](yhJR4WEnJw.png)

Так же добавляем, node_memory_Active_bytes и node_disk_read_bytes_total скрыв node_cpu_seconds_total для удобства отображения

![alt text](zLX7yQUDXq.png)