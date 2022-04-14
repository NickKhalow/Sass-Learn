# Установка

## Npm

Переходим на сайт https://nodejs.org/en/download/
И ставим пакет
Работает для Windows, Mac и Linux

После установки npm прописываем 
 
```
npm install -g sass 
//-g значит глобально
```

## Git dart-sass

Качаем архив https://github.com/sass/dart-sass/releases/tag/1.20.1 для своей OS

Распаковываем в любую папку

Добавляем PATH (опционально)
- MacOS \
https://phoenixnap.com/kb/set-environment-variable-mac
- Linux (Ubuntu) \
https://askubuntu.com/questions/730/how-do-i-set-environment-variables
- Windows \
https://phoenixnap.com/kb/windows-set-environment-variable

# Sass компиляция в Css

## Вручную

```
sass source.sass output.css
```

## Авто

Компиляция одного файла

```
sass --watch source.sass output.css
```

Компиляция файлов в директории
Используем флаг --no-source-map если не хотим генерировать .map файлы

```
sass --watch source_sass_dir:output-css_dir
```