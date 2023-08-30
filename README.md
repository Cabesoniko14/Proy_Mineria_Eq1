# Proyecto Minería de Datos: sonidos de aves

<img src="md_format/pajarito.jpg" alt="Pajarito" style="width:400px; height:250px;">

Trabajo del semestre Otoño 2023, ITAM.

Integrantes del **Equipo 1**:
  - Isaac Pimentel
  - David González
  - Javier Nieto
  - Rubén Robles
  - Daniel Díaz Barriga


## Índice

- [Definición del problema](#Definición-del-problema)
  - [Objetivo general](#Objetivo-general)
  - [Objetivos específicos](#Objetivos-específicos) 
- [Alcances y limitaciones](#Alcances-y-limitaciones)
- [Datos](#Datos)
- [Referencias](#Referencias)
- [Format dump](#Format-dump)

## Definición del problema

Definir tan claro como sea posible. Se puede enriquecer con la definición de objetivos generales y específicos, si los hay.

### Objetivo general

### Objetivos específicos

## Alcances y limitaciones

En la medida de lo posible, tratar de definir el scoping (lo refinaremos para la segunda presentación). Definir alcances y limitaciones.

**Imporante:** Qué vamos a hacer y qué no vamos a hacer.

## Datos

Presentar su primera revisión de los datos.
 - **Origen:** de dónde se consiguieron los datos, quién los juntó y con qué fin
 - **Forma:** si es tabular, o son imágenes, perfiles de imágenes, series de tiempo, etc.
 - **Tamaño de la base de datos:** cuál es el *número de registros*, cuál es el *número de variables*
 - **Tipo de variables:** numéricos, categóricos, etc.
 - **Datos faltantes:** dónde, cuántos, qué se harán con ellos

## Referencias

 - Incluir libros, artículos, URLs.
 - Si hay algún artículo donde se describa el problema, o donde ya se haya resuelto
 - De dónde salieron los datos

## Format dump

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





