[Главная](readme.md) 

---
## <p align='center'>git pull</p>


<br>

Чтобы обновить локальный репозиторий до последнего коммита, нужно сделать *“пулл”*.

```bash=
git pull [ветка]
```
- *git pull [ветка] - например **origin master***

<br>

 Пример:

*После выполнения команды **git push** в консоле мы видим ошибку, указывающую на то что в удалённом репозитории произошли изменения*.

![git push error](git.pull.error.PNG)

<br>

*Что-бы это исправить выполним команду **git pull***.

![git pull](git.pull.PNG)

*Отлично! теперь все изменения добавлены в локальный репозиторий и мы опять смело можем добавить наши изменённые файлы на GitHub*.

```bash=
git add
git commit -m "massege"
git push
```

---
[ < назад](remote.md) &nbsp;&nbsp;&nbsp;&nbsp; [вперёд >](stages_Of_Work.md)
