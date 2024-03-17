# Elementary X  

#### ¡Se necesita mantenedor! Por favor deje un comentario en "¡Se necesita mantenedor!" problema si estás interesado

Bifurcación de la hoja de estilo Gtk+ predeterminada para SO elemental con controles de ventana de OS 

La hoja de estilo Gtk.CSS bifurcada con controles de ventana de OS X está diseñada específicamente para [elementary OS](https://elementary.io) y su entorno de escritorio: Pantheon. **Dado que Gtk.CSS ha cambiado bastante, esta hoja de estilo solo admite Gtk. >= 3.22**

#### Elementary-X está disponible en dos variantes

##### Variante oscura

![](https://i.imgur.com/kWuZ2aY.png)
![](https://i.imgur.com/n2T2tjm.png)
![](https://i.imgur.com/lPLt0Xx.png)

##### Variante ligera
###### (old screenshots)

![](http://i.imgur.com/AFwq5WW.png)

![](http://i.imgur.com/XjGm1FX.png)


[More screenshots](https://imgur.com/a/yoBOoSx)

#### Features

- Controles de ventanas de semáforos.
- Widgets rediseñados para lucir geniales
- Siempre actualizado con la hoja de estilo original de Elementary-OS.

### Instalación

Necesitarás ```git``` para instalar este tema
   ```
  apt-get install git
```

1. Abra la terminal y ejecute lo siguiente
```
git clone https://github.com/desarrollo032/elementary-x.git ~/.themes/elementary-x
```
2. Seleccione este tema en la herramienta de ajuste o ejecute lo siguiente
```
gsettings set org.gnome.desktop.interface gtk-theme "elementary-x"
```  
3. ¡Eso es todo, ya terminaste!

***Nota**: Para instalarlo globalmente, es decir, en situaciones en las que ejecuta aplicaciones como root o paquetes SNAP especiales, mueva su tema a ```/usr/share/themes ```*

### Extras
* Consulte aquí para ver cómo configurar [DARK MODE](https://askubuntu.com/questions/769417/how-to-change-global-dark-theme-on-and-off-through-terminal) 
* El tema de iconos utilizado es [La Capitaine](https://github.com/keeferrourke/la-capitaine-icon-theme). (Use `install_fixed_icons.sh` para instalar una versión fija del tema de iconos para eos)
* ¡La carpeta también incluye temas de tablones! Para instalar simplemente use el ```install_plank_themes.sh``` script
* Los temas de Chrome se incluirán pronto.
* Hay temas de metacity y xfwm4 que son para uso en otros entornos de escritorio.
* *No hay un tema de gnome-shell ya que está diseñado para la gala elemental*.

#### TO-DO
Aquí está el enlace al tablero de Trello para el proyecto. >  [board](https://trello.com/b/hEsKYAOa).  


### Contributing

No es necesario compilar esta hoja de estilo. Se recomienda hacer un enlace simbólico desde el directorio fuente a "/usr/share/themes" para las pruebas:

    ln -s /path/to/your/branch /usr/share/themes/

Será necesario reiniciar las aplicaciones o modificar la
hoja de estilo del sistema. cambiado para que los cambios
surtan efecto.

También puedes probar los cambios en vivo con Gtk Inspector. 
Asegúrate de tener Gtk bibliotecas de desarrollo instaladas:

    sudo apt install libgtk-3-dev

Abra una aplicación en la que desee probar sus cambios. Abra Gtk 
Inspector con el método abreviado de teclado Shift + Ctrl + D, luego 
navegue hasta la pestaña "Custom CSS". Sus cambios aquí tendrán 
efecto inmediato en la aplicación enfocada.

### Todo

* Merge https://github.com/elementary/stylesheet/pull/381
