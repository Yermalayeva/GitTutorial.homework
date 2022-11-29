# Дополнительная информация к туториал  по GIT

## Просмотри истории коммитов

Чтобы посмотреть что было сделано — историю коммитов, необходимо использовать следующую команду:
```
git log
```
## Определение состояния файлов

Чтобы узнать  какие файлы в каком состоянии находятся, необходимо прописать команду:
```
git status
```
## Cоздание коммита

Чтобы зафиксировать все наши изменения, необходимо использовать следующую команду:
```
git commit -m “message” 
```
## Переход от одного коммита к другому

Для того, чтобы перейти от одной версии файла к другой существует следующая команда:
```
git checkout 
```
## Изменение последнего коммита

Чтобы изменить последний коммит, необходимо прописать следующую команду:
```
git commit --amend -m “message” 
```
## Cоздание новой директории

Для создания нового каталог необходима следующая команда:
```
mkdir <название папки>
```
## Клонирование внешнего репозитория на локальный ПК

Клонирование репозитории осуществляется при помощи следующей команды:
```
git clone <url-адрес репозитория>
```
## Получение изменений и слияние с локальной версией

Чтобы забрать изменения из множества удалённого репозитория, а затем слить их с наблюдаемой веткой, необходимо прописать команду:
```
git pull 
```
## Отправка изменений в удаленный репозиторий

Для того, чтобы отправить измененную локальную версию репозитория в удаленный репозиторий, необходимо использовать команду:
```
git push 
```