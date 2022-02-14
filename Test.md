![Git-logo](logo.png)
# Работа с Git
## 1. Проверка наличия установленного Git
в терминале выполнить команду `git version`

*Курсив*
**Полужирный**
***Полужирный Курсив***
## 2. Установка Git

Загружаем последнюю версию Git с [сайта](https://git-scm.com/downloads)

## 3. Настройка Git
При первом использовании Git необходимо призвести его настройку спомощью команд:
```
git config --global user.name "Ваше имя"
git config --global user.mail "email@mail.com"

git help -a
git commit -am "Insert #2" 
git commit -a -m "Insert #2" 
git add
git commit -m "Insert #2" 
git commit --amend -m "Message"
git log --oneline
```
## 4. Инициализация репозитория
## 5. Запись измененийв в репозиторий
## 6. Просмотр истории commit
## 7. Перемещение между сохранениями
## 8. Игнорирование файлов
## 9. Создание веток в Git
Ветка в Git - это простой перемещаемый указатель на один из commit (обычно последний в цепочке). По умолчанию имя основной ветки в Git - master.
Создать ветку можно командой:
```
git branch create_Branch1
git checkout -b mergeBranch2
```
Чтобы при создании ветки сразу не неё переключиться используется команда:
```
git checkout -b <имя_новой_ветки>
```
`git branch create_Branch1`
`git checkout -b mergeBranch2`
В результате создаётся новый указатель на текущий commit.
Список веток в репозитории можно посмотреть с помощью команды: 
`git branch`
## 10. Слияние веток и разрешение конфликтов
## 11. Удаление веток
