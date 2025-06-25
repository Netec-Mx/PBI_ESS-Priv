# Práctica 2. Creación de informe y mejora en la experiencia de usuario

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:
- Diseñar un informe en Power BI con visualizaciones adecuadas, elementos interactivos y un enfoque centrado en la experiencia del usuario.

## Duración aproximada:
- 60 minutos.

---
| | | |
|-|-|-|
|**[⬅️ Atrás](https://netec-mx.github.io/PBI_ESS-Priv/Cap%C3%ADtulo1/)** | **[Lista General](https://netec-mx.github.io/PBI_ESS-Priv/)** | **[Siguiente ➡️](https://netec-mx.github.io/PBI_ESS-Priv/Cap%C3%ADtulo3/)**|
| | ||

---
## Instrucciones:

**Descripción:** Después de construir un modelo de datos estructurado en la primera práctica, el siguiente paso es transformar esa base en un informe funcional, claro y orientado al análisis. A partir de las relaciones entre productos, regiones, revendedores y periodos de tiempo, tu objetivo será crear visualizaciones que destaquen patrones clave y faciliten la exploración de los datos.

Esta práctica se enfoca en diseñar una experiencia visual efectiva utilizando segmentaciones, jerarquías, tooltips y gráficos adecuados para cada tipo de información. El objetivo es que el informe final no solo comunique datos, sino que también permita interactuar con ellos de forma intuitiva y con criterio analítico.

> 💡***Nota:** En esta práctica utilizarás el archivo resultante del laboratorio anterior: **PBI_ESS_PRIV.pbix***.

---

### Tarea 1. Diseñar la primera página del informe.

1. En el panel de **Vistas**, selecciona la opción **Vista de informe**.

2. En la parte inferior, añade una página para trabajar en un nuevo **lienzo de informe**.

![img4](../images/Capitulo3/img4.png) 

En este ejercicio, diseñarás un informe.

3. Agregar una página nueva en el informe. Para cambiar el nombre de la página en Power BI Desktop, en la parte inferior izquierda, haga clic con el botón derecho en **Página 2**, elija **Cambiar nombre de página** y dele el nombre **Información general**.

    > *Sugerencia: También puede hacer doble clic en el nombre de la página para cambiarle el nombre.*

4. Para añadir una imagen, ve a la pestaña **Insertar** en la cinta de opciones. En el grupo **Elementos**, selecciona **Imagen**.

    ![Insertar Imagen](../images/Capitulo2/07-design-report-in-power-bi-desktop_image15.png)

5. En la ventana **Abrir**, dirígete a la carpeta del repositorio del curso.
6. Selecciona el archivo **Logo.png** y, posteriormente, da clic en **Abrir**.
7. Arrastra la imagen y colócala en la esquina superior izquierda del lienzo. Usa los marcadores de guía para ajustar su tamaño.

     ![Imagen 12](../images/Capitulo2/07-design-report-in-power-bi-desktop_image17.png)

8. Para agregar una segmentación, primero anula la selección de la imagen. Para ello, haz clic en un área vacía de la página del informe. A continuación, en el panel **Visualizaciones**, selecciona el ícono de **Segmentación** .

     ![Imagen 49](../images/Capitulo2/07-design-report-in-power-bi-desktop_image18.png)

9. En el panel **Datos**, arrastra el campo **Date [Fiscal Year]** directamente (no el nivel **Año** de la jerarquía) a la segmentación **Campo**, en el panel Visualizaciones.

10. Para cambiar la segmentación de lista en una lista desplegable, ve a: **Visualizaciones ➡️ Objeto visual ➡️ Visual ➡️ Configuración de segmentación ➡️ Estilo**, y en la lista desplegable selecciona **Menú desplegable**.

    ![Estilo de segmentación](../images/Capitulo2/img1.png)

11. Ajusta el tamaño y coloca la segmentación justo debajo de la imagen. Asegúrate de que tenga el mismo ancho que la imagen.

     ![Imagen 19](../images/Capitulo2/07-design-report-in-power-bi-desktop_image20.png)

12. En la segmentación **Fiscal Year**, abre la lista desplegable, selecciona **FY2020** y luego contrae nuevamente la lista.

    > 💡***Nota:** La página del informe ahora se filtra por el año **FY2020**.*

     ![Imagen 20](../images/Capitulo2/07-design-report-in-power-bi-desktop_image21.png)

13. Haz clic en un área vacía del lienzo para anular la selección de la segmentación actual.
14. Crea una segunda segmentación usando el campo **SalesTerritory [Región]** (no en el nivel **Región** de la jerarquía).
15. Deje la segmentación en forma de lista y, después, cambie el tamaño de la segmentación y colóquela debajo de la segmentación **Fiscal Year**.

     ![Imagen 21](../images/Capitulo2/07-design-report-in-power-bi-desktop_image22.png)

16. Anule la selección de la segmentación haciendo clic en un área vacía de la página del informe.

17. Para agregar un gráfico a la página, en el panel **Visualizaciones**, seleccione el tipo de objeto visual **Gráfico de columnas apiladas y de líneas**.

     ![Imagen 51](../images/Capitulo2/07-design-report-in-power-bi-desktop_image26.png)

18. Cambie el tamaño y coloque el objeto visual para situarlo a la derecha del logotipo y que ocupe el resto del ancho de la página del informe.

     ![Imagen 26](../images/Capitulo2/07-design-report-in-power-bi-desktop_image27.png)

19. Arrastre y coloque los siguientes campos al objeto visual:

     - **Date [Month]**
     - **Sales [Sales Amount]**

20. En el panel de campos del objeto visual (situado debajo del panel **Visualizaciones**), fíjese en que los campos están asignados a los apartados o áreas **Eje X** y **Eje Y de columna**.

    > *Si arrastra campos a un objeto visual, se agregarán a los apartados o áreas predeterminados. Para mayor precisión, puede arrastrar campos directamente a los apartados o áreas, como hará a continuación.*

     ![Imagen 27](../images/Capitulo2/07-design-report-in-power-bi-desktop_image28_N.png)

21. En el panel **Datos**, arrastre el campo **Sales [Profit Margin]** al apartado o área **Eje Y de línea**.

     ![Imagen 28](../images/Capitulo2/img2.png)


22. Anule la selección del gráfico haciendo clic en un área vacía de la página del informe.

23. Ahora, para agregar un gráfico a la página, en el panel **Visualizaciones**, seleccione el tipo de objeto visual **Gráfico de barras apiladas**.

     ![Imagen 53](../images/Capitulo2/07-stacked-column-chart.png)

24. Cambie el tamaño y coloque el objeto visual para situarlo debajo del gráfico de columnas o líneas, y que ocupe la mitad del ancho del gráfico anterior.

     ![Imagen 33](../images/Capitulo2/07-design-report-in-power-bi-desktop_image32.png)

25. Agregue los campos siguientes a los apartados o áreas del objeto visual:

     - Eje X: **SalesTerritory [Country]**
     - Eje Y: **Sales [Sales Amount]**
     - Leyenda: **Product [Category]**

26. Anule la selección del gráfico haciendo clic en un área vacía de la página del informe.

27. Para agregar un gráfico a la página, en el panel **Visualizaciones**, haga clic en el tipo de objeto visual **Gráfico de barras apiladas**.

     ![Imagen 54](../images/Capitulo2/07-design-report-in-power-bi-desktop_image33.png)

28. Cambie el tamaño y coloque el objeto visual para que rellene el espacio restante de la página del informe.

     ![Imagen 35](../images/Capitulo2/07-design-report-in-power-bi-desktop_image34.png)

29. Agregue los campos siguientes a los apartados o áreas del objeto visual:

     - Eje Y: **Product [Category]**
     - Eje X: **Sales [Order Quantity]**

30. Para dar formato al objeto visual, abra el panel **Formato**.

     ![Imagen 3](../images/Capitulo2/07-design-report-in-power-bi-desktop_image35.png)

31. Expanda las **Barras** y el grupo **Color**, y luego establezca la propiedad **Color predeterminado** en un color de su preferencia (para complementar el gráfico de columnas o líneas).

32. Establezca la propiedad **Etiquetas de datos** como **activada**.

     ![Imagen 2](../images/Capitulo2/img3.png)

33. Guarde el archivo de Power BI Desktop.

     ![Imagen 2](../images/Capitulo2/img6.png)

*Ahora se ha completado el diseño del informe.*

---

### Tarea 2. Diseño segunda página del informe

 Para crear una nueva página, en la parte inferior izquierda, seleccione el icono de signo más y cambie el nombre de la página nueva a **Profit**.

1. Agregue segmentaciones basadas en los campos **SalesTerritory [Region]** y **Date [Fiscal Year]**. 
 
1. Usa el panel **Formato** para habilitar la opción “Seleccionar todo” (en el grupo **Configuración de la segmentación > Selección**).

1. Cambie el tamaño y coloque las segmentaciones para situarlas en el lado izquierdo de la página del informe.

1. Agregue un objeto visual de matriz, cambie su tamaño y colóquelo de al lado derecho del segmentador, en la parte superior y que ocupe el resto del ancho de la página

1. Agregue la jerarquía **Date [Fiscal]** a la matriz del apartado o área **Filas**.

1. Agregue los siguientes cinco campos de la tabla **Ventas** al apartado o área **Valores**:

     - **Sales Amount**
     - **Total Product Cost**
     - **Profit**
     - **Profit Margin**

     ![Imagen 55](../images/Capitulo2/img4.png)

1. Agregue un objeto visual **Gráfico de columnas apiladas y líneas**, cambie el tamaño y la posición para que se sitúe en la parte inferior de la matriz y rellene el ancho restante de la página.
     
1. Agregue los cuatro campos siguientes al objeto visual:

     - Eje X: **Product[Category]**
     - Eje Y columna: **Sales [Order Quantity]**
     - Eje Y linea: **Sales [Profit Margin]**

1. Aplique formato a los objetos visuales de Matriz y Gráfico de columnas apiladas y de lineas, aumentando el tamaño de la fuente y cambiando el color.

     ![Imagen 79](../images/Capitulo2/img5.png)

1. Guarde el archivo de Power BI Desktop.

*Ahora se ha completado el diseño de la segunda página.*

---

### 3. Mejora en la experiencia del usuario

#### **Sincronizar segmentaciones**

En esta tarea, sincronizará las segmentaciones **Fiscal Year** y **Región**.

1. En Power BI Desktop, en la página **Información general**, establezca la segmentación **Fiscal Year** en **FY2018**.

1. Vaya a la página **Profit** y, después, observe que la segmentación **Fiscal Year** es otro valor.

    > *Cuando las segmentaciones no están sincronizadas, pueden contribuir a la representación errónea de los datos y a la frustración de los usuarios del informe. Ahora sincronizará las segmentaciones del informe.*

1. Vuelva a la página **Información general** y, después, seleccione la segmentación **Fiscal Year**.

1. En la ficha de cinta **Ver**, desde el grupo **Mostrar paneles**, seleccione **Sincronizar segmentaciones**.

     ![Imagen 1](../images/Capitulo2/08-design-report-in-power-bi-desktop-enhanced_image13.png)

1. En el panel **Segmentaciones de sincronización** (a la izquierda del panel **Visualizaciones**), en la segunda columna (que representa la sincronización), active las casillas de las páginas **Información general** y **Profit**.

     ![Imagen 93](../images/Capitulo2/img7.png)

1. En la página **Información general**, seleccione la segmentación **Región** y sincronicela.

1. Sincronice la segmentación con las páginas **Información general** y **Profit**.

     ![Imagen 94](../images/Capitulo2/img7.png)

1. Para probar las segmentaciones de sincronización, seleccione otras opciones de filtrado y, después, compruebe que las segmentaciones sincronizadas filtran por la misma selección.

1. Para cerrar la página **Sincronizar segmentación**, selecciona la opción **Sincronizar segmentación** situada en la ficha de cinta **Vista**.

#### **Adición de marcadores y botones**

Mejorará la página **Profit** con botones, lo que permite al usuario del informe seleccionar el tipo de objeto visual que se va a mostrar.

1. Vaya a la página **Profit**. En la ficha de cinta **Ver**, desde el grupo **Mostrar paneles**, seleccione **Marcadores**.

    ![Imagen 118](../images/Capitulo2/08-design-report-in-power-bi-desktop-enhanced_image39.png)

1. En la ficha de cinta **Ver**, desde el grupo **Mostrar paneles**, seleccione **Selección**.

1. En el panel **Selección**, situado junto a uno de los elementos **Matriz**, seleccione el icono de ojo para ocultar el objeto visual.

    ![Imagen 120](../images/Capitulo2/img8.png)

1. En el panel **Marcadores**, haga clic en **Agregar**.

    > *Para cambiar el nombre del marcador, haga doble clic en él.*

    ![Imagen 121](../images/Capitulo2/08-design-report-in-power-bi-desktop-enhanced_image42.png)

1. Si el gráfico visible es el Gráfico de barras, cambie el nombre del marcador por **Gráfico de barras ON**, de lo contrario cámbielo por **Matriz ON**.

1. Para editar el marcador, en el panel **Marcadores**, desplace el cursor sobre el marcador, seleccione los puntos suspensivos y, a continuación, seleccione **Datos**.

    > *Deshabilitar la opción **Datos** significa que el marcador no usará el estado de filtro actual. Esto es importante porque, de lo contrario, el marcador se bloqueará permanentemente en el filtro aplicado actualmente por la segmentación **Fiscal Year**.*

     ![Imagen 16](../images/Capitulo2/img9.png)

1. Para actualizar el marcador, seleccione los puntos suspensivos de nuevo y, a continuación, seleccione **Actualizar**.

    > *En los pasos siguientes, creará y configurará un segundo marcador para mostrar el segundo objeto visual.*

1. En el panel **Selección**, alterne la visibilidad de los elementos.

    > *En otras palabras, oculte el objeto visual visible y haga visible el objeto visual oculto.*

1. Cree un segundo marcador y asígnele el nombre apropiado (**Matriz ON** o **Gráfico de barras ON).**

     ![Imagen 123](../images/Capitulo2/img10.png)

1. Configure el segundo marcador para omitir los filtros (opción **Datos** desactivada) y actualizar el marcador.

1. En el panel **Selección**, para que los dos objetos visuales sean visibles, basta con mostrar el objeto visual oculto.

1. Cambie el tamaño y la posición de los dos objetos visuales para que rellenen la página y se superpongan por completo.

    *Para seleccionar el objeto visual que está oculto, selecciónelo en el panel **Selección**.*

1. En el panel **Marcadores**, seleccione cada uno de los marcadores y observe que solo uno de los objetos visuales es visible.

*La siguiente fase de diseño consiste en agregar dos botones a la página, lo que permitirá al usuario del informe seleccionar los marcadores.*

1. En la cinta **Insertar**, desde el grupo **Elementos**, seleccione **Botón** y, después, seleccione **En blanco**.

     ![Imagen 125](../images/Capitulo2/img11.png)

1. Coloque el botón directamente debajo de las segmentaciones.

1. Seleccione el botón y, después, en el panel **Botón de formato**, seleccione **Botón**, expanda la sección **Estilo** y establezca la propiedad **Texto** del botón en **Activado**.

     ![Imagen 126](../images/Capitulo2/img12.png)

1. Expanda la sección **Texto** y, a continuación, en el cuadro **Texto**, escriba **Matriz**.

1. Expanda la sección **Rellenar** y, a continuación, establezca un color de fondo mediante un color complementario.

1. Seleccione **Botón** y establezca la propiedad **Acción** en **Activado**.

    ![Imagen 127](../images/Capitulo2/img13.png)

1. Expanda la sección **Acción** y, después, establezca la lista desplegable **Tipo** en **Marcador**.

1. En la lista desplegable **Marcador**, seleccione **Matriz ON**.

    ![Imagen 128](../images/Capitulo2/img14.png)

1. Cree una copia del botón mediante copiar y pegar y, después, configure el botón nuevo de la siguiente manera:

    *Sugerencia: Los comandos de acceso directo para copiar y pegar son **Ctrl+C** seguido de **Ctrl+V**.*

    - Establezca la propiedad **Texto del botón** en **Gráfico de barras**.
    - En la sección **Acción**, establezca la lista desplegable **Marcador** en **Gráfico de barras ON**.

*Ahora se ha completado el diseño del informe*

---
### Resultado esperado

Al finalizar el laboratorio se espera que el resultado sea similar a la siguiente imágen:

![result1](../images/Capitulo2/resultado1.png) 

![result2](../images/Capitulo2/Resultado2.png)

---
