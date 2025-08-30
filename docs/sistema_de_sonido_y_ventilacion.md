# Audio y Refrigeración: Dando Vida y Frescor al Proyecto

Una vez que tuvimos imagen, surgieron dos nuevos desafíos: el sonido y el calor. ¿De qué sirve una consola retro si no puedes escuchar los "pew-pew" o si se sobrecalienta en medio de una partida?

## Potenciando el Sonido

El sistema de audio original presentaba dos problemas clave:

1.  **El altavoz original era una basura:** Apenas se escuchaba,
2.  **Problemas de conexión:** No teníamos una forma directa de enviar el audio desde el jack de la placa base al conector SCART.

Nuestra solución fue crear un sistema de audio 2.0 a medida, reutilizando componentes y añadiendo un poco de magia.

### El Corazón del Sistema: Amplificador PAM8403

Para darle la potencia necesaria, optamos por un pequeño amplificador **PAM8403**. Este pequeño circuito nos permitiría manejar dos canales de audio (estéreo) y dar vida a los altavoces.

```{image} /_static/img/43.png
:width: 400px
:align: center
:alt: Amplificador PAM8403
```

El montaje fue sencillo, conectando la entrada de audio desde el jack de la placa base y las salidas a nuestros dos altavoces, como muestra el diagrama.

```{image} /_static/img/29.jpeg
:width: 400px
:align: center
:alt: Diagrama de conexiones del amplificador
```

### Colocación Estratégica de Altavoces

Para conseguir un sonido estéreo, distribuimos los altavoces de forma ingeniosa:

-   **Altavoz original:** Lo reinstalamos en su ubicación original. Como se ve en la imagen, lo pegamos y lo sujetamos temporalmente con cinta. 
-   **Nuevo altavoz:** Encontramos un hueco perfecto en la parte superior de la carcasa.

(Al final ambos altavoces fueron pegados con pegamento en sus nuevas ubicaciones)

```{image} /_static/img/23.jpeg
:width: 400px
:align: center
:alt: Altavoz original siendo pegado en su sitio
```

```{image} /_static/img/32.jpeg
:width: 400px
:align: center
:alt: Altavoz nuevo instalado en la parte superior del televisor
```

El resultado final fue un sistema de sonido compacto y perfectamente integrado.

```{image} /_static/img/31.jpeg
:width: 400px
:align: center
:alt: Montaje final del amplificador
```

Para alimentarlo, usamos una solución simple y elegante: un puerto USB de 5V de la propia placa base.

---

## Manteniendo la Calma: Sistema de Ventilación

Las primeras pruebas revelaron un problema: **el calor** , que aunque no era mucho despues de largas sesiones de juego podria ser un problema . El interior del televisor se estaba convirtiendo en un horno, ya que el aire caliente generado por el PC no tenía una salida eficiente.

Decidimos tomar cartas en el asunto e instalar un sistema de ventilación activa.

### El Plan: Un Ventilador de Extracción

Aprovechando unas rejillas de ventilación existentes en el lateral de la carcasa, planeamos instalar un ventilador que extrajera activamente el aire caliente del interior.

```{image} /_static/img/24.jpg
:width: 400px
:align: center
:alt: Ubicación elegida para el ventilador
```

### Manos a la Obra

Con la ayuda de nuestra fiel **Dremel**, marcamos y perforamos los agujeros necesarios para atornillar el ventilador. *(Nota del constructor: hicimos tres agujeros por si acaso, pero al final solo necesitamos dos).*

```{image} /_static/img/25.jpeg
:width: 400px
:align: center
:alt: Agujeros para el ventilador marcados
```

Y aquí está el resultado final: un ventilador perfectamente acoplado, listo para mantener los componentes a una temperatura óptima durante las largas sesiones de juego.

```{image} /_static/img/26.jpeg
:width: 400px
:align: center
:alt: Ventilador instalado en su sitio