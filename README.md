## Установка и настройка

```zsh
$ yay -S random-wallpaper
$ sudo systemctl start random-wallpaper.timer && sudo systemctl enable random-wallpaper.timer
```

Обои можно менять вручную:

```zsh
$ random-wallpaper
```

Настройки находятся в файле `/etc/conf.d/random-wallpaper`.

## Ручная установка

Перемещаем `random-wallpaper.service` и `random-wallpaper.timer` в `/lib/systemd/system`, `random-wallpaper` ‒ в `/usr/bin` и делаем `chmod +x`, `random-wallpaper.conf` -> `/etc/conf.d/random-wallpaper`.
