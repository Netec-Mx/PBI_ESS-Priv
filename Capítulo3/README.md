# Práctica 3. Exploración de Power BI Service y Creación de Dashboard

## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:
- Publicar y compartir informe al servicio de Power BI
- Crear un dashboard interactivo.
- Diseñar el informe para dispositivos móviles

## Duración aproximada:
- 80 minutos.

## Instrucciones 
<!-- Proporciona pasos detallados sobre cómo configurar y administrar sistemas, implementar soluciones de software, realizar pruebas de seguridad, o cualquier otro escenario práctico relevante para el campo de la tecnología de la información -->
### Tarea 1. Iniciar sesión y crear un área de trabajo

1. Abre tu navegador e ingresa a: [https://app.powerbi.com](https://app.powerbi.com)
2. Inicia sesión con tu cuenta de Power BI.
    ![img1](../images/Capitulo3/img1.png)
3. En el panel izquierdo, haz clic en **Áreas de trabajo > Crear un área de trabajo**.
    
    ![img2](../images/Capitulo3/img2.png)
4. Asigna un nombre: **Informes de ventas** (o un nombre relacionado al proyecto)
5. Opcional: agrega una descripción y agrega una imágen al área de trabajo
    ![img3](../images/Capitulo3/img3.png)
6. Haz clic en **Guardar**.

---
### Tarea 2. Publicar el informe en Power BI Service

1. Abre el archivo `PBI_ESS_PRIV.pbix` en Power BI Desktop.
2. En la cinta de opciones, selecciona **Inicio > Publicar**.
    ![img4](../images/Capitulo3/img4.png)
4. Inicia sesión con tu cuenta de Power BI (Ahora en la aplicación de escritorio).
    ![img5](../images/Capitulo3/img5.png)
5. Selecciona el área de trabajo creada: **Informes de ventas** (O el área de trabajo creda con el nombre relacionado al proyecto).
    ![img6](../images/Capitulo3/img6.png)
6. Dar clic en **Seleccionar**.
    ![img7](../images/Capitulo3/img7.png)

---
### Tarea 3. Verificar la publicación en el servicio Power BI

1. Abre tu navegador e ingresa a [https://app.powerbi.com](https://app.powerbi.com).
1. Navega al área de trabajo creada **Informes de ventas**
    ![img8](../images/Capitulo3/img8.png)
1. Abre el informe recientemente publicado.
    ![img9](../images/Capitulo3/img9.png)
1. Revisa que las visualizaciones se comporten como en Power BI Desktop.

---

### Tarea 4. Compartir el reporte con otros usuarios

> ***Nota:** Esta funcionalidad requiere que tanto tú como el destinatario tengan licencias Power BI Pro o acceso a capacidad Premium.*

1. Abre el informe desde el servicio.
1. En la cinta superiror, haz clic en **Compartir**.
1. Escribe el correo de otro usuario dentro de tu organización.
1. Añade un mensaje personalizado y haz clic en **Enviar**.
    ![img10](../images/Capitulo3/img10.png)
1. Confirma que el usuario tenga acceso al área de trabajo.

> ***Nota:** Si te compartieron un área de trabajo, revisa que ahora cuenta con acceso a la misma y explore los informes allí publicados.*

---
### Tarea 5. Explorar la relación entre reportes y datasets

1. En el panel lateral, accede al área de trabajo creada **Informes de ventas**.
1. Verifica que el dataset (modelo semántico) asociado al informe tiene el mismo nombre y abre el archivo.
1. En la cinta de opciones superior, dar clic en **Linaje > Abrir linaje del área de trabajo**
    ![img11](../images/Capitulo3/img11.png)
1. Revisar los elementos del linaje del informe publicado.
    ![img12](../images/Capitulo3/img12.png)

1. Crea un nuevo informe desde ese dataset:
   - Haz clic en los tres puntos (…) > **Crear informe Automático**.
        ![img13](../images/Capitulo3/img13.png)

    > ***Nota:** El informe creado puede variar su resultado dada la funcionalidad automática.*
    
    ![img14](../images/Capitulo3/img14.png)

   - En la cinta superiror seleccionar la opción **Guardar**, selecciona el área de trabajo y especifica un nombre para guardar el informe creado.
    ![img15](../images/Capitulo3/img15.png)

   - Guarda el informe.

> ***Nota:** Así compruebas que múltiples reportes pueden reutilizar un mismo modelo de datos publicado.*

![img16](../images/Capitulo3/img16.png)

---

### 5. Crear dashboard

#### 5.1 Fijar visualizaciones a un dashboard

1. Abre el informe publicado **PBI_ESS_PRIV**.
1. En la página **Información General**, posiciona el mouse sobre el **gráfico combinado de Columnas y lineas**.
1. Haz clic en el ícono de **pin(📌)**.
    ![img17](../images/Capitulo3/img17.png)
1. En la ventana emergente:
   - Elige **Nuevo panel**.
   - Nombra el dashboard: `Panel Ejecutivo de Ventas`.
   - Haz clic en **Anclar**.
   ![img18](../images/Capitulo3/img18.png)

> ***Nota:** Al anclar el primer objeto visual se crea el dashboard. Puede ingresar desde el área de trabajo y lo encuentras con el nombre anteriormente especificado.*

5. Fijar nuevos elmentos de los informes:
   - PBI_ESS_PRIV
   - PBI_ESS_PRIV AUTO
1. Verifica que los elementos fijados se visualicen correctamente.
    
    ![img19](../images/Capitulo3/img19.png)

---
### 7. Diseñar vista para dispositivos móviles

1. En el dashboard, haz clic en **Editar > Diseño para móviles**.

    ![img20](../images/Capitulo3/img20.png)
2. Reorganiza los tiles (Iconos) verticalmente para que se adapten a pantallas pequeñas.

    ![img21](../images/Capitulo3/img21.png)

    ![img22](../images/Capitulo3/img22.png)


3. Regresa al diseño del dashboard. Dar clic en **Diseño Web** en la vista de diseño móvil.

    ![img23](../images/Capitulo3/img23.png)

---
### Resultado esperado

Al finalizar el laboratorio se espera que el resultado sea similar a la siguiente imágen:
![img9](../images/Capitulo3/img9.png)
![img19](../images/Capitulo3/img19.png)
![img24](../images/Capitulo3/img24.png)

---

¡Felicidades! Con esta práctica concluyes el ciclo completo de un flujo profesional de trabajo en Power BI: desde la conexión a datos hasta la publicación y consumo final del análisis.



