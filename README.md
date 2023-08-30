# Proyecto Minería de Datos: sonidos de aves

<img src="md_format/pajarito.jpg" alt="Pajarito" style="width:400px; height:250px;">


Integrantes del equipo:
  - Isaac Pimentel
  - David González
  - Javier Nieto
  - Rubén Robles
  - Daniel Díaz Barriga


## Índice

- [Parte 1](#Parte-1)
- [Parte 2](#Parte-2)
- [Parte 3](#Parte-3)
  -  [Subtema 1](#Subtema-1) 
  -  [Subtema 2](#Subtema-2) 

## Parte 1

Texto

Code snippet

<pre> <code id="codeSnippet"># Ejecutar en la interfaz:

CALL gds.graph.create('pinturasYArtistas', ['Artista', 'Pintura'], ['PINTADA_POR']) YIELD graphName AS graph, nodeProjection, nodeCount AS nodes, relationshipCount AS rels;

# Luego, ejecturar:

CALL gds.pageRank.stream('pinturasYArtistas') YIELD nodeId, score RETURN gds.util.asNode(nodeId).nombre AS nombre, score ORDER BY score DESC, nombre ASC</code></pre>

Ejemplo de un cuadro de comentarios

> **¡Antes de empezar!** Es importante que tengas prendida tu instancia de AWS y Docker prendido. Decidimos dejar de fuera un inicio de sesión directo con AWS en Python para no comprometer credenciales en el código.

Ejemplo de cajitas para variables

Variable: <code>pajarito_verde</code>


## Parte 2

Texto

## Parte 3

Texto

### Subtema 1

Texto

### Subtema 2

Texto

