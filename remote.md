[К содержанию](./readme.md)

## Удалённые репозитории(remote add, remote rename и remote remove)

---

### git remote add

**git remote add** - команда для добавления удалённого репозитория и присвоения ему имени (shortname).

```bash=
git remote add <shortname> <url>:
```


### git remote rename


**git remote rename** - для переименования удалённого репозитория.


```bash=
git remote rename <old name> <newname>
git remote
origin 
<newname>
``````


### git remote remove


**git remote remove** - используется для удаления репозиторя.
При удалении ссылки на удалённый репозиторий все отслеживаемые ветки и настройки, связанные с этим репозиторием, так же будут удалены.

```bash=
git remote remove <name>
git remote
origin
```