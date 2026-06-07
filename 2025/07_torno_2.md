---
title: "Guía 7: Tornería - Montajes y preparación"
autor: "José Juarez"
version: "24/06/25"
---

<span hidden>Local path of the file: "H:/im/dmec4/"</span>
<span hidden>Local path of images: "H:/im/dmec4/_i/"</span>


<br><br>


## Introducción 

En este bloque verás como lo básico sobre la preparación del torno antes de realizar un mecanizado. Involucra conocimientos sobre cómo montar la pieza y la herramienta. También sobre como ajustar los parámetros de corte. Todo esto es fundamental para garantizar **seguridad**, **precisión** y **eficiencia** en el trabajo.


<br><br>


## Sujeción de la pieza

El primer paso antes de mecanizar es fijar correctamente la pieza en el torno. Esto depende de la forma, tamaño y tipo de operación que se va a realizar.

<br>

### Sujeción al plato al aire

* La pieza se fija **sólo en el plato**, sin apoyo del contrapunto.
* Se utiliza en piezas cortas o cuando se debe mecanizar el extremo libre (por ejemplo, refrentado o roscado).
* Riesgosa para piezas largas o pesadas si no se toman precauciones.

Mira esta [explicación](https://www.youtubetrimmer.com/view/?v=yNeYexP5wpM&start=933&end=968&loop=0).

<br>

### Sujeción entre plato y punto

* La pieza se fija por un extremo en el **plato**, y el otro se apoya sobre el **punto del contrapunto**.
* Aporta **estabilidad**, especialmente útil para piezas largas o delgadas que podrían flexionarse si estuvieran "al aire".
* Se usa cuando se necesita mecanizar sólo una parte de la longitud total.

Mira esta [explicación](https://www.youtubetrimmer.com/view/?v=yNeYexP5wpM&start=1125&end=1154&loop=1).

<br>

### Sujeción entre puntos (entre centros)

* Ambos extremos de la pieza se apoyan en puntos cónicos. El plato tiene una punta cónica y se usa una brida de arrastre que se atornilla a la pieza para lograr que la pieza gire.
* Permite mecanizar todo el contorno de la pieza (salvo los extremos).
* Requiere que la pieza tenga **centros cónicos previamente trazados**.

Mira esta [explicación](https://www.youtubetrimmer.com/view/?v=yNeYexP5wpM&start=1204&end=1316&loop=1).

<br>

### Sujeción con luneta

* Cuando la pieza es muy larga o requiere soporte adicional, se emplean **lunetas fijas o móviles**.
* Este método se combina con cualquiera de los anteriores para **evitar vibraciones o flexiones**.

Mira esta [explicación](https://www.youtubetrimmer.com/view/?v=yNeYexP5wpM&start=1318&end=1386&loop=0).
<br><br>


<br><br>


## Actividad 1

Prepara, si quieres escríbela, una exposición de uno o dos minutos, explicando los distintos tipos de sujección que hemos visto hasta aquí. Cuando estés listo exponla al profesor. Se requiere esto para aprobar esta guía.


<br><br>


## Actividad 2

Investiga sobre los platos de 4 mordazas y explica en unos 4 renglones como funciona y para que se usa.


<br><br>


## Centrado y alineación de la pieza

Una pieza mal centrada puede producir errores de medida o dañar la herramienta.

### Según el tipo de sujeción:

* En **plato de 3 mordazas**, la pieza se centra automáticamente.
* En **plato de 4 mordazas**, se ajustan las mordazas una por una y se usa un **comparador** para centrar.
* **Entre puntos**: se usan **centros cónicos normalizados**, y se comprueba que el eje de la pieza coincida con el del torno.


<br><br>


## Actividad 3


Observa este fragmento de [video](https://www.youtubetrimmer.com/view/?v=5qmi_fE-w18&start=222&end=380&loop=1) y responde estas preguntas:

**a)** ¿Cómo se llama el instrumento que usa para centrar de un modo muy preciso la pieza?

**b)** ¿De qué tipo de plato se trata aquí? ¿Las mordazas se mueven todas juntas (al mismo tiempo) o son independientes?

**c)** ¿Básicamente que hace para desplazar un poquito la pieza hacia un lado? 



<br><br>

<div hidden>

## 3. **Montaje de herramientas en el carro porta-herramientas**

El montaje correcto de la herramienta es esencial para que el mecanizado sea seguro y preciso.

### Pasos:

1. Elegir la herramienta adecuada (desbaste, acabado, roscado, ranurado, etc.).
2. Asegurarla en el **porta-herramientas** con firmeza, sin inclinaciones.
3. Ajustar la **altura del filo**: el filo de corte debe coincidir con el **centro del eje de la pieza**.

   * Si queda más bajo: puede empujar la pieza y generar vibraciones.
   * Si queda más alto: empeora el ángulo de ataque y puede romperse.
   * Se puede usar el **punto del contrapunto** como referencia para ajustar la altura.

> 🛠️ **Tip:** Usar cuñas o calzos si el porta-herramientas no tiene ajuste micrométrico de altura.

---

## 4. **Selección de velocidad, avance y profundidad de pasada**

Estos tres parámetros determinan cómo se realiza el mecanizado. Deben ajustarse en función del **material**, **diámetro de la pieza**, tipo de **herramienta**, y el **acabado** deseado.

### a) **Velocidad de corte (Vc)**

* Se refiere a la **velocidad tangencial** entre la herramienta y la pieza (m/min).
* Se calcula a partir de la fórmula:

$$
n = \frac{1000 \cdot Vc}{\pi \cdot D}
$$

Donde:

* $n$: revoluciones por minuto (rpm)
* $Vc$: velocidad de corte en m/min
* $D$: diámetro de la pieza en mm

> Ejemplo: para acero con herramienta HSS, $Vc \approx 30$ m/min

### b) **Avance (f)**

* Es la distancia que avanza la herramienta por cada vuelta del husillo.
* Se expresa en mm/vuelta.
* Para desbaste: avance mayor. Para acabado: menor.

### c) **Profundidad de pasada (ap)**

* Es cuánto se saca en cada pasada (en mm).
* Se ajusta según la rigidez del sistema y la etapa del mecanizado.
* Para desbaste: mayor profundidad (2-4 mm), para acabado: menor (0,2-0,5 mm).

> ⚠️ **Importante:** Usar parámetros muy altos puede generar sobrecalentamiento, vibraciones o romper la herramienta.

---

## Actividades prácticas sugeridas

1. **Montar una pieza cilíndrica** en el plato de 3 garras, ajustar velocidad y mecanizar un cilindrado.
2. **Centrar una pieza irregular** en el plato de 4 garras.
3. **Montar y alinear** una herramienta de corte para desbaste.
4. **Calcular y ajustar rpm** para una pieza de acero de 50 mm de diámetro.
5. **Comparar resultados** entre distintas profundidades de pasada y avances.

</div>




<!-- HTML style definitions -->
<style>
/* Colors */
.grey1 {color: #b3b3b3;} /* my light-grey */
.grey2 {color: #999999;} /* my middle-grey */
.grey3 {color: #808080;} /* my dark-grey */
.blue1 {color: #6495ed;} /* nvim blue */
.blue2 {color: #276cdf;} /* Andrew Ng Blue */
.sky1 {color: #7dbed8;} /* nvim sky */
.sky2 {color: #27a2db;}   /* my sky */
.green {color: #81b524;} /* my green */
.red1 {color: #ec5469;} /* my coral-red */
.red2 {color: #f44336;} /* my red */
.rose {color: #ec9998:} /* nvim rose */
.gold {color: #df9d43;} /* Andrew Ng gold */
.orange1 {color: #fda556;} /* nvim orange */
.orange2 {color: #ff9505;} /*Andrew Ng orange */
.purple1 {color: #ff40ff;} /* Andrew Ng purple */
.purple2 {color: #d164d7;} /* Andrew Ng purple */
/* Font Size */
.size90 {font-size: 0.9em;}
.size85 {font-size: 0.85em;}
.size80 {font-size: 0.8em;}
.size70 {font-size: 0.7em;}
/* Document General Font Size */
body {font-size: 1.3em;}
</style>
<!-- Use <span> inline and <div> with several lines --->
