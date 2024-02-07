# ***Шпаргалка по Git и Markdown***

* # **Git.**
git version - вывод версии программы.   
git init - инициализация папки с файлами, выполняется только один раз в начале.   
git log - журнал изменений. 
git status - текущее состояние.  
git commit -m "комментарий" - сохранение состояния с комментарием.  
git add имя файла - добавить файл для отслеживания.  
git add . или git add all - добавить все файлы текущей папки для отслеживания.  
git cd имя папки - смена текущей папки. 
git checkout имя ветви  - переключение между ветвями.   
git checkout +первые четыре символа имя комита - переключение между комитами.  
git branch - вывод ветвей  
git branch имя ветви - создать новую ветвь. 
git branch -d branch имя ветви - удалить ветвь с именем.  
git branch -b имя ветви  - создать ветвь и перейти на нее.    
git merge branch имя ветви - слияние ветви с основной.  
git log --graph  - вывод журнала изменений с графом.    

чтобы выйти из команды git log нажать q    
clear - очистка терминала   
.gitignore.md - записать  в файл имена файлов для иннорирования. 

всегда перед переходом на другую ветвь делать commit.   

*не забывать использовать tab для ускорения заполнения команды.*




* # **Markdown**    
*Курсив*  * *  или _Курсив_ _ _  
**Полужирный**  ** ** или __Полужирный__ __ __     
Заголовок #  перед текстом  
Заголовок меньшим текстом ##    
Список *  перед текстом     
Нумерованный список 1.  перед текстом   

Ссылки 

[пояснение][адрес http]     
[Markdoun] [https://ilfire.ru/kompyutery/shpargalka-po-sintaksisu-markdown-markdaun-so-vsemi-samymi-populyarnymi-tegami/?upm_export=print#link11]   
[Git][https://habr.com/ru/articles/541258/]

[настройка репозитория][https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository]  
[сохранение изменений][https://www.atlassian.com/ru/git/tutorials/saving-changes]
 [проверка репозитория][https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository]

## *Ошибки*
1.![изображение не найдено](e325.jpg)
Удалить файл подкачки.

Важное.     
Порядок работы      
Всегда перед комитом добавлять файл для отслеживания.     
