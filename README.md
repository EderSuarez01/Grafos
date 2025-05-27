#Grafo No Dirigido en PHP

Este proyecto implementa una estructura de datos tipo **grafo no dirigido** utilizando PHP. El código permite agregar nodos (también llamados vértices), establecer conexiones (aristas) entre ellos y visualizar el grafo resultante. Es un ejemplo simple pero claro de cómo representar relaciones entre elementos usando listas de adyacencia.

---

##Estructura del Código

El programa está compuesto por una clase principal:

- **`Grafo`**: Contiene dos propiedades principales:
  - `$nodos`: Un arreglo que almacena los nombres de todos los nodos del grafo.
  - `$conexiones`: Un arreglo asociativo que representa la lista de adyacencia, es decir, las conexiones entre los nodos.

Además, la clase `Grafo` incluye tres métodos fundamentales:

- `agregarNodo($nombreNodo)`: Añade un nodo al grafo.
- `agregarConexion($nodo1, $nodo2)`: Conecta dos nodos entre sí, ya que es un grafo no dirigido, ambos se enlazan mutuamente.
- `imprimirGrafo()`: Recorre todos los nodos y muestra con quién está conectado cada uno.

---

##Funcionamiento

El código crea un grafo con los nodos "A", "B", "C" y "D". Luego establece conexiones entre ellos:
- A está conectado con B
- B está conectado con C
- C está conectado con A
- B está conectado con D

Finalmente, se imprime el grafo en formato de texto. Por ejemplo:
