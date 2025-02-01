# Run It (in Konsole, No Hold Edition)

Run Scripts in KDE Konsole without the default --hold / --noclose
option, so Konsole can exit after running the script.

## inspired by

https://discuss.kde.org/t/using-konsole-how-to-open-a-folder-in-dolphin-then-automatically-konsole-returns-to-its-command-line/

## install hints

Installing via Configure Dolphin failed for me with the flatpak variant, so you might have to create the menu entry manualy by yourself.

This service menu file goes to:


```
$HOME/.var/app/org.kde.dolphin/data/kio/servicemenus/run-it.desktop
```

