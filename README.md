# Amigo Secreto

Este proyecto web permite gestionar una lista de nombres para realizar un sorteo al estilo "Amigo Secreto". La aplicación está desarrollada con HTML, CSS y JavaScript, y se incluye la siguiente funcionalidad:

## Funcionalidades

- **Agregar amigos:**  
  Permite al usuario ingresar nombres en un campo de texto.  
  - Se valida que el campo no esté vacío, mostrando un mensaje de error en caso de entrada vacía.
  - Los nombres válidos se agregan a un array interno.
  - Se actualiza dinámicamente una lista HTML que muestra todos los nombres ingresados.

- **Sorteo aleatorio:**  
  Permite seleccionar de forma aleatoria uno de los nombres agregados.
  - Se verifica que existan nombres en la lista.
  - Se utiliza `Math.random()` para generar un índice aleatorio.
  - El nombre seleccionado se muestra en la interfaz.

## Uso

1. Abra el archivo `index.html` en su navegador.
2. Ingrese un nombre en el campo de texto y haga clic en el botón **"Añadir"** para agregarlo a la lista.
3. Una vez agregados uno o más nombres, haga clic en el botón **"Sortear amigo"** para seleccionar de manera aleatoria un nombre de la lista.
