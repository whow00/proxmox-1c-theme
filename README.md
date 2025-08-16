## Описание
Самый обыкновенный фановый мод Proxmox в стиле 1С. На данный момент не самый стабильный, но вполне адекватно смотрится на светлой теме.

## 🚀 Установка
1. Скопируйте содержимое папок `css` и `images` в директорию темы Proxmox: /usr/share/pve-manager/
2. Перезапустите веб-интерфейс Proxmox:
```bash
systemctl restart pveproxy
```
3. Если тема не применяется, попробуйте во вкладке с proxmox нажать ctrl + f5, или переустановите pve-manager: ```bash apt install --reinstall pve-manager```

## Скриншоты
![1С жесть](screen/screenshot.png)
