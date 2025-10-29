# Модель музыкальных рекомендаций на основе KMeans Clustering

Этот проект создает **простую систему рекомендаций** на основе треков в Spotify, используя кластеризацию
!!!to be updated!!!

Содержимое репозитория:

- **spotify_recommender.ipynb** - ноутбук с обучением модели
- **spotify_songs.csv** - тренировочные данные
- **spotify_with_clusters.csv** - новые данные с кластерами
- **kmeans_model.joblib** - файл обученной модели для импорта
- **imputer.joblib и scaler.joblib** - файлы для препроцессинга
- **requirements.txt** - файл для установки зависимостей
- **README.md** - readme

## Запуск
```bash
pip install -r requirements.txt
jupyter notebook spotify_recommender.ipynb