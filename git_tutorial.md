# Инструкция по работе с Git
## Подготовка рабочего места
1. git config
2. git config --global user.name
3. git config --global user.email
## Инициализация репозитория
1. git init
2. git status
## Первый коммит
1. git add 'file_name' | .
2. git commit -m 'commit_name'
## Ветки в Git
1. git branch <branch_name>
2. git checkout <branch_name>
3. git checkout -b <branch_name>
4. git merge <feature_branch>
## История коммитов и работа с ними
1. git show
2. git log  | --oneline | --stat | --graph
3. git diff
## Задание 1. Команда, которая создает коммит без использования команды add
1. git commit -a -m 'commit_name'
## Задание 2. Команда, которая изменяет комментарий коммита
1. git commit --amend -m 'new_commit_name'
## Работа с удаленным репозиторием
1. git remote add origin <repository_address>
2. git push -u origin master