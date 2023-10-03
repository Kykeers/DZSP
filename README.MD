# Это файл для дз. Жду ваши изменения снизу, в последующих строках в этом файле)

**Команды Git**

* Git checkout master - возвращение на вершину мастерской ветки 

* Git branch - посмотреть на какой ветке сейчас располагаемся

* Git branch [name_of_new_branch] - создать новую ветку с таким-то именем

* Git checkout [name_of_new_branch]  - перейти на эту ветку из другой ветки

* Clear - чистит терминал

* Git merge [name_of_branch_for merge] - слияние веток (имя донорской ветки в скобках)

* Git branch -d [name_of_branch_to_delete] - удалить ветку

* Git log —graph - выводит историю и дерево веток

* `gitgit remote --verbose` This will give you the origin URLs for fetch and push, for the repo you cloned.

* Git rebase [name_of_branch] - способ объединения изменений в ветках - это *rebasing*. При ребейзе Git по сути копирует набор коммитов и переносит их в другое место.

* Git branch -M [name_of_branch] - делает ветку главной

* Git push -u origin [branch_name] - отправляет ветку с локального репозитория на удалённый

* Git clone  [link_to_reporitory] - скопировать весь удалённый репозиторий + связанность, если удалённый репозиторий под твоим управлением