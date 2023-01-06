[Главная](readme.md) 

---
## <p align='center'>git remote</p>


<br>

Прежде чем добавлять что либо в удаленный репозиторий, нам нужно его создать на GitHub.

После чего мы увидим окно, с командами необходимыми для работы с репозиторием в командной строке,
где мы так же можем найти команду **git remote add origin** с указанием полного пути к нашему репозиторию.

![gitHub](remote.gitHub.PNG)

```bash=
git remote add origin [сервер]
```
- _Где ***[ сервер ]*** — это путь до репозитория_.
<br>

Теперь полностью копируем команду git remote с адресом  репозитория и вставляем в GitBash.

```bash=
git remote add origin https://github.com/someone/something.git
```
<p align='center'><img src='git.remote.PNG'></p>

Отлично! теперь путь в наш репозиторий указан и можно переходить к седующей команде.
 
---
[ < назад](commit.md) &nbsp;&nbsp;&nbsp;&nbsp; [вперёд >](push.md)
