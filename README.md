# actors_recognition
Face recognition of actors

Перед использование необхимо установить все зависимости из req.txt

Структура проекта:

    - req.txt - зависимости, которые нужно установить, чтобы запустить проект
    
    - dataset - содержит изображения лиц шести актеров, организованные в подкаталоги на основе их соответствующих имен.
    
    - examples - имеет три изображения лиц для тестирования, которых нет в наборе данных.
    
    - output - здесь можно сохранять обработанные видео с распознаванием лиц и текстовый файл с данными
    
    - videos - входящие видео должны храниться в этой папке
    
    дополнительные 5 файлов в корневом каталоге
    
    - encode_faces.py - кодировки (128-d векторы) для лиц создаются с помощью этого скрипта
    
    - recognize_faces_image.py - распознавать лица на одном изображении (на основе кодировок из набора данных)
    
    - recognize_faces_video_file.py -  распознавать лица в видеофайле, и выводить обработанное видео в папку output
    
    - encodings.pickle - кодировки распознавания лиц генерируются из набора данных через encode_faces.py (должен появиться после выполнения)
    
 
