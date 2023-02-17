Programacion Movil 2



MarsPhotos
==================================

Código de inicio descargado de [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course).

Introduccion
------------

Se creo la app MarsPhotos, una aplicación de demostración que muestra imágenes reales de la superficie de Mar. estas imagenes son fotos de la vida real de Marte capturadas por los rovers de Marte de la NASA. Los datos se almacenan en un servidor web como un servicio web REST. La aplicación usa la implementacion de [Retrofit](https://square.github.io/retrofit/) para realizar solicitudes REST al servicio web, [Moshi](https://github.com/square/moshi) y para manejar la deserialización del JSON devuelto a los objetos de datos de Kotlin, y [Coil](https://coil-kt.github.io/coil/) para cargar imágenes por URL.

La aplicación también aprovecha [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), y
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) con binding 
adapters.

---------------
Necesitas saber:
- Cómo crear y usar fragmentos.
- Cómo usar los componentes de la arquitectura, incluidos ViewModel y LiveData.
- Cómo usar rutinas para tareas de larga duración
