# Лабораторная работа №6
_Цель лабораторной работы_: изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удалённым репозиторием.

## Ход работы 

1. Получение истории каждой из веток
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/1.png">
</p>


2. Просмотр последних изменений
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/2.png">
</p>

3. Создание новой ветки и файла ms.txt
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/3.png">
</p>

4. Слияние веток
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/4.png">
</p>

5. Удаление ветки
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/5.png">
</p>

6. На этом этапе были произведены изменения. Были созданы файлы suai.txt, suai1.txt. и закоммичены, после чего был создан файл suai2.txt. Коммит с созданием этого файла откатан. 
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/6.jpg">
</p>

7. Создана ветка для отчета
<p align="center">
  <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/7.png">
</p>

8. История операций в форматированном виде, где:
- `%h` — это сокращённый хеш коммита.
- `%an` — это имя автора коммита.
- `%ar` — это время, прошедшее с момента коммита.
- `%s` — это сообщение коммита.
<p align="center">
   <img src="https://github.com/stpkn/LR6/blob/otchet/screenshots/8.png">
</p>

## Лог команд
```
git clone
git pull
git add
git commit -m
git push
git show
git branch
git checkout
git log
git merge
git branch -d
git revert HEAD
git push --set-upstream origin 
git log --pretty=format:"%h - %an, %ar : %s"
```
## Вывод
В данной лабораторной работе были изучены базовые возможности системы управления версиями, был получен опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.
