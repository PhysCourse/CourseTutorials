# CourseTutorials

В этом файле будет рассказано как все установить и оформлять.

## Установка

- Установка пакета mkdocs и расширения material
```bash
    pip install mkdocs
    pip install mkdocs-material
```


## Структура проекта

```text
Book/
├──mkdocs/ # Это корень: все файлы проекты индексируются отсюда
|  ├──Chapter1/
|  |  ├──P1.md
|  |  ├──P2.md
|  |  └──P3.md
|  ├──css/ # опционально, если захочется менять стили
|  ├──javascripts/
|  |  └──mathjax.js #пригодится для подключения математики
└──mkdocs.yml # файл со всей конфигурацией: индексация страниц, плагины итд. 
```

!!! info "Superfence"
    Text in superfence