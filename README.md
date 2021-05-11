*PASOS PARA MODIFICAR FONDO DINAMICO*
**REQUISITOS**
- INSTALAR GNOME-TWEAK
 

**DESCARGAR IMAGENES Y CONFIGURACION*
```
user@host:~# git clone https://github.com/Racso20/BigSur_Ubuntu.git
Clonando en 'BigSur_Ubuntu'...
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (19/19), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 19 (delta 3), reused 0 (delta 0), pack-reused 0
Desempaquetando objetos: 100% (19/19), 28.19 MiB | 1.32 MiB/s, listo.
```

```
user@host:~# sudo mv BigSur_Ubuntu/ /usr/share/backgrounds/
user@host:~# cd /usr/share/backgrounds/
user@host:~# sudo mv BigSur_Ubuntu/ BigSur/
```

**MODIFICAR FONDO**
- En apariencia de GNOME-TWEAK agregar BigSur.xml ubicado en /usr/share/backgrounds/BigSur
