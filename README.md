## **Домашнее задание** 

##### 1. Посмотреть где я 
        pwd
##### 2. Создать папку 
        mkdir homework
##### 3. Зайти в папку 
        cd homework
##### 4. Создать 3 папки 
        mkdir folder_1 folder_2 folder_3
##### 5. Зайти в любую папку 
        cd folder_1
##### 6. Создать 5 файлов (3 txt, 2 json)
        touch 1.txt 2.txt 3.txt
        touch 1.json 2.json
##### 7. Создать 3 папки 
        mkdir Saint-Petersburg Moscow Novorossiysk
##### 8. Вывести список содержимого папки
        ls -la
##### 9. Открыть любой txt файл 
        cat 1.txt
##### 10. Написать туда что-нибудь, любой текст
        vim 1.txt
        i
        222
##### 11. Сохранить и выйти
        ESCAPE - выйти из редактирования
        SHIFT+: wq
##### 12. Выйти из папки на уровень выше
        cd ..
##### 13. Переместить любые 2 файла, которые вы создали, в любую другую папку
        mv folder_1/1.txt folder_1/1.json folder_2/
##### 14. Cкопировать любые 2 файла, которые вы создали, в любую другую папку
        cp folder_1/2.txt folder_1/2.json folder_2
##### 15. Найти файл по имени
        find folder_2/1.txt
##### 16. Просмотреть содержимое в реальном времени
        tail -f folder_2/1.txt | grep "2" - отслеживание определенных символов в реальном времени
        tail -f folder_2/1.txt - отслеживание любых изменений в файле в реальном времени
##### 17. Вывести несколько первых строк из текстового файла
        head -n 2 folder_2/1.txt - выведет первые 2 строки текстового файла
##### 18. Вывести несколько последних строк из текстового файла
        tail -n 2 folder_2/1.txt - выведет последние 2 строки текстового файла
##### 19. Просмотреть содержимое длинного файла
        less -N long_file.txt - откроется текст файла в утилите Less с нумерацией по строкам.

        "up" и "down" позволяют листать текст вниз и вверх 
        "space" перемещает на следующую страницу 
        "b" перемещает на предыдущую страницу
        "g" перемещает в начало текста
        "G" перемещает в конец текста
        ng перемещает на n-ю строку текста
        "q" - выход из утилиты 
##### 20. Вывести дату и время
        date
##### 21. Отправить http запрос на сервер
        curl http://162.55.220.72:5005/terminal-hw-request
##### 22. Написать скрипт который выполнит автоматически пункты 3-8, 13
        ./script.sh - запуск скрипта

[скрипт](https://github.com/ruslan-9/Vadim_homework_bash/blob/ad402dda5c264fb1de1e02cf5cd66ddd83cb9f0d/script.sh)
