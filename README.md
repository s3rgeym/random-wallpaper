## Установка и настройка

```zsh
$ yay -S random-wallpaper
$ sudo systemctl start random-wallpaper.timer && sudo systemctl enable random-wallpaper.timer
```

Обои можно менять вручную:

```zsh
$ random-wallpaper
```

## Ручная установка

Перемещаем `random-wallpaper.service` и `random-wallpaper.timer` в `/lib/systemd/system`, `random-wallpaper.sh` ‒ в `/usr/bin` и делаем `chmod +x`.
