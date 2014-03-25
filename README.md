#Phots

Adding timestamp (+%Y/%m/%d %H:%M) for photos.

Добавляет временную метку на фото (дата, когда фото было сделано). Берется дата из exif или имени файла.

##Usage

    chmod +x phots
    mkdir dist_dir
    ./phots src_dir dist_dir

где src_dir - папка с фотографиями, dist_dir - папка для сохранения фото

##Depends

imagemagick, exiv2
