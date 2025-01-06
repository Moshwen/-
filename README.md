1. Сборка Docker образа
```python
docker build --no-cache --progress=plain -t my-airflow:latest .
```

2. Запуск Docker контейнера
```python
docker run -d -p 8080:8080 my-airflow:latest standalone
```
Чтобы получить доступ к интерфейсу Airflow необходимо перейти по этому адресу:
```python
http://localhost:8080
```
