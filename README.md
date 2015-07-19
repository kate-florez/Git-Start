# Git-Start
План работы:
1. Скачать Git программу https://git-scm.com/downloads
2. Установить
3. Сгенерировать ключи https://help.github.com/articles/generating-ssh-keys/
ssh-keygen -t rsa -b 4096 -C "lebedeva.kait@gmail.com"
clip < ~/.ssh/id_rsa.pub
5. https://github.com/settings/ssh Добавить рабочий ключ
6. git clone git@github.com:lebedeva-kait/TokensApp.git .

Сохранить изменения:
1. git add -A
2. git commit -m "com"
3. git push origin master

Обновить с др компа:
git pull
