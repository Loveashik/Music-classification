## Кластеризация 

### Подготовка данных
`genres.xlsx`  - изначальный файл с названиями музыкальных произведений и их жанровой принадлежностью
`data_preparation_clu.ipynb` - код для предобработки данных. Включает в себя коррекцию жанров, исправление названий и пр. 

### Извлечение признаков
`feature_extraction_clu.ipynb` - код для извлечения признаков из каждого музкального произведения и записи их в отдельный файл 
`genres_for_cluster.csv` - файл с исправленными названиями и скорректированными жанрами

### Кластеризация
`dataset.csv` - данные о признаках музыкальных произведений, разделённых на части по 10 секунд
`music_clasterization_final_clu.ipynb` - код для кластеризации музыкальных произведений по 52 признакам.
 