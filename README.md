# Código del meetup de Realidad Aumentada de #campusFA
Código del meetup de Realidad Aumentada de #campusFA
El acceso al vídeo y resumen del evento se hará desde la propia web del [#campusFA](https://www.fundacionayesa.org/realidad-aumentada-con-unity-y-vuforia/).

## Cómo importar el proyecto
El código del proyecto está en formato de unitypackage. Para importarlo simplemente crear un proyecto nuevo y doble clic en el archivo. 

## Cosas a tener en cuenta para ejecutar el proyecto
Es importante tener una versión actualizada de Unity (el proyecto está realizado con la versión 2017.2.0f3 personal)
Además, debe tener instalados los componentes de Vuforia (aparecen en el instalador, en la pantalla de "Choose Components". El componente se llama "Vuforia Augmented Reality Support"
Por otro lado, este proyecto utiliza la base de datos de Vuforia, la clave de API y los marcadores que se han utilizado en la charla. Deberéis registraros en el [portal de desarrolladores de Vuforia](https://developer.vuforia.com/) para poder utilizar vuestra propia clave de API y marcadores.

## Escenas del proyecto
Se adjuntan las siguientes escenas dentro de Unity:
- Inicio: Trae todo lo necesario para probar la detección de marcadores.
- Meetup: El "HolaMundo" que generamos durante la charla. 
- Gravedad: Los pequeños proyectos de gravedad. También incorpora el script para hacer que la gravedad vaya en otra dirección.
- Cubo: Ejemplo de uso de MultiMarkers para hacer el seguimiento de cuboides.

## Autores
- **Rafael Caro** - [Racafe92](https://github.com/Racafe92)
- Modelos 3D obtenidos de la Asset Store de Unity

Todo el código es libre de ser distribuido y modificado bajo la licencia Apache v2.0
