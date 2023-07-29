# сгенерировать пару ключей

ssh-keygen -t ed25519 -C "email"

## старый вариант

ssh-keygen -t rsa -b 4096 -C "email"

# добавить ключ в ssh-agent

ssh-add ~/.ssh/id_ed25519

# далее скопировать текст из id_ed25519.pub

github->main->settings->SSH and GPG keys


