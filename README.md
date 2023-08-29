1.Проект "Персональний помічник", існує як пакет у системі, 
встановлений в системі poetry, та використовує версію Python 3.11.
Запуск застосунку:
poetry run py __main__.py

2. Dockerfile
Запуск контейнера за допомогою dockerfile робив в іншому каталозі
Команди для створення image/contaner та запуску застосунку:
python -m venv env 
env\Scripts\activate
python -m pip freeze > requirements.txt
docker build . -t anatolii6974/address-book-docker
sha256:e14530322fbe75eb9c4734156b56a4b60b034f9a7d4fae108efd5e43045a7044
docker run -it e145

