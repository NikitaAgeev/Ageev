1. Делаем ключ
ssh-keygen -t ed25519 -C "почта"
2. Загружаем в гитхаб (иконка в правом верхнем/settings/SSH keys/ там вставить ключ из файла с разрешением .pub)
3. Для добавления ключа на пк
shh-add {адрес ключа}
4. Для копирования репозитория копируем его SSH и пишем
git clone {SSH}
