# Туториал по работе с Git

## Начало работы

Для начала работы, необходимо инициализировать сам Git

Для его инициализации введите команду 

```
  git init
```

## Добавление файла

Для добавления файла в Git необходимо воспользоваться командой 

```
git add название_файла
```

## Получение информации о текущем состоянии git

Чтобы получить информацию о текущем состоянии git, используйте команду

```
git status
```

## Создание коммита

Для создания коммита, используйте следующую команду

```
git commit -m “message”
```

## Вывод на экран истории всех коммитов

Для вывода на экран истории всех коммитов, введите следующую команду

```
git log
```

## Переход от одного коммита к другому

Для перехода от одного коммита к другому, используйте следующую команду

```
git checkout
```

## Возврат к актуальному состоянию

Чтобы вернуться к актуальному состоянию и продолжить работу, воспользуйтесь командой

```
git checkout master
```

## Просмотр разницы между текущим файлом и закоммиченным файлом

Чтобы увидеть разницу между текущим файлом и закоммиченным файлом, используйте команду

```
git diff
```

## Добавление всех файлов целиком к следующему коммиту

Для добавления всх файлов целиком к следующему коммиту, введите команду

```
git add --all 
```

## Изменение последнего коммита

Для изменения последнего коммита, используйте следующую команду

```
git commit --amend -m “message”
```

## Сброс всех изменений до определенного коммита

Для сброса всех изменений до определенного коммита, используйте  команду

```
git reset номер_коммита
```

## Создание новой директории

Для создания новой директории, воспользуйтесь командой

```
mkdir название_папки 
```

## Просмотр всех файлов в текущей папке

Чтобы просмотреть все файлы в текущей папке, используйте команду

```
ls
```

## Просмотр всех введенные когда-либо в терминал команд

Чтобы просмотреть все введенные когда-либо в терминал команды, используйте команду

```
history
```