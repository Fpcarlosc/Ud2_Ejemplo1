# Ud2_Ejemplo1
_Ejemplo 1 de la Unidad 2._

Vemos la diferencia entre wrap_content y match_parent, para ello sólo hemos de fijarnos en el fichero _activity_main.xml_ 
y en concreto en las siguientes líneas:

```
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:background="@android:color/darker_gray"
        ... />
```

Donde podemos ver que el texto del TextView es _Hello World!_ y el color de fondo es gris oscuro (Lo pintamos para ver la diferencia).  
Si vamos cambiando entre _wrap_content_ y _match_parent_ tanto en _layout_width_ como en _layout_height_ veremos cómo se modifica el tamaño del TextView.

También podemos hacer cambios asignándoles números en _dps_.
