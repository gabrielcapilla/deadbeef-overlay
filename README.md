# deadbeef-gc
Configuración rápida para DeaDBeeF. Incluye pestañas para ver la letra de las canciones. Necesita instalar plugins extra. Probado en Linux Manjaro KDE.

![preview-general](https://user-images.githubusercontent.com/104425110/230133189-fca4266e-f486-4872-a163-fbea3b12ab8d.png)
![preview-lyricbar](https://user-images.githubusercontent.com/104425110/230133264-002ecc30-efef-4039-8fc9-93990171c681.png)


## Instale **DeaDBeeF**.
```zsh
sudo pamac install deadbeef-git
```

### Instalar dependencias necesarias para los plugins.
```zsh
sudo pamac install hwloc libxml++ gtkmm boost openpmix openmpi fftw
```

### Instale los plugins necesarios para una mejor experiencia.
```zsh
sudo pamac install deadbeef-plugin-lyricbar-git deadbeef-plugin-medialib-git deadbeef-plugin-waveform-gtk3-git deadbeef-plugin-musical-spectrum-gtk3-git
```

### Archivo config
Añade el archivo **config** en `~/.config/deadbeef/`.

---

## Complementos necesarios (AUR)
- [deadbeef-plugin-lyricbar-git](https://aur.archlinux.org/packages/deadbeef-plugin-lyricbar-git)
- [deadbeef-plugin-medialib-git](https://aur.archlinux.org/packages/deadbeef-plugin-medialib-git)
- [deadbeef-plugin-waveform-gtk3-git](https://aur.archlinux.org/packages/deadbeef-plugin-waveform-gtk3-git)
- [deadbeef-plugin-musical-spectrum-gtk3-git](https://aur.archlinux.org/packages/deadbeef-plugin-musical-spectrum-gtk3-git)
