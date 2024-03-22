Например, мы изменили два файла и хотим добавить их в разные коммиты, но случайно выполнили команду `git add *` и добавили в индекс оба. Как исключить из индекса один из них 😢?

Команда `git status` напомнит нам:
```console
$ git add *
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage) (ИСПОЛЬЗОВАТЬ ЭТУ КОМАНДУ)

    renamed:    README.md -> README
    modified:   CONTRIBUTING.md
```

