# Подсказка по GIT


## *Для обозначения имени и электронной почты человека работавшего с репозиторием*
**Ввод имени**
```sh
git config --global user.name "Your Name"
```
**Ввод электронной почты**
```sh
git config --global user.email "Your email"
```
## *Работа с файлами*
**Добавление файлов к отслеживанию**
```sh
git add <filename>
```
**Фиксирование изменений в файле**
```sh
git commit -m "Message text"
```
**Удаление файла**
```sh
git rm <filename>
```
## *Для просмотра истории коммитов*
**Просмотр внесенных изменений**
```sh
git log
```
**Вывод лога в сокращенном формате**
```sh
git log --oneline
```
## *Работа с репозиторием*
**Инициализация репозитория**
```sh
git init
```
**Сравнение изменений двух коммитов**
```sh
git diff
```
**Проверка статуса репозитория**
```sh
git status
```
**Перемещение по веткам**
```sh
git checkout <имя_ветки>
```
**Отображение всех веток**
```sh
git branch
```
**Создание новой ветки**
```sh
git branch <имя_ветки>
```
**Удаление ветки**
```sh
git branch -d <имя_ветки>
```
**Выводим список коммитов в виде красивого графа/дерева**
```sh
git log --graph
```
**Сливание созданной ветки с оснавной**
```sh
git merge <имя_ветки>
```

## *Pull Request*
**Клонирование из fork-копии**
```sh
git clone git@github.com:*ваш_github*/version_control.git
```
**Делаем PUSH**
```sh
git push --set-upstream origin updatereadme
```
