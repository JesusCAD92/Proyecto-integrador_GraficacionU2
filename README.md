# Proyecto-integrador_GraficacionU2
## 1. Configuración Inicial (El Lienzo)
1) **Abrir Blender:** Al iniciar, selecciona 2D Animation en la pantalla de bienvenida. Esto te dará un lienzo blanco y las herramientas de dibujo listas.

2) **Importar Referencia:** Presiona Shift + A > Image > Reference.

* Busca tu imagen de los 8 pasos (image_27.png).
<img width="512" height="279" alt="image" src="https://github.com/user-attachments/assets/16ab8add-f623-4ccc-9659-6848c21b4859" />

* En el panel de la derecha (Propiedades de la imagen), baja la Opacity a 0.5 para que no estorbe al dibujar encima.

* Muévela con G para que el primer pájaro quede en el centro.
## 2. Dibujo de las Poses Clave (Keyframes)
Blender usa una línea de tiempo abajo. Vamos a colocar cada pose en un punto específico.
1) **Capa de Líneas:** En el panel de capas (derecha superior), asegúrate de estar en la capa Lines.

2) **Pose 1 (Frame 1):** Dibuja el contorno del ave siguiendo tu referencia. No te preocupes por el color aún, solo la línea.

3) **Pose 2 (Frame 3 o 5):** Avanza unos cuantos frames en la línea de tiempo. Mueve tu imagen de referencia hacia la izquierda para alinear el pájaro "2" con el centro y dibújalo.

* Tip: Activa el Onion Skinning (el icono de dos cuadrados arriba a la derecha) para ver una sombra del dibujo anterior y que no se te pierda la proporción.
4) **Repetir:** Haz lo mismo para las 8 poses. Te recomiendo dejar un espacio de 2 a 4 frames entre cada dibujo para que la animación no vaya demasiado rápido.
##  3. Aplicación de Color (Materiales)
Aquí es donde usaremos los códigos que definimos antes.

1) Crear Materiales: Ve a la pestaña de Material Properties (el icono de la esfera roja).

2) Color del Cuerpo (Azure Blue):

* Crea un nuevo material, llámalo "Cuerpo".

* Cambia el estilo de Stroke (línea) a Fill (relleno).

* En Base Color, haz clic en el color y pega el código HEX: #007FFF.

3) **Color de la Panza (Cream):** Repite el proceso con el código #FAF3E0.

4) **Pintar:** Cambia al modo Draw y selecciona la herramienta Fill (el bote de pintura). Haz clic dentro de tus dibujos en la capa de "Fills".
## 4. Creación del Loop (Ciclo Infinito)
Para que el ave vuele sin parar sin tener que dibujar mil veces:

1) Abre la ventana Dope Sheet (suele estar abajo).

2) Cambia el modo de la Dope Sheet a Grease Pencil.

3) Selecciona todos tus puntos (frames) con la tecla A.

4) Presiona Shift + D para duplicarlos y ponlos justo después del frame 8.
## Ejemplo visual del resultado final 



https://github.com/user-attachments/assets/bfa7e12c-6416-40a6-a85b-49edf50b6224



## Conclusión
La animación frame por frame (cuadro por cuadro) es la esencia pura del movimiento digital. A través de este proyecto, se demuestra que la fluidez de una acción compleja, como el vuelo de un ave, no es más que la suma de decisiones anatómicas y temporales precisas.
### Puntos Clave del Proyecto
* **Descomposición del Movimiento:** El éxito de la animación no radica en el dibujo final, sino en la capacidad de analizar la realidad. Al identificar las 8 poses clave (desde el contacto inicial hasta el empuje de potencia), transformamos un fenómeno biológico en un algoritmo visual lógico y repetible.

* **Sinergia Tecnológica:** La implementación en Blender utilizando el Grease Pencil permite cerrar la brecha entre el dibujo artesanal y el entorno 3D. El uso de capas, materiales con códigos de color específicos (HEX/RGB) y modificadores de looping optimiza un proceso que antiguamente tomaba semanas, permitiendo una iteración rápida y profesional.

* **Documentación y Escalabilidad:** Al alojar este proceso en un repositorio de GitHub, el proyecto deja de ser un simple ejercicio visual para convertirse en un recurso de software. La estructura organizada de archivos (assets, frames, src) asegura que la animación sea entendible, reproducible y lista para ser integrada en aplicaciones o videojuegos.<br>
<br>Animar cuadro por cuadro es entender que el movimiento es una ilusión técnica. Este proyecto integra la observación científica, la destreza artística y la gestión de activos digitales, sentando las bases para cualquier desarrollo multimedia de alto nivel.
