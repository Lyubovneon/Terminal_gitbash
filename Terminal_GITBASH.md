### 👉 *START* 💙💛
***
### *1. Посмотреть где я.* 
- **pwd**
***
### *2. Создать папку.*
- **mkdir** GITBASH_HW_1
***
### *3. Зайти в папку.*
- **cd** GITBASH_HW_1
***
### *4. Создать 3 папки.*
- **mkdir** folder{00..2}
***
### *5. Зайти в любую папку.*
- **cd** folder01
***
### *6. Создать 5 файлов (3 txt, 2 json).*
- **touch** lyuba{00..2}.txt
- **touch** dasha(00..1).json
***
### *7. Создать 3 папки.*
- **mkdir** levelfolder{00..2}
***
### *8. Вывести список содержимоe папки.*
- **ls -la**          *  пробел после **ls***
***
### *9. Открыть любой txt файл.*
- **vim** lyuba01.txt
***
### *10. + написать туда что-нибудь, любой текст*
- **🡪   **i**  🡪  *вызов insert*  🡪  *пишем текст*
 ***
### *11. + сохранить и выйти.*
- **esc**(кнопка) : **wq**  🡪*выход с сохранением*  
- **esc**(кнопка) :**q**  🡪*выход без сохранения*
***
### *12. Выйти из папки на уровень выше.*
- **cd ..**  *!!!!!  пробел после ***cd***
***
### *13. Переместить любые 2 файла, которые вы создали, в любую другую папку.*
- 🡪  *выйти в общую папку проекта*
- 🡪  **mv -v folder01/dasha00.json folder02/**
or
- **mv  folder01/dasha00.json folder02/** 
***
### *14. Скопировать любые 2 файла, которые вы создали, в любую другую папку.*
- *выйти в общую папку проекта*
- 🡪 **cp -r folder01/dasha00.json folder00/**
или
- **cp  folder01/dasha00.json folder00/**         
***
### *15. Найти файл по имени.*
- **find . -iname  “dasha01.json”**
***
### *16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает.*

***
### *17. Вывести несколько первых строк из текстового файла.*
- **head -n 2 lyuba01.txt**  *выведет две первые строки*
- **head -n 4 lyuba01.txt**  *выведет четыре первые строки*
***
### *18. Вывести несколько последних строк из текстового файла.*
- **tail -n 2 lyuba01.txt** *выведет две последние строки*
- **tail -n 3 lyuba01.txt** *выведет три последние строки*
***
### *19. Просмотреть содержимое длинного файла (команда less) изучите как она работает.*
- **less lyuba01.txt** *видим содержимое файла*
or 
- **less -s lyuba01.txt** *видим содержимое файла без пустых строк, пустые строки убираются*
***
### *20. Вывести дату и время.*
- **$ date**    current date 

###  *F I N I S H* 👈









