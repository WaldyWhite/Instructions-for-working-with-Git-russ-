[Главная](readme.md) 

---
## <p align='center'>git commit</p>


<br>

 После того как мы добавили наши файлы с помощью команды ***git add*** . нам необходимо их _закоммитить_.
<br>

Создадим коммит командой **git commit и -m**:
-  _В кавычках нужно в крации указать изменения которые вы сделали в файлах_.

```bash=
git commit -m "Commit message"
```
<br>

>_Команда **git commit** делает для проекта снимок текущего состояния изменений, добавленных в раздел проиндексированных файлов_. 

<p align='center'><img src='git.commit.PNG'></p>

-  _Отлично ! теперь файл(-ы) находятся в **HEAD** рабочей локальной копии. **В удаленном репозитории их все еще нет**_.

<br>

Если вы редактировали несколько файлов и хотите *закоммитить* все изменения так что бы на пример **file_1.md** и **file_2.md** были одним  a **file_3.md** и **file_4.md** должны идти отдельным *коммитом* так как они логически не связаны с первыми двумя, то можно сделать вот так.

```bash=
git add file_1.md
git add file_2.md
git commit -m "Commit message for file_1.md and file_2.md"
```
```bash=
git add file_3.md
git add file_4.md
git commit -m "Commit message for file_3.md and file_4.md"
```
---
[ < назад](add.md) &nbsp;&nbsp;&nbsp;&nbsp; [вперёд >](remote.md)
