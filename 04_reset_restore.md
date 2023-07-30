# убрать файл из коммита

git restore --staged %file%
----
git restore --staged . // откатить все файлы
----
git restore %file%    // откатить изменения в файл, которые не попал в stage 

# откатиться к предыдущему коммиту

git reset --hard %commit hash&




