[< к содержанию](./readme.md "перейти")
## GIT. Ветвление
Создание различных версий репозиториев, отличных друг от друга и называется **ветвлением**.

### Создание ветки и переключение на ветку

команда    | значение команды|
:-------- |:-----:|
git branch [наименование]|создает новую ветку в репозитории.|
git checkout [наименование]|переключает вас на определенную ветку.|
git checkout -b [наименование]|создаёт новую ветку и переключает вас на неё.|
### Объединение ветвей
команда    | значение команды|
:-------- |:-----:|
git merge [наименование]|поглощение. Вносит коммиты из другой ветки в текущую.|
git rebase[наименование]|перебазирование. В этом случае коммиты вашей ветки накладываются поверх текущего состояния указанной ветки.|