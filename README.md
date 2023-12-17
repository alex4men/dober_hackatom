# YOLOv8-FastAPI:
Нейросетевой сервис команды DoberTeam специально для Атомик Хака 2023, кейс поиск дефектов.

# Что внутри:

- YOLOv8: A popular real-time object detection model
- FastAPI: A modern, fast (high-performance) web framework for building APIs
- Docker: A platform for easily building, shipping, and running distributed applications

<img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/yolo-comparison-plots.png"></a>

---
# Установка и запуск

## Через докер

```
docker-compose up
```

## Локально

1. Установите требуемые зависимости:

```
pip install -r requirements.txt
```
2. Запустите приложение:
```
uvicorn main:app --reload --host 0.0.0.0 --port 8001
```  
*Вы можете изменить порт в файле **docker-compose.yaml***

## FAST API Docs url:
http://0.0.0.0:8001/docs#/
