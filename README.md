# Отчет по лабораторной работе: Основы работы с Git
## Цель работы:  
освоить основные команды Git
## Задание 1 - Автоматизация проверки формата файлов при коммите
в директории ``` .git/hooks/ ``` создаю новый файл ``` pre-commit ``` и начинаю его редактирование:
![image](https://github.com/user-attachments/assets/63cf573e-df85-4988-a57d-602b7398b774)
наполняю его следующим кодом:
![image](https://github.com/user-attachments/assets/0b78863d-6547-4ff9-80bf-62b5d67d7d47)
пытаюсь создать "плохие" файлы и получаю нужный ответ:
![image](https://github.com/user-attachments/assets/932f15ac-d5b1-43f7-8b15-c5e417d982d5)
очищаю staging area, чтобы Git не выдавал ошибку старых файлов перед коммитом новых и добавляю "правильный" файл:
![image](https://github.com/user-attachments/assets/8cbfca04-3175-4d9d-873f-a12f84fa2f10)
все прошло успешно
