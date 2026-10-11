# Гайд на установку и запуск Nginx

## Установка

1. Обновляешь списки пакетов: `sudo apt update`
2. Устанавливаешь Nginx: `sudo apt install nginx`
3. Проверяешь статус службы: `sudo systemctl status nginx`
4. Закидываешь в автозагрузку: `sudo systemctl enable --now nginx `

## Подключение

1. Смотришь свой IP-адрес: `ip a`
2. Пишешь в браузере: `http://твой IP-адрес` без слеша
