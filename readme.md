В Prometeus alerts настроены следующие алерты:

на контейнеры:
jenkins_down (1 active)
jenkins_high_cpu (0 active)
jenkins_high_memory (0 active)

на хост:
high_cpu_load (0 active)
high_memory_load (0 active)
high_storage_load (0 active)

monitor_service_down (0 active)

В dashboards grafana 4 дашборда:
Docker Containers (мониторинг контейнеров)
Docker Host (мониторинг хоста с контейнерами)
Monitor Services (мониторинг служб)
Nginx (мониторинг веб-сервера nginx)

в Docker Containers след. метрики:
загрузка CPU , количество ядер, загрузка оперативной памяти, используемое количество оперативной памяти,
загрузка памяти и количество использованной памяти, работоспособность контейнеров, загрузка системы, использование сети.
