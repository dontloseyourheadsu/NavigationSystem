# Manual de Usuario para el Sistema de Navegación Basado en Grafos

Este manual explica cómo utilizar los módulos del sistema de navegación basado en grafos que implementa el algoritmo de Dijkstra. Incluye instrucciones para trabajar localmente y alternativas en línea disponibles en CodePen.

## Requisitos Previos

- Software necesario:
  - Un navegador web moderno (Google Chrome, Mozilla Firefox, etc.).
  - Visual Studio Code (opcional, para una experiencia más integrada).
  - Extensión Live Server para Visual Studio Code (opcional).

- Archivos necesarios:
  - Clonar o descargar el repositorio [NavigationSystem](https://github.com/dontloseyourheadsu/NavigationSystem), que contiene los directorios `GraphCreator` y `DijkstraPathFinding`.

## Pasos para Utilizar el Sistema

### 1. Clonar el Repositorio

1. Abre una terminal o consola en tu computadora.
2. Ejecuta el siguiente comando para clonar el repositorio:
   ```
   git clone https://github.com/dontloseyourheadsu/NavigationSystem.git
   ```
3. Navega al directorio del proyecto con:
   ```
   cd NavigationSystem
   ```

### 2. Utilizar el Módulo GraphCreator

Este módulo permite crear un grafo de manera interactiva y exportarlo como un archivo JSON.

1. Dirígete al directorio `GraphCreator` con:
   ```
   cd GraphCreator
   ```
2. Abre el archivo html en un navegador web. Si estás usando Visual Studio Code con Live Server:
   - Abre Visual Studio Code.
   - Selecciona el directorio `GraphCreator`.
   - Abre el archivo html.
   - Haz clic en el botón "Go Live" para visualizar la interfaz en tu navegador.
3. Usa la interfaz para dibujar nodos y aristas en el lienzo interactivo.
4. Una vez que termines de crear el grafo, exporta el diseño como un archivo JSON haciendo clic en el botón **Exportar**.

### 3. Utilizar el Módulo DijkstraPathFinding

Este módulo permite cargar un grafo desde un archivo JSON y calcular la ruta más corta entre dos nodos.

1. Ve al directorio `DijkstraPathFinding` con:
   ```
   cd ../DijkstraPathFinding
   ```
2. Abre el archivo html en un navegador web. Si estás usando Visual Studio Code con Live Server:
   - Abre Visual Studio Code.
   - Selecciona el directorio `DijkstraPathFinding`.
   - Abre el archivo html.
   - Haz clic en el botón "Go Live".
3. En la interfaz, utiliza el botón **Cargar Grafo** para importar el archivo JSON que generaste en el módulo GraphCreator.
4. Selecciona dos nodos en el grafo:
   - Uno como punto de inicio.
   - Otro como destino.
5. El sistema calculará la ruta más corta entre los dos nodos seleccionados utilizando el algoritmo de Dijkstra y resaltará la ruta en el grafo.

## Alternativas en Línea

Si no deseas trabajar localmente, puedes usar las versiones en línea de los módulos en CodePen:
- [GraphCreator](https://codepen.io/dontloseyourheadsu/pen/qEWOWvx): Permite crear un grafo interactivo y exportarlo como JSON.
- [DijkstraPathFinding](https://codepen.io/dontloseyourheadsu/pen/LEPpYGJ): Carga un archivo JSON y calcula rutas óptimas.

## Notas Adicionales

- Usa un navegador moderno para garantizar la compatibilidad.
- La extensión Live Server es opcional, pero simplifica el uso local del sistema.
- Si encuentras errores, revisa la consola del navegador para obtener detalles.

## Créditos

- Jesús Alvarez Sombrerero: Creación del sistema para dibujar el grafo en un lienzo interactivo y generación de JSON.
- Camila García Alvarez: Implementación del cálculo de rutas más cortas con Dijkstra y visualización de resultados.

Para más información, consulta el repositorio oficial: [NavigationSystem](https://github.com/dontloseyourheadsu/NavigationSystem).
