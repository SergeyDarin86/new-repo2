# $${\color{blue}Поисковый \space \color{blue} движок}$$
![фото](https://github.com/SergeyDarin86/new-repo2/blob/master/Dashboard1.png?raw=true)
## 2. Описание проекта
  👆 _Данное приложение позволяет <b>индексировать</b> страницы сайтов  и осуществлять по ним быстрый поиск слов и фраз, вводимых пользователем в запросе._ 
  - _Программа <b>обходит</b> все страницы сайта (сайтов), указанного в конфигурационном файле в многопоточном режиме, <b>сохраняет</b> их содержимое в таблицы в базе данных._
  - _В проекте реализована <b>система индексации</b> (процесс формирования <b>поискового индекса</b> по некоторому объёму информации) страниц сайта, которая позволит подсчитывать встречающиеся на страницах сайта слова (точнее, их леммы) и по поисковому запросу определяет наиболее релевантные страницы._
  ><b>Поисковый индекс</b> — это специальным образом организованная база данных (в нашем случае — база данных MySQL), позволяющая быстро и удобно осуществлять поиск по этой информациию
  - _Реализована система поиска информации с использованием созданного <b>поискового индекса</b>. Метод поиска учитывает, по каким сайтам происходит этот поиск — по всем или по тому, который выбран в веб-интерфейсе в выпадающем списке._
    
## 3. Демо (изображения, ссылки на видео, интерактивные демо-ссылки)
  - содержимое данного блока
  - :+1: This PR looks great - it's ready to merge! :shipit:
    
## 4. Технологии в проекте
  - <img src="nature_spring.png" alt="drawing" width="25"/> Поисковый движок разработан на фреймворке <b>Spring Boot</b>
  - <img src="maven.png" alt="drawing" width="25"/> Сборщик <b>Maven</b> с подключением шаблонизатора <b>Thymeleaf</b>
  - <img src="mysqlworkbench.png" alt="drawing" width="25"/> Реляционная база данных <b>MySQL</b>
  - <img src="restApi.png" alt="drawing" width="25"/> Архитектура <b>REST</b>

## 5. Что-то характерное для проекта (проблемы с которыми пришлось столкнуться, уникальные составляющие проекта)
  - содержимое данного блока

## 6. Техническое описание проекта (Установка, настройка, как помочь проекту)
  - содержимое данного блока
  - для улучшения проекта необходимо подключить LuceneMorphology на английском языке, чтобы поиск также осуществлялся на английском
