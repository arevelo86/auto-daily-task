# auto-daily-task

Repositorio de ejemplo para ejecutar una tarea diaria mediante GitHub Actions.

Archivos incluidos:
- README.md
- .gitignore
- scripts/daily-task.sh
- .github/workflows/daily.yml

La workflow `daily.yml` ejecuta `scripts/daily-task.sh` una vez al día (cron) y permite ejecuciones manuales.
