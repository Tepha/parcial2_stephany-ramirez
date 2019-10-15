# parcial2_stephany-ramirez

La aplicación arranca desde el login, donde los usuarios registrados pueden ingresan con su nombre de usuario y clave. Se cuenta con la posibilidad de poder registrarse para el caso de los usuarios nuevos en la sección de registrar (estas 2 secciones son las únicas visibles en tanto no se ingrese con un usuario y una clave válidas).

La aplicación arranca desde el login, donde los usuarios registrados pueden ingresan con su nombre de usuario y clave. Se cuenta con la posibilidad de poder registrarse para el caso de los usuarios nuevos en la sección de registrar (estas 2 secciones son las únicas visibles en tanto no se ingrese con un usuario y una clave válidas).

Una vez logueado en el sistema, se muestran las últimas ventas registradas desde un archivo CSV principal; desde allí se pueden realizar cualquiera de las 4 consultas solicitadas por el trabajo en la barra de navegación:

Productos por Cliente
Clientes por Producto
Productos más vendidos
Clientes que más gastaron
En cada uno se ofrece la posibilidad de poder descargar en nuestra máquina la consultas efectuadas en formato CSV.

También desde la misma barra de navegación se puede ver en el extremo derecho el nombre del usuario logueado, desde el cual se puede hacer clic para ver las opciones de cambiar clave o salir del sistema (desloguearse y volver a la sección de login).

Consultas: Clase que también recibe en su constructor un nombre de archivo como fuente de datos y un archivo log para guardar errores. Esta misma clase instancia un objeto de la clase Csv, y si la validación del CSV en esta última es correcta entonces la clase Consultas brinda los métodos necesarios para realizar todas las consultas de datos que se pueden hacer a lo largo del sitio.

Valores: Clase que recibe solamente un nombre de campo y que representa en forma de "lista de listas" los resultados utilizados en uno de los métodos de la clase Consultas. En concreto, contiene los métodos necesarios para encontrar, sumar, agregar, ordenar/recortar/devolver los resultados en dicha lista.
