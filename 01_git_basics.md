# инициализация

git init

# статус

git status

# добавить в stash

git add <files>
git add --all
git add .

# простой коммит

git commit -m '%commit name%'

# просмотр логов

git log           # полная версия
git log --oneline # по 1 строке на коммит

# исправить текущий коммит

git commit --amend

# привязка удаленного репозитория

git remote add origin git@github.com:<accounts_name>/<repo_name>.git

# отправка в удаленный репозиторий

git push -u origin main # в первый раз
git push                # в последующие
git push -f             # принудительно, например после --amend





